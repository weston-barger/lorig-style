# lorig-style


In an attempt to make the world more aesthetic, I have compiled the latex stylings of my phd advisor, Professor [Matt Lorig](https://mattlorig.yolasite.com/), into a latex package which bears his name. This package uses concrete modern font for text, latin modern typewriter of greek letters in math mode, applies `\mdseries\scshape` title and section headers, asserts preferred word spacing, shows equation labels only when referenced, contains a slew of convenient mathematical symbol shortcuts, colorful hyper-references for `\ref` and `\eqref` (and other references) and more. 

To use, simply place "lorig.sty" in your latex path and use `\usepackage{lorig}` to include.

### Arguments
 Optional arguments:

    * `lmacros`     - Includes the macros defined in `lmacros.sty'

    * `draft`       - when specified, equation labels are shown on the left

    * `doublespace` - when specified, document is double spaced

    * `lgrgreek`    - uses `LGRgreek` option in `mathastext` and `lmtt` font for greek math letters
### Examples
* [Approximate pricing of European and Barrier claims in a local-stochastic volatility setting](https://arxiv.org/pdf/1610.05728.pdf)

### Note
* The `eqnarray` environment is made illegal i.e. `\PackageError` is thrown when `eqnarray` is used. Please use the `align` environment instead.