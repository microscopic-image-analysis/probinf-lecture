# Probabilistic Inference

This repository contains lecture materials for the Probabilistic Inference lecture (currently WS 22/23) at Uni Jena.

For an overview over the lecture, have a look at [Overview.md](Overview.md)

## Repository Structure

The lecture is written using [quarto](https://quarto.org). To render the lecture(s) to different output formats (pdf, html, jupyter notebooks, ...)
you need to install `quarto` (see [below](#prerequisites)).

The main file is called  [lecture.qmd](lecture.qmd), which is a short file that simply includes all files in the [lectures](lectures) folder.
The lecture folder contains one file for each lecture/day.

## Rendering the lecture

The lecture can be rendered to different output formats using `quarto`

### Prerequisites

* Install [quarto](https://quarto.org/docs/get-started/)
* Install python dependencies
    * It's best to do this in a dedicated virtual (python-) environment. See [below](#optional-creating-a-python-virtual-environment) how to create one.
    * Install all required dependencies
        * To install the exact requirements used by the authors: `pip install -r requirements.txt`
* If you want to render the lecture to pdf, you also need a working distribution of TeX.
    * If you don't have TeX installed, the easiest way to do this is to run `quarto install tool tinytex`
    * See the [relevant section](https://quarto.org/docs/output-formats/pdf-engine.html) of the quarto documentation for more details.

### Rendering the whole lecture

Rendering the lecture to a large number of output formats is then as easy as (assuming you're in the repository's root folder):

```bash
quarto render --to html
```

to render to html (a website). This will create a file called `lecture.html` in the same folder, which you can open with your browser.

Or:

```bash
quarto render --to pdf
```

which will create a single pdf file `lecture.pdf` (note that you need a working TeX installation for pdf output to work, as discussed in [prerequisites](#prerequisites)).

Refer to the quarto documentation for other output options.

### Rendering individual files / creating notebooks

You can render the files for each lecture day individually, e.g.:

```bash
quarto render lectures/01-Introduction.qmd --to pdf
```

which puts the pdf file `01-Introduction.pdf` into the [lectures](lectures) folder.

You can also convert the lecture files to [jupyter](https://jupyter.org/) notebooks, which allows you to play with the code yourself!

```
quarto convert lectures/02-Direct-Sampling-Methods.qmd
```

This places a new file `02-Direct-Sampling-Methods.ipynb` in the [lectures](lectures) folder.

### (Optional:) Creating a python virtual environment

It's best practice to have a separate (virtual) environment for each python project.
To create a new virtual environment called `env` in your current folder (e.g. in this project's root folder), run:

```bash
python -m venv env
```

you need to do this only once.

#### Working with/inside the virtual environment

Each time you want to change in your new virtual environment, go to the folder in which you created your environment
(The folder containing the folder `env`, if you created your environment like above)
and run

```bash
. env/bin/activate
```

Note the `.` at the beginning!

This activates your virtual environment. Now you're ready to 
* install the prerequisites inside your virtual environment (only need to do that once.)
* render the lecture using `quarto` as described above.
