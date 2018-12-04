# What is the _Issues Label Standard_ (WIP)

This is an unofficial standard and guide for creating scalable and efficient
naming conventions and practices for GitHub Issues, where the default labels are
unfortunately not enough for larger, collaborative, projects.

# How to use this guide

This standard practice can be applied to newly created GitHub repositories or
added on top of existing ones. The philosophy behind this unofficial standard
is to not only add scalable structure to the naming conventions of the label, but also the colors, sub-categories, and personal discipline.

# Contribute
Please, please, please contribute. If you see a mistake in grammar, spelling,
syntax, usage of words, etc, do open a pull request! Help build this standard.
Supply your opinion, your suggestion, your edits, your enhancements.

# CLI

TODO

# Issues Label Standard

## Color
### Visible Light

If we compare color to its wavelength in visible light, it can be attributed
that violet, blue, and green (darker colors), respectively have shorter
wavelengths than yellow, orange, red (brighter colors), respectively having
longer wavelengths.

#### Long-wave
- yellow
- orange
- red

Similarly, amongst the longer wavelengths, we associate `yellow` with caution and
yield. Less of an emergency but still a priority. `orange` we can see as a neutral
between the two long wavelengths, which serves its purpose as a more neutral
emergency but still unsettling as we can't tell which way it could go (lighter
to yellow, or darker to red)

#### Short-wave
- violet
- blue
- green

Short-wave colors, on the other hand, the more dark colors which may or may not
include achromatic colors, which ironically means "without color." 

### Anti-Color

A literal translation of Achromatic is "without color." Taking into n

#### Achromatic
- gray
- black
- white

### Tints

GitHub's label color defaults are actually interesting, as you have the option to
use a dark tint of a specified color or its respective dark tint. These 
different tints of colors can act as the contrast between severity and gentility.

### Association

As humans, we generally associate certain colors with certain emotional bonds.
As an example when we think of `red` we think of love, sex and fire, but we also
see it as urgent, emergent, or error.

- yellow (refactor, trivial, open, in review)
- orange (security, performance, major, minor, in progress)
- red (bug, blocker, critical, blocked)
- violet (free)
- blue (free)
- green (enhancement, update, accepted)
- gray (documentation, help, abandoned, invalid, duplicate)
- black (reserved for release number or version)

To ensure better separation, we can use different tints of these colors in
order to differentiate between top-level categories (type, priority, etc).

color      | darkest     | darker        | *           | lighter     | lightest 
---        | ---         | ---           | ---         | ---         | ---      
**yellow** | refactor    | in review     | trivial     | open        | discussion        
**yellow** | ![][ffff00] | ![][ffff7f]   | ![][ffff99] | ![][ffffb2] | ![][ffffcc]
**orange** | major       | in progress   | performance | security    | minor     
**orange** | ![][ffa500] | ![][ffb732]   | ![][ffc966] | ![][ffdb99] | ![][ffe4b2]
**red**    | critical    | bug           | blocker     | blocked     |           
**red**    | ![][ff0000] | ![][ff3232]   | ![][ff6666] | ![][ff9999] | ![][ffcccc]
**green**  | enhancement | feature       | update      |             |           
**green**  | ![][008000] | ![][329932]   | ![][66b266] | ![][99cc99] | ![][cce5cc]
**gray**   | help        | documentation | abandoned   | duplicate   | invalid   
**gray**   | ![][808080] | ![][999999]   | ![][b2b2b2] | ![][cccccc] | ![][e5e5e5]

[ffff00]: https://dummyimage.com/90x40/ffff00/000.png&text=ffff00
[ffff7f]: https://dummyimage.com/90x40/ffff7f/000.png&text=ffff7f
[ffff99]: https://dummyimage.com/90x40/ffff99/000.png&text=ffff99
[ffffb2]: https://dummyimage.com/90x40/ffffb2/000.png&text=ffffb2
[ffffcc]: https://dummyimage.com/90x40/ffffcc/000.png&text=ffffcc
[ffa500]: https://dummyimage.com/90x40/ffa500/fff.png&text=ffa500
[ffb732]: https://dummyimage.com/90x40/ffb732/fff.png&text=ffb732
[ffc966]: https://dummyimage.com/90x40/ffc966/fff.png&text=ffc966
[ffdb99]: https://dummyimage.com/90x40/ffdb99/000.png&text=ffdb99 
[ffe4b2]: https://dummyimage.com/90x40/ffe4b2/000.png&text=ffe4b2 
[ff0000]: https://dummyimage.com/90x40/ff0000/fff.png&text=ff0000 
[ff3232]: https://dummyimage.com/90x40/ff3232/fff.png&text=ff3232 
[ff6666]: https://dummyimage.com/90x40/ff6666/fff.png&text=ff6666 
[ff9999]: https://dummyimage.com/90x40/ff9999/000.png&text=ff9999 
[ffcccc]: https://dummyimage.com/90x40/ffcccc/000.png&text=ffcccc 
[008000]: https://dummyimage.com/90x40/008000/fff.png&text=008000 
[329932]: https://dummyimage.com/90x40/329932/fff.png&text=329932 
[66b266]: https://dummyimage.com/90x40/66b266/fff.png&text=66b266 
[99cc99]: https://dummyimage.com/90x40/99cc99/000.png&text=99cc99 
[cce5cc]: https://dummyimage.com/90x40/cce5cc/000.png&text=cce5cc 
[808080]: https://dummyimage.com/90x40/808080/fff.png&text=808080 
[999999]: https://dummyimage.com/90x40/999999/fff.png&text=999999 
[b2b2b2]: https://dummyimage.com/90x40/b2b2b2/fff.png&text=b2b2b2 
[cccccc]: https://dummyimage.com/90x40/cccccc/000.png&text=cccccc 
[e5e5e5]: https://dummyimage.com/90x40/e5e5e5/000.png&text=e5e5e5 

## Types 

- bug
- enhancement
- discussion
- feature

## Sub-Types

- regression
- security
- performance
- documentation
- refactor
- update

## Priority

- blocker
- critical
- major
- minor
- trivial

## Status
- in discussion
- in progress
- in review

## Resolution

- open
- abandoned
- accepted
- invalid
- duplicate
- blocked

# Usage

GitHub Issue's does not provide a very intuitive way to bulk create or import
labels. However, there are numerous open-source modules that serve this very
purpose. Some of which accept templates.

# References
- https://science-edu.larc.nasa.gov/EDDOCS/Wavelengths_for_Colors.html
- http://www.color-hex.com

# License
MIT