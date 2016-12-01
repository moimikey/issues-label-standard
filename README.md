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
yield. Less of an emergency but a still priority. `orange` we can see as a neutral
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

### Shades

GitHub's label color defaults are actually interesting, as you have the option to
use a dark shade of a specified color or its respective dark shade. These 
different shades of colors can act as the contrast between severity and gentility.

### Association

As humans, we generally associate certain colors with certain emotional bonds.
As an example when we think of `red` we think of love, sex and fire, but we also
see it as urgent, emergent, or error.

- yellow (refactor, trivial, open, in review)
- orange (security, performance, major, minor, in progress)
- red (bug, duplicate, invalid, blocker, critical, blocked)
- violet ()
- blue ()
- green (enhancement, update, accepted)
- gray (documentation, help, abandoned)
- black ()

To ensure better separation, we can use different shades of these colors in
order to differentiate between top-level categories (type, priority, etc).

## Types

- bug
- enhancement
- help
- invalid
- duplicate

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
- blocked

## Duration

TODO

### Point systems

TODO

## Usage

GitHub Issue's does not provide a very intuitive way to bulk create or import
labels. However, there are numerous open-source utilities that serve this very
purpose. Some of which accept templates. This unofficial standard pairs well with
utilities that accept a pre-defined template. Here are Issues Label Standard
templates that can be imported and used:

```js
Example 1
```

```js
Example 2
```

# References
- https://science-edu.larc.nasa.gov/EDDOCS/Wavelengths_for_Colors.html

# License
MIT