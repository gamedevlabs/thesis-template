# LaTeX template for TUM theses

This is a LaTeX template created according to the guidelines for TUM informatics theses in WS 2022. **Always check the [current formatting guidelines][thesis-guidelines] before you hand in.** See [`_build/main.pdf`][sample-pdf] for an example PDF created with this template.

Comments & contributions are welcome!

## Quickstart
* Download and extract the template, or upload it to an online editor such as [Overleaf][overleaf] or [TUM ShareLaTeX][tum-sharelatex]. If you prefer to use Git, just clone/fork the repository.
* If you are using VS Code in Windows, I suggest to follow these steps: 
    1. All the steps in the following link: [Setup][setup]
    2. If it doesn't compile, try restarting to make sure the path variables are known to the system
    3. Change latex build directory in VS Code: 
``file -> preferences -> settings -> search for "latex outdir" -> change outdir to "%DIR%/_build"``
 * Look for `TODO` comments in the provided files. Start at `main.tex` and the files in the ``setup`` folder.

If you are new to LaTeX, the [Overleaf Documentation][overleaf-learn] or the [LaTeX Wikibook][latex-wikibook] might help.

If you still have problems with the template, feel free to [create an issue][issue]. For general LaTeX questions, use [TeX StackExchange][tex-se].

## Folder structure
### ``_`` prefix
- Folders with an ``_`` prefix can usually be ignored if you don't want to do your own fancy stuff. If you do, you know how to do it anyways.
### bib
- add ``.bib`` files here
- update ``.bib`` files here
### chapters
- add ``.tex`` files for chapters of your thesis here
- add other relevant files like figures here
- ``abstract.tex``: write abstract here
- ``acknowledgements.tex``: write acknowledgements here
### setup
- ``bibliography.tex``: include bib files here
- ``contents.tex``: include chapters here
- ``document.tex``: change details about the document structure here
- ``settings.tex``: include packages and other settings here
- ``thesis_information.tex``: edit thesis information here

## License

[![Creative Commons License][license-image]][license]

This template is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License][license], meaning that:

 * You can share (copy, redistribute) and adapt (remix, transform, build upon) this template for any purpose, even commercially.
 * If you share the template or a modified (derived) version of it, you must attribute the template to the original authors ([Florian Walch and contributors][template-authors]) by providing a [link to the original template][template-url] and indicate if changes were made.
 * Any derived template has to use the [same][license] or a [compatible license][license-compatible].

The license **applies only to the template**; there are no restrictions on the resulting PDF file or the contents of your thesis.

[setup]: https://mjcb.ca/blog/2020/01/23/visual-studio-code-with-latex/
[issue]: https://github.com/TUM-Dev/tum-thesis-latex/issues
[latex-wikibook]: https://en.wikibooks.org/wiki/LaTeX
[license-compatible]: https://creativecommons.org/compatiblelicenses
[license-image]: https://i.creativecommons.org/l/by-sa/4.0/88x31.png
[license]: https://creativecommons.org/licenses/by-sa/4.0/
[overleaf]: https://www.overleaf.com/
[sample-pdf]: https://raw.github.com/TUM-Dev/tum-thesis-latex/master/build/main.pdf
[overleaf-learn]: https://www.overleaf.com/learn
[tum-sharelatex]: https://sharelatex.tum.de/ldap/login
[template-authors]: https://github.com/TUM-Dev/tum-thesis-latex/graphs/contributors
[template-download]: https://github.com/TUM-Dev/tum-thesis-latex/archive/master.zip
[template-url]: https://github.com/TUM-Dev/tum-thesis-latex
[tex-se]: https://tex.stackexchange.com/
[thesis-guidelines]: https://www.cit.tum.de/en/cit/studies/students/thesis-completing-your-studies/informatics/
[wiki]: https://github.com/TUM-Dev/tum-thesis-latex/wiki/

