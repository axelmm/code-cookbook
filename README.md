# Haxe Code Cookbook

> Sources for the Haxe Code Cookbook site

This project contains a static website generator, it is mixing templates and markdown files into plain HTML files.

### Structure

 * The actual code snippets are in `assets/content/cookbook`, organized per folder.
 * The template files are in `assets/content/`.
 * The static files (css, js, images) files are in `assets/includes/`.
 * The Haxe source files of the generator are in `src/`
 * The website-generated content will output in `output/`

### Running a local copy

To run the project you need [Haxe](http://haxe.org).

Call `build-site.bat` to re-generate the output files.

### Contributing to the content/website/

Please edit the code snippets, website files, template and markdown in the [assets folder](https://github.com/markknol/code-cookbook/tree/master/assets/cookbook) and do a pull request.

It would be nice if you keep the formatting of the code in the same style as used already.

### Contributing to the generator

You need [Haxe](http://haxe.org) 3.2+ installed.

The static site generator source depends on [hxtemplo](http://lib.haxe.org/p/hxtemplo) and [markdown](http://lib.haxe.org/p/markdown). Install from haxelib:
```
haxelib install hxtemplo
haxelib install markdown
```