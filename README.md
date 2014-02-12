gis-book
========

A book about GIS fundamentals.

The book will be distributed under a CC Attribution license.

This project is a translation of the free book *Sistemas de Información Geográfica*, originally written in spanish.

This is a work in progress. 

Current status
---------------

You can see the current status of the translation here.


How to collaborate
-------------------

Here are some ideas and instructions for those wanting to collaborate:

- First of all, clone the repository. We will be using a normal git workflow, where authors can collaborate using pull requests.

- The project is written using Sphinx. The repository has been initially populated with the original files containing text in spanish. Translation should be done directly on the sphinx files, replacing spanish text with its corresponding english translation.

- Most images do not have associated text, so they can be used directly. Original names are in spanish, but they should be renamed to an english name. Replace the corresponding references in the Sphinx code.

- For those images including text, an original SVG version should be available in the ``svg`` folder. Use it to create a translated image and export as png so it can be inserted in the final document. If a suitable SVG file is not available, the image should be remade from scratch.

- When translating a Sphinx label, make sure that you translate also all references to it. Use a *Search in files* functionality in your text editor and replace all ocurrences, even in files that haven't been translated yet.


Other translations
-------------------

You are welcome to translate the book into any other language. This repository will contain the english version of the book, but you can start a new translation project by forking it and setting a similar workflow. Please let me know in case you want to coordinate a translation to a different language.

