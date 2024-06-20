# Montserrat Alternates

Montserrat and Montserrat Alternates is a geometric sans-serif typeface.

\usepackage[defaultfam,thin,tabular,lining,alternates]{montserrat}

## Options

- scale (or scaled) will cause Montserrat to render magnified by the specified scale factor.
- defaultfam will cause \familydefault to be set to \sfdefault, so that Montserrat becomes the default text font for the document.
- alternates will result in \sfdefault being set to MontserratAlternates, with the rounder shapes.
- One of the options lining, oldstyle (or osf) may be specified to select the figure style. (The default is lining.)
- One of the options proportional (or p), tabular (or t) may be specified to select the figure alignment. (The default is proportional.)


| Regular     | Bold      |
| ----------- | --------- |
| thin        | semibold  |
| extralight  | bold [d]  |
| light       | extrabold |
| regular [d] | black     |
| medium      |           |

```
{\montserratalt ...}
{\fontseries{thin}\selectfont x}
```