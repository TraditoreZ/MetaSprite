# MetaSprite

MetaSprite is an Unity plugin that lets you import [Aseprite][aseprite]'s .ase file into Unity, as Mecanim animation clips/controllers. It also has rich **metadata support** built in, allowing one to manipulate colliders, change transforms, send messages (and much more!) easily in Aseprite.

MetaSprite is now ready for production (already used heavily by myself in a WIP action platformer). New features will gradually be added.

# Feature overview

* Doesn't require external aseprite executable to run
* Blazing fast
* Efficient atlas packing
* Simple workflow achieved using the new scriptable pipeline
* Extensive metadata support
  * Commented (ignored) Layers/Tags
  * Manipulate colliders/events/positions/sprite pivots using image data
  * Specify clip looping using frame tag properties
  * ...
* Write custom MetaLayerProcessor for extended functionality

# Installation & Usage

Check out [releases](https://github.com/WeAthFoLD/MetaSprite/releases) for unitypackage downloads. You can copy the `Assets/Plugins` folder of the repo into your unity project's asset folder for same effect.

See [wiki](https://github.com/WeAthFoLD/MetaSprite/wiki) for explanation of importing, import settings, meta layers and other importer features.

# Credits

* [tommo](https://github.com/tommo)'s Aseprite importer in gii engine
* [talecrafter](https://github.com/talecrafter)'s [AnimationImporter](https://github.com/talecrafter/AnimationImporter), where the code of this project is initially based from

[aseprite]: https://aseprite.org

# Donation

If this plugin helped you in your project or you want to support the developement, consider buying me a cup of coffee (°∀°)ﾉ

<a href="https://www.patreon.com/bePatron?u=2955382">
<img src="https://c5.patreon.com/external/logo/become_a_patron_button.png"/>
</a>
