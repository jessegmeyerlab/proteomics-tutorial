# A Practical Beginner's Guide to Proteomics

<!-- usage note: edit the H1 title above to personalize the manuscript -->

[![HTML Manuscript](https://img.shields.io/badge/manuscript-HTML-blue.svg)](https://jessegmeyerlab.github.io/proteomics-tutorial/)
[![PDF Manuscript](https://img.shields.io/badge/manuscript-PDF-blue.svg)](https://jessegmeyerlab.github.io/proteomics-tutorial/manuscript.pdf)
[![GitHub Actions Status](https://github.com/jessegmeyerlab/proteomics-tutorial/workflows/Manubot/badge.svg)](https://github.com/jessegmeyerlab/proteomics-tutorial/actions)

^^^ click the links above to see the current manuscript in HTML or PDF format!! ^^^

## Project information

**Purpose.** We are collaboratively writing a broad, basic tutorial on proteomics invited by the ACS journal [Measurement Science Au](https://pubs.acs.org/journal/amachv). Anyone is welcome to contribute! An example of the scope and style is [this tutorial from Jillian Dempsy's group on cyclic voltammetry](https://pubs.acs.org/doi/full/10.1021/acs.jchemed.7b00361). We are using [Manubot](https://github.com/manubot/manubot) to write this manuscript and track contributions. See the remaining readme below this section or at the link above for more information about manubot. **We are aiming to submit by the end of 2022.**

**Authorship.** I (Jesse Meyer) am leading this project as senior author, and we will decide author order for everyone else based on the contributions recorded via github. The minimum suggested contribution for authorship is five coherent and well referenced paragraphs. Authorship can also be awarded for helping with reviewing new contributions (pull requests), editing, or by making figures and tables. 

The author order in the pdf and html versions is currently set to random to indicate that the order is up in the air until the first draft of the paper is complete.

**Rules.** 
See also [the code of conduct](https://github.com/jessegmeyerlab/proteomics-tutorial/blob/main/CODE_OF_CONDUCT.md) for participants. 

## **How to contribute:**
Edit sections in the /content directory and create a pull request describing your changes. You can practice contributing [here](https://github.com/manubot/try-manubot). 
See the [contributing section](https://github.com/jessegmeyerlab/proteomics-tutorial/blob/main/contributing.md) for guidance on how to contribute and what is expected of authors. 

[** PLEASE CHECK OUT THIS HELP VIDEO FIRST**](https://manubot.org/docs/getting-started.html) and also [this step-by-step guide](https://github.com/greenelab/covid19-review/blob/master/CONTRIBUTING.md) for the COVID-19 review by @rando2.

See also this [additional information](https://github.com/greenelab/covid19-review/blob/master/INSTRUCTIONS.md) in the COVID review project.

**Use Issues** to discuss organization, potential figures, and discussion of papers.

**Focus Areas** of this tutorial include an entire overview of topics that are relevant to mass spectrometry based proteomics. The current list of sections includes:

1. Introduction
2. protein extraction
3. proteolysis
4. Peptide and protein labeling
5. enrichment of proteins or modifications 
6. peptide purification
7. types of mass spectrometers used for proteomics
8. Peptide ionization
9. Data Acquisition (targeted and untargeted DDA and DIA)
10. Basics of data analysis
11. Biological Interpretation
12. Experiment design and considerations not discussed elsewhere


## Manubot

<!-- usage note: do not edit this section -->

Manubot is a system for writing scholarly manuscripts via GitHub.
Manubot automates citations and references, versions manuscripts using git, and enables collaborative writing via GitHub.
An [overview manuscript](https://greenelab.github.io/meta-review/ "Open collaborative writing with Manubot") presents the benefits of collaborative writing with Manubot and its unique features.
The [rootstock repository](https://git.io/fhQH1) is a general purpose template for creating new Manubot instances, as detailed in [`SETUP.md`](SETUP.md).
See [`USAGE.md`](USAGE.md) for documentation how to write a manuscript.

Please open [an issue](https://git.io/fhQHM) for questions related to Manubot usage, bug reports, or general inquiries.

### Repository directories & files

The directories are as follows:

+ [`content`](content) contains the manuscript source, which includes markdown files as well as inputs for citations and references.
  See [`USAGE.md`](USAGE.md) for more information.
+ [`output`](output) contains the outputs (generated files) from Manubot including the resulting manuscripts.
  You should not edit these files manually, because they will get overwritten.
+ [`webpage`](webpage) is a directory meant to be rendered as a static webpage for viewing the HTML manuscript.
+ [`build`](build) contains commands and tools for building the manuscript.
+ [`ci`](ci) contains files necessary for deployment via continuous integration.

### Local execution

The easiest way to run Manubot is to use [continuous integration](#continuous-integration) to rebuild the manuscript when the content changes.
If you want to build a Manubot manuscript locally, install the [conda](https://conda.io) environment as described in [`build`](build).
Then, you can build the manuscript on POSIX systems by running the following commands from this root directory.

```sh
# Activate the manubot conda environment (assumes conda version >= 4.4)
conda activate manubot

# Build the manuscript, saving outputs to the output directory
bash build/build.sh

# At this point, the HTML & PDF outputs will have been created. The remaining
# commands are for serving the webpage to view the HTML manuscript locally.
# This is required to view local images in the HTML output.

# Configure the webpage directory
manubot webpage

# You can now open the manuscript webpage/index.html in a web browser.
# Alternatively, open a local webserver at http://localhost:8000/ with the
# following commands.
cd webpage
python -m http.server
```

Sometimes it's helpful to monitor the content directory and automatically rebuild the manuscript when a change is detected.
The following command, while running, will trigger both the `build.sh` script and `manubot webpage` command upon content changes:

```sh
bash build/autobuild.sh
```

### Continuous Integration

Whenever a pull request is opened, CI (continuous integration) will test whether the changes break the build process to generate a formatted manuscript.
The build process aims to detect common errors, such as invalid citations.
If your pull request build fails, see the CI logs for the cause of failure and revise your pull request accordingly.

When a commit to the `main` branch occurs (for example, when a pull request is merged), CI builds the manuscript and writes the results to the [`gh-pages`](https://github.com/jessegmeyerlab/proteomics-tutorial/tree/gh-pages) and [`output`](https://github.com/jessegmeyerlab/proteomics-tutorial/tree/output) branches.
The `gh-pages` branch uses [GitHub Pages](https://pages.github.com/) to host the following URLs:

+ **HTML manuscript** at https://jessegmeyerlab.github.io/proteomics-tutorial/
+ **PDF manuscript** at https://jessegmeyerlab.github.io/proteomics-tutorial/manuscript.pdf

For continuous integration configuration details, see [`.github/workflows/manubot.yaml`](.github/workflows/manubot.yaml).

## License

<!--
usage note: edit this section to change the license of your manuscript or source code changes to this repository.
We encourage users to openly license their manuscripts, which is the default as specified below.
-->

[![License: CC BY 4.0](https://img.shields.io/badge/License%20All-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)
[![License: CC0 1.0](https://img.shields.io/badge/License%20Parts-CC0%201.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

Except when noted otherwise, the entirety of this repository is licensed under a CC BY 4.0 License ([`LICENSE.md`](LICENSE.md)), which allows reuse with attribution.
Please attribute by linking to https://github.com/jessegmeyerlab/proteomics-tutorial.

Since CC BY is not ideal for code and data, certain repository components are also released under the CC0 1.0 public domain dedication ([`LICENSE-CC0.md`](LICENSE-CC0.md)).
All files matched by the following glob patterns are dual licensed under CC BY 4.0 and CC0 1.0:

+ `*.sh`
+ `*.py`
+ `*.yml` / `*.yaml`
+ `*.json`
+ `*.bib`
+ `*.tsv`
+ `.gitignore`

All other files are only available under CC BY 4.0, including:

+ `*.md`
+ `*.html`
+ `*.pdf`
+ `*.docx`

Please open [an issue](https://github.com/jessegmeyerlab/proteomics-tutorial/issues) for any question related to licensing.
