Jupyter TabNine
==========
This extension provides code auto-completion based on deep learning.

Options
-------

* `jupytertabnine.before_line_limit`:
   maximum number of lines before for context generation,
   too many lines will slow down the request. -1 means Infinity,
   thus the lines will equal to number of lines before current line.

* `jupytertabnine.after_line_limit`:
   maximum number of lines after for context generation,
   too many lines will slow down the request. -1 means Infinity,
   thus the lines will equal to number of lines after current line.

* `jupytertabnine.options_limit`:
   maximum number of options that will be shown

* `jupytertabnine.assist_active`:
   Enable continuous code auto-completion when notebook is first opened, or
   if false, only when selected from extensions menu.

* `jupytertabnine.assist_delay`:
   delay in milliseconds between keypress & completion request.
