# Repository-3 

Alamat Referensi Teman bespoke saya : https://github.com/rhonyabdullah/TeknologiKolaborasi/blob/0ab792cc1776fca9c10120e78a597c8c06af9ffa/.bowerrc

Tutorial Singkat Mengenai Bespoke.js
1. Bespoke.js Generator

A generator for Yeoman that scaffolds a Bespoke.js presentation.

The boilerplate project includes a Gulp build system, a preview server with LiveReload, Jade and Stylus compilation, a GitHub Pages deployment task, and .

Optionally, PDFs of your presentation can be generated using bespoke-pdf. This will mean a 100mb+ download (for nw.js) but it's cached once for all bespoke projects.

Additionally, your generated presentation includes the following Bespoke.js plugins based on your configuration:

    bespoke-bullets
    bespoke-backdrop
    bespoke-scale
    bespoke-hash
    bespoke-progress
    bespoke-forms

Usage

install  Node.js, install generator-bespoke:

$ npm install -g generator-bespoke

Make a new directory and cd into it:

$ mkdir presentation-hello-world
$ cd presentation-hello-world

Scaffold a new presentation:

$ yo bespoke

Presentation workflow

All source files for the presentation reside in the src directory.

Start a local preview server:

$ gulp serve

Compile and deploy to GitHub Pages, assuming a git repo with origin pointing to GitHub:

$ gulp deploy

To manually deploy elsewhere, compile all assets into the dist directory:

$ gulp

If you've selected PDF generation, your PDFs will be created in the pdf directory.
