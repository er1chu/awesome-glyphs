# Awesome Glyphs [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A list of plugins / python scripts, tutorials, and other resources for Glyphs, the next generation type design software. 
> Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.

## Table of Contents
- [Glyphs Manuals](#manuals)
- [Plugins / Scripts](#plugins-and-scripts)
- [Tutorials](#tutorials)
	- Glyphs
	- Type Design
- [Misc](#misc)

## Glyphs Manuals
- [Glyphs 2.2 Manual](https://glyphsapp.com/content/1-get-started/2-manuals/1-handbook-glyphs-2-0/Glyphs-Handbook-2.2.pdf)
- [Glyphs 1.x Manual](https://glyphsapp.com/content/1-get-started/2-manuals/2-handbook-glyphs-1/Glyphs-Handbook-2013.pdf)
- [Glyphs 1.x Manual (Deutsche)](https://glyphsapp.com/content/1-get-started/2-manuals/3-handbook-glyphs-1-de/Glyphs-Handbuch-2014.pdf)

## Plugins and Scripts
### Plugins
- [Remix Tools](http://remix-tools.com/glyphsapp) - Remix Tools port to Glyphs: Harmonizer, Tuner, Scaler ([Read more](http://remix-tools.com/)).
- [Word-o-Mat](https://github.com/ninastoessinger/word-o-mat) - Word generator with options to set length, frequency of specific letters, diagonals, descenders, etc. Also available for Robofont. 
- [StringSmash](https://github.com/BelaFrank/StringSmash) - Script to generate strings for spacing/kerning. Also available for Robofont.
- [RandomCitiesA_Z](https://github.com/arialcrime/PythonLab/tree/master/RandomCitiesA_Z) - Script to generate list of random cities as test strings.
- [Glyphs Git](https://github.com/simoncozens/GlyphsGit) - Provides git integration for Glyphs.
- [Speed Punk](https://yanone.de/typedesign/code/speedpunk/) - Curvature visualization tool
- [RedArrow](https://github.com/jenskutilek/RedArrow-Glyphs) - This plugin points at possible outline errors, like FontAudit in FontLab Studio. This version only works in Glyphs 2.
- [Curve Equalizer](https://github.com/jenskutilek/Curve-Equalizer) - Quickly balance the Bézier handles of a curve or change its curvature independently.
- [Show Coordinates of Selected Nodes](https://github.com/mekkablue/ShowCoordinatesOfSelectedNodes) - Displays coordinates for selected on-curve nodes, as well as length and angle of the surrounding handles and line segments.
- [Fix Zero Handles](https://github.com/jenskutilek/RedArrow-Glyphs) - Analyzes the path structure of selected layers and will rearrange path segments that contain completely retracted handles, a.k.a. ‘zero handles,’ which typically occurs when importing from Adobe Illustrator.
- [DeutschMark’s Plugins](https://github.com/DeutschMark/Glyphsapp-Plugins) - Type designer Mark Frömberg’s plugin repository.
	- **Siblings** - Superimposes shape groups for the current glyph as a drawing reference. Essential.
	- **Distance And Angle** - Shows the direct distance of two selected Elements (Nodes, Anchors, Components) and their angle.
	- **Next Master** - Displays the next Master in the currently active edit view.
	- **Kerning Group Reference** - Live preview of the kerning group reference glyph next to the current one.
	- **Rotated** - Displays the current letter as a 180° rotated version of itself. Symmetry helper.
	- **Node Count** - A little number in the edit view which keeps track of the current glyphs’s count of nodes.

### Scripts
- [Tosche’s Scripts](https://github.com/Tosche/Glyphs-Scripts) - Toshi Omagari’s repository of helper scripts.
	- **Analyze Manuscript** - (GUI) Calculates the minimal character set required for the pasted text.
	- **Create .case alternate** - Duplicates selected glyphs but as components, giving them .case suffix and the sidebearings. Modified from Mekkablue's "Create .ssXX glyph from current layer" script.
	- **Generate ss20 for All-Glyph Access** - Writes OpenType ss20 feature for all glyphs in the font. Copy glyphs names with slashes and paste it to an OT-savvy application, and activate ss20 to see the glyphs.
	- **Guideline Locker** - (GUI) Locks selected guidelines and unlocks all global guidelines. Vanilla required.
	- Export Tagged Text with All Glyphs for InDesign: Saves InDesign tagged text file that contains all glyphs for typesetting a specimen, using glyph ID. This is a better solution than generating ss20 feature.
	- **Nudge-move by Numerical Value** - (GUI) Nudge-moves selected nodes by the values specified in the window.Vanilla required.
	- **Regular Expression Glyph Renaming** - (GUI) Renames selected glyphs using regular expression, with case conversion options. You can use it as a normal renaming tool too. Vanilla required.
	- **Transform Images with Proper Math** - (GUI) Batch scale and move images in selected layers, using the math you learned at school. Based on mekkablue's Transform Images script. Vanilla required. ## Metrics & Kerning
	- **Batch Metric keys** - (GUI) Applies the specified logic of metrics key to the selected glyphs. Vanilla required.
	- **Copy Kerning Pairs** - (GUI) Copies kerning patterns to another. It supports pair-to-pair and preset group copying.Vanilla required.
	- **Copy kerning to Greek & Cyrillic** - (GUI) Copies your Latin kerning to the common shapes of Greek and Cyrillic, including small caps, using predefined dictionary. Exceptions and absent glyphs are skipped. It's best used after finishing Latin kerning and before starting Cyrillic and Greek. Vanilla required.
	- **MenuTitle** - Display Unlocked Kerning Pairs Shows unlocked kerning pairs (exceptions) in the edit view. String part done by Ben Jones, display part done by Toshi Omagari and Georg Seifert.
	- **Kerning Exception** (GUI) - Makes an kerning exception of the current pair. Note: Current glyph is considered the RIGHT side of the glyph. Vanilla required.
	- **Permutation Text Generator** - (GUI) Outputs glyph permutation text for kerning. Vanilla required.
	- **Rename Kerning Groups** - (GUI) Lets you rename kerning names and pairs associated with them. Vanilla required.
	- **Report Metrics Keys** - (GUI) Reports possibly wrong keys. It reports non-existent glyphs in the keys, glyphs using different keys in each layer, and nested keys. Vanilla required.
	- **Report Glyphs with Acute-angled Node** - Reports glyphs that have nodes with very acute angle (default: less than 15 degrees).

- [Just Another Foundry's Scripts](https://github.com/justanotherfoundry/glyphsapp-scripts) - Just Another Foundry's repository of helper scripts.
	- **Delete All Hints** - Removes all hints from the selected glyphs.
	- **Expand Kerning** - Expande Kerning just like in FontLab.
	- **Insert Glyph to Background** - User enters a glyph name and glyph gets inserted to background.
	- **Insert Glyph** - Same as above but glyph is inserted into foreground.
	- **Mask to Master** - Emulates Mask to Master function from FontLab (i.e. replaces current outline with background).
	- **Paste Background** - Pastes background into current layer
	- **Remove Backup Layers** - Removes all backup layers.
	- **Symmetrify** - Symmmetrifes glyph shape with different options.
	- **Round Kerning** - Rounds the kerning values to full integer numbers.

## Tutorials
### Glyphs
- [Glyphs Tutorial Database](https://glyphsapp.com/tutorials/articles) - Tutorials and helpful articles from the creators of Glyphs
- [Working with Paths](https://vimeo.com/43552747)
- [Building Diacritics](https://vimeo.com/43551729)
- [Kerning](https://vimeo.com/44454636)

### Type Design - Practice
- [Bézier Curves and Type Design: a Tutorial](http://learn.scannerlicker.net/2014/04/16/bezier-curves-and-type-design-a-tutorial/)
- [Drawing Good Paths](https://glyphsapp.com/tutorials/drawing-good-paths) - Practical guide to create smooth curves.
- [Notes on Type Design](http://66.147.242.192/~operinan/2/2.3.1a/2.3.1.01.notes.htm) - Website operated by Gunnlauger SE Briem that is a good introduction to the practical concerns of type design.
- [Type Cooker](http://typecooker.com/) - Ideas generator that suggests what kind of typeface to draw.
- [Type Basics](http://www.typeworkshop.com/index.php?id1=type-basics&id2=&id3=&id4=&id5=&idpic=02#pictloader) - Illustrated guide to explain some basic issues in type design.

### Type Design - Theory
- [Sketching and Broadnib Simulation Techniques](https://glyphsapp.com/tutorials/sketching)
- [Preparation for Incoming MATD Students](http://typefacedesign.net/resources/preparation-for-incoming-matd-students/) - Reading list for students enrolling in the Masters in Type Design program at the University of Reading
- [Type Culture Articles](http://www.typeculture.com/academic_resource/articles_essays/) - Helpful list of articles on type design.

## Misc
- [Luc Devroye's Type Design Information Page](http://luc.devroye.org/fonts.html) - Massive—if not legendary—resource on typefaces and their designers.
- [Font Testing Page](http://www.impallari.com/testing/index.php) - Incredibly handy online specimen tool.


## Contribute
Contributions welcome! Read the [contribution guidelines](contribute.md) first.

## License
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
