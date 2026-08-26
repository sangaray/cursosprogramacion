# Measurement Units

## Unit types

- absolute = is a fixed measurements, it doesn't change. It keep the sizes of the elements fixed
  | Unit | Meaning | Approximate measurement |
  | --- | --- | --- |
  | **in** | Inches | 1in = 25.4mm |
  | **cm** | Centimeters | 1cm = 10mm |
  | **pc** | Picas | 1pc = 4.23mm |
  | **mm** | Millimeters | 1mm = 1mm |
  | **pt** | Points | 1pt = 0.35mm |
  | **px** | Pixels | 1px = 0.26mm |
  | **Q** | Quarter of a mm | 1Q = 0.248mm |

- relative = it depends of otrher factors. This allows the flexible elements
  | Unit | Meaning | Approximate measurement |
  | --- | --- | --- |
  | **em** | «M» | 1em = font size set in browser |
  | **ex** | «X» (~0.5em) | 1ex = ~ half of browser font size |
  | **ch** | «zero width» | 1ch = width of the zero character ( 0 ) |
  | **rem** | «root M» | 1rem = root font size |
  | **%** | Percentage | Relative to inheritance (parent container) |

- The font size of the root element is set to 16px by default

- flexible units
  - `viewport` = It is a concrete percentage of the specific size in the browser window.

  | Unidad   | Significado      | Medida aproximada                      |
  | :------- | :--------------- | :------------------------------------- |
  | **vw**   | viewport width   | 1vw = 1% ancho de navegador            |
  | **vh**   | viewport height  | 1vh = 1% alto de navegador             |
  | **vmin** | viewport minimum | 1vmin = 1% de alto o ancho (el mínimo) |
  | **vmax** | viewport maximum | 1vmax = 1% de alto o ancho (el máximo) |
