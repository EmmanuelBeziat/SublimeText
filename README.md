# SublimeText
My SublimeText 3 setup


## Preferences

```json
{
	"bold_folder_labels": true,
	"color_scheme": "Packages/Material Theme/schemes/Material-Theme.tmTheme",
	"font_size": 10,
	"ignored_packages":
	[
		"Vintage"
	],
	"index_exclude_patterns":
	[
		"*.log"
	],
	"tab_size": 4,
	"theme": "Material-Theme.sublime-theme",
	"trim_trailing_white_space_on_save": true,
	"word_wrap": true
}
```

## Key map (Windows)

```json
[
	{ "keys": ["ctrl+v"], "command": "paste_and_indent" },
	{ "keys": ["ctrl+shift+v"], "command": "paste" }
]
```

## Key map (OSX)

```json
[
	{ "keys": ["super+v"], "command": "paste_and_indent" },
	{ "keys": ["super+shift+v"], "command": "paste" }
]
```


# Plugins

## [AdvancedNewFile](https://github.com/skuroda/Sublime-AdvancedNewFile)

Permet la création rapide de nouveaux fichiers et dossiers dans un projet SublimeText 2 & 3.

![AdvancedNewFile](http://take.ms/xnE9w)

## [AutoFileName](https://github.com/BoundInCode/AutoFileName)

Autocomplétion de noms de fichiers dans un projet SublimeText.

![AutoFileName](http://take.ms/dNwNH)

## [Better CoffeeScript](https://github.com/aponxi/sublime-better-coffeescript)

Permet d'utiliser le langage CoffeeScript et ses fichiers (.coffee) au sein de SublimeText. Gestion du langage, options de compilation, prévisualisation.

CoffeeScript doit être installé avec NodeJS :

```Shell
npm install -g coffee-script
```

## [BracketHighlighter](https://github.com/facelessuser/BracketHighlighter)

Facilite la lecture du code en affichant l'ouverture / fermeture des balises / brackets / parenthèses / autres dans la gouttière.

![BracketHighlighter](http://take.ms/trbkt)

## [Color Highlighter](https://github.com/Monnoroch/ColorHighlighter)

Prévisualise les couleurs (Aux formats hexadecimal, rgb(a), hsl(a), etc.). Fonctionne avec les variables de préprocesseurs.

![Color Highlighter](http://take.ms/lwioj)

## [ColorPicker](https://github.com/weslly/ColorPicker)

Ouvre le *ColorPicker* par défaut de l'OS pour choisir une couleur à la volée.

## [DocBlockr](https://github.com/spadgos/sublime-jsdocs)

Facilite l'écriture des commentaires.

![DockBlockr](http://take.ms/FPfvH)

## [EditorConfig](https://github.com/sindresorhus/editorconfig-sublime)

Permet d'avoir des fichiers édités de façon propre entre différents éditeurs et différents OS.

## [Emmet](https://github.com/sergeche/emmet-sublime)

Facilite l'écriture du html avec une syntaxe CSS avancée.

![Emmet](http://take.ms/rskJR)

## [GitGutter](https://github.com/jisaacks/GitGutter)

Affiche les modifications git d'un fichier dans la gouttière.

![GitGutter](http://take.ms/hldLn)

## [Glue](https://github.com/chrissimpkins/glue)

Terminal utilisable depuis SublimeText.

## [Increment Selection](https://github.com/yulanggong/IncrementSelection)

Permet d'insérer automatiquement des nombres auto-incrémentés sur plusieurs lignes.

**Pour Windows** <kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>i</kbd>
**Pour OSX** <kbd>cmd</kbd> + <kbd>ctrl</kbd> + <kbd>i</kbd>

## [JsFormat](https://github.com/jdc0589/JsFormat)

Nettoie et clarifie automatiquement un code Javascript.

![JsFormat](http://take.ms/pSjZg)

**Pour Windows** <kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>f</kbd>
**Pour OSX** <kbd>cmd</kbd> + <kbd>alt</kbd> + <kbd>f</kbd>

## [SideBarEnhancements](https://github.com/titoBouzout/SideBarEnhancements)

Ajoute de nombreuses fonctionnalités à la sidebar de projet de SublimeText.

## [Stylus](https://github.com/billymoon/Stylus)

Permet d'utiliser le langage Stylus et ses fichiers (.styl, .stylus) au sein de SublimeText. Gestion du langage, options de compilation.

Stylus doit être installé avec NodeJS :

```Shell
npm install -g stylus
```

## [SublimeLinter 3](https://github.com/SublimeLinter/SublimeLinter3)

Gestionnaire de *linters* (Voir packages suivants).

### [SublimeLinter-jshint](https://github.com/SublimeLinter/SublimeLinter-jshint)

Permet l'utilisation de jshint pour vérifier la syntaxe d'un fichier Javascript.

![JsHint](http://take.ms/h4B2V)

jshint doit être installé avec NodeJS :

```Shell
npm install -g jshint
```

## [ToggleQuotes](https://github.com/spadgos/sublime-ToggleQuotes)

Permet de switcher simplement de *single quotes* à *double quotes* (Dans les deux sens).

![ToggleQuotes](http://take.ms/lXxze)

## [TrailingSpaces](https://github.com/SublimeText/TrailingSpaces)

Permet d'afficher et supprimer (Automatiquement ou manuellement) les espaces vides dans un fichier (cf. "Preferences" plus haut).

# Plugins (Less used)

## [ApacheConf](https://github.com/colinta/ApacheConf.tmLanguage)

Gestion des fichiers de configuration Apache (.conf)

## [INI](https://github.com/clintberry/sublime-text-2-ini)

Gestion des fichiers de configuration Windows (.ini)

## [nginx](https://github.com/brandonwamboldt/sublime-nginx)

Gestion des fichiers de configuration NGINX

## [Sass](https://github.com/nathos/sass-textmate-bundle)

Permet d'utiliser le langage Sass et ses fichiers (.scss) au sein de SublimeText.

Sass doit être installé avec NodeJS :

```Shell
npm install -g sass
```

## [LESS](https://github.com/danro/Less-sublime)

Permet d'utiliser le langage LESS et ses fichiers (.less) au sein de SublimeText.

LESS doit être installé avec NodeJS :

```Shell
npm install -g less
```

## [MJML](https://github.com/mjmlio/mjml-syntax)

Langage de templating (utiliser avec https://mjml.io/).

Installation de MJML avec NodeJS :

```Shell
npm install -g mjml
```


# Templates

## [Material-Theme](https://github.com/equinusocio/material-theme)

## [itg.flat](https://github.com/itsthatguy/theme-itg-flat)

## [flatland](https://github.com/thinkpixellab/flatland)
