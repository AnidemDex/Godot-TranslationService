# TranslationService [v0.1]
A plugin to use TranslationServer inside the editor, useful for plugins

**Note: There's a bug that may not let you export your game. Please see issues**

## Installation
To install this plugin, download it as ZIP archive. Copy the `addons` folder to the root of your project.

This plugin doesn't need to be activated, since it just need populate the editor to be used. 

## Usage
> Be sure to [add some translations](https://docs.godotengine.org/en/stable/tutorials/i18n/internationalizing_games.html) to your project to use the internationalization feature bundled with Godot.

_This plugin has a very complex usage_:
1. Use `TranslationService.translate()` function as a replacement for [`tr()`](https://docs.godotengine.org/en/stable/classes/class_object.html#class-object-method-tr) or [`TranslationServer.translate()`](https://docs.godotengine.org/en/stable/classes/class_translationserver.html#class-translationserver-method-translate) _(wich are essentially the same)_

That's all.

You can also use  `TS.translate()` instead `TranslationService.translate()` if you preffer short lines.
