# Bottletags for Maschinisten
– sourced from [Parametric Bottle Name Tag by rohieb][1]

*Parametric Bottle Name Tag by rohieb is licensed under the [Creative Commons - Attribution - Share Alike][2] license. The included script `Write.scad` is Public Domain.*

**If you also like a fancy bottletag like your fellow Maschinisten, proceed as described below.**

## Instructions
1. Load `bottle-clip.scad` into OpenSCAD. At the beginning of the file, there are two variables to modify your tag, `NAME` and `LOGO`. You probably only need to change `NAME`.
2. Render, export to `.stl`, slice and print it.
3. Consider adding your `.stl` to the `stl` folder in this repository for easy future access. Please also edit the `CHANGELOG.md` and `VERSION` accordingly.

## Summary
An OpenSCAD script to create clips with your name on it which can be used to mark your bottles. In contrast to the original version by daniel, this derivative is easier adaptable and knows the following parameters:   

- name
- logo (DXF, should be 50mm*50mm)
- radius at upper and lower side
- height
- font
- gap angle

The name tag itself resides as a module in `bottle-clip.scad`.

[1]: https://www.thingiverse.com/thing:38861
[2]: http://creativecommons.org/licenses/by-sa/3.0/
