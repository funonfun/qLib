qLib
====

A procedural asset library for SideFX Houdini.

- http://qlab.github.io/qLib/
- https://github.com/qLab/qLib
- https://www.facebook.com/qLibHoudini

Download the **latest version** here:
https://github.com/qLab/qLib/archive/master.zip


### About

qLib is a digital asset library for SideFX's Houdini.
It is a collection of tools designed to work flawlessly with each other
and Houdini's native toolset.
It is driven by (and used in) *real production environments*,
but at the same time it fully respects and conforms to all the important
Houdini concepts.

Strong emphasis on the following things:
- **Backwards-compatibility**: old scenes will _not_ break over time
- **Performance**: we press for VEX/multithreading as much as possible
- **Usability**: our tools avoid the "in-house" look-and-feel

qLib is **open source software** licensed under the [New BSD
license](https://github.com/qLab/qLib/blob/master/LICENCE). It's developed by
VFX professionals from several studios working on feature films, game
cinematics and commercials.


### Tools

- Generation, manipulation and visualization of geometry attributes and groups
- Boundary geometry generation and manipulation
- A complete deformer suite, implemented through a common deformer framework
- Reimplemented high-performance versions of certain original Houdini OPs
- Workflow-related tools
- A large collection of gallery items (node and subnet presets)
- Shelf tools
- Colour scemes, extra menu items
- Experimental extras

More details here:
https://www.facebook.com/notes/qlib/qlib-summary-highlights/726676570699463


### Quick Installation

- Download the latest dev-branch (see link above)
- Extract and move it into your Houdini config directory
- Append the provided houdini.env example file to your own houdini.env

(Note that the provided env file example is for linux.)


### Installation

The installation process involves two steps: **getting the contents** and
**setting up the environment** for Houdini.

#### 1. Getting the contents

You can either grab a compressed archive file (as mentioned above), or
you can clone the official repository with **git**.

The archive way is the easiest, but using git has additional benefits,
such as instant updates, easy access to older versions, other development
branches, etc.

#### 2. Adding it to the Houdini environment

We provide example *houdini.env* files (windows and linux) which can be
*appended to your houdini.env file in your Houdini config folder*
(the HoudiniXX.X/ folder in your home directory).

To read more on configuration, see
<a href="http://www.sidefx.com/docs/houdini/basics/config_env">documentation on houdini.env</a>.

#### 2a. Important note for facilities

If you're installing at a large facility with a package management system,
use your package manager to set up these environment variables instead of
relying on houdini.env files.


### Further readings and other places of interest

qLib comes with documentation. All assets have help cards (even with
example images and whatnot), providing all the related important details.

Other aspects of the library are covered in the
[Wiki](https://github.com/qLab/qLib/wiki).

We appreciate bug reports, RFEs (Request For Enhancement), or feedback of
any kind.
[Our issue tracker is here](https://github.com/qLab/qLib/issues?state=open).

If you need help, have a question or just want to keep up with the news
regarding qLib, feel free to join us on our [Google
Groups](https://groups.google.com/forum/#!forum/qlib) page.

#### Thank you for your interest in qLib!
##### The qLib Team

