# LyX-OnlyTheorems

This module was written to export only  the theorems in a Lyx File.

## Use

To install the module, copy the file theorems-only.module to the layouts folder in LyX's user directory (which can be found in Help->About LyX), and reconfigure lyx via Tools->Reconfigure. Note that you should always load this module after all the other theorems modules.

If you want to restate all the theorems at the end of the document, and not to print only the theorems, write in the preamble \onlytheoremsfalse.

The list of environments that will be printed is saved in the macro \onlytheorems@envs, thus if you want to print, e.g., only lemmas and definitions, write in the preamble \def\onlytheorems@envs{lem,defn}.
## License

GNU Affero GPL v3.0. See `LICENSE`.
