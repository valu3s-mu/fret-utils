# FRET-Utils
#### Matt Luckcuck and Marie Farrell

## fretish.sty

A LaTeX Style File for writing/writing about `Fretish`.

### Usage

* Add `\usepackage{fretish}` to the preable of your LaTeX source file.
* To print the components of a `Fretish` requirement, you can use `fretishComponents{}` (or `\fretishComponentsSmall{}` if the other command is too wide, this seems to work well in IEEE two-column).
* Each part (component) of a `Fretish` requirement has two commands:
    - A command starting with an uppercase letter prints the name of that part in the right `Fretish` colour, e.g. `\Condition{}` prints "Condition" in orange.
    - A command starting with a lowercase letter takes 1 argument and prints that argument in the right `Fretish` colour for that part of the requirement, e.g. `\condition{if x >= 5 }` prints "if x >= 5" in orange. 