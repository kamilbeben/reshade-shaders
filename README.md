# Fork info
This repository was forked with the sole purpose of addressing an issue encountered while utilizing ReShade 4.5.4 in conjunction with the original repository. The error message "unable to extract reshade-shaders-master" arose as a result of the source repository's default branch being renamed from `master` to `slim`. In order to resolve this, I forked the repository and restored the default branch name to `master`, in the hopes that it will assist anyone encountering the same error during their search for a solution.

ReShade FX shaders
==================

This repository aims to collect post-processing shaders written in the ReShade FX shader language.

Installation
------------

1. [Download](https://github.com/crosire/reshade-shaders/archive/master.zip) this repository
2. Extract the downloaded archive file somewhere
3. Start your game, open the ReShade in-game menu and switch to the "Settings" tab
4. Add the path to the extracted [Shaders](/Shaders) folder to "Effect Search Paths"
5. Add the path to the extracted [Textures](/Textures) folder to "Texture Search Paths"
6. Switch back to the "Home" tab and click on "Reload" to load the shaders

Contributing
------------

Check out [the language reference document](REFERENCE.md) to get started on how to write your own!
