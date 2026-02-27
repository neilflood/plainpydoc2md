# plainpydoc2md
Convert plain Python docstrings into Markdown files

This is intended for simple projects, where things like Sphinx and ReadTheDocs are more complex than desired. 

This scripts reads one or more Python modules and generates corresponding Markdown (.md) files with the docstrings layed out in a simple but readable fashion. The main point is that the docstrings are not parsed for further formatting, but rather they are just copied over as plain text. In most cases, programmers make their docstrings readable in a text editor anyway, so this is usually sufficient, even if not very fancy.
