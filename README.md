<h1><img src="https://rawgit.com/morkro/atom-emoji-syntax/master/resources/emoji-syntax-logo.svg" alt="Emoji Syntax" style="width:100%;"></h1>

<a href="https://travis-ci.org/morkro/atom-emoji-syntax"><img src="https://travis-ci.org/morkro/atom-emoji-syntax.svg?branch=master" alt="Build Status"></a> <img alt="devDependencies" src="https://david-dm.org/morkro/atom-emoji-syntax.svg">

Getting bored of your code? Already tried out hundreds of syntax highlighter but always felt something is missing?

**Emoji Syntax is what you need!**

An atom package adding emoji to language keywords.

## State Of Project :white_check_mark: _[active]_
The project is in **active development**.

## Installation
Install Emoji Syntax either via `apm`
```
apm install emoji-syntax
```
or search for `emoji syntax` in your Atom settings panel.

## Features :fire:
- **Emoji-Syntax is on top of your syntax theme**; you can still choose any theme you like
- Choose between four different emoji styles
- Change existing keywords with *any* emoji you want
- Define position and spacing of an emoji around the keyword
- Disable entire languages or only specific keywords

_This package does not actually add emoji characters to your code—don't worry—your linter or tests won't go crazy!_

## Supported Languages :microphone:
Only official language packages are supported. Other language packages might use different selectors to highlight syntax and not work as intended.

<table>
	<thead>
		<tr>
			<th>Language</th>
			<th>Preview</th>
			<th style="width:20%;">Keywords</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>JavaScript</td>
			<td><img src="resources/javascript-preview.png" title="JavaScript" alt="JavaScript"></td>
			<td>
				<code>📦 import</code>,<br>
				<code>📦 export</code>,<br>
				<code>default 🔸</code>,<br>
				<code>class🏷</code>,<br>
				<code>💣 delete</code>,<br>
				<code>function🔧</code>,<br>
				<code>🔧 =></code>,<br>
				<code>🔬 typeof</code>,<br>
				<code>🔬 instanceof</code>,<br>
				<code>📣 yield</code>,<br>
				<code>🚧 console</code>,<br>
				<code>const 💎</code>,<br>
				<code>var 🌀</code>
			</td>
		</tr>
		<tr>
			<td>TypeScript</td>
			<td><img src="resources/typescript-preview.png" title="TypeScript" alt="TypeScript"></td>
			<td>
				<code>📥 import</code>,<br>
				<code>📤 export</code>,<br>
				<code>class🏷</code>,<br>
				<code>function🔧</code>,<br>
				<code>🎛 interface</code>,<br>
				<code>const 💎</code>,<br>
				<code>🔬 typeof</code>,<br>
				<code>🔬 instanceof</code>,<br>
				<code>🚧 console</code>
			</td>
		</tr>
		<tr>
			<td>CSS</td>
			<td><img src="resources/css-preview.png" title="CSS" alt="CSS"></td>
			<td>
				<code>📦 @import</code>,<br>
				<code>💻 @media</code>,<br>
				<code>📹 @keyframes</code>,<br>
				<code>📖 @font-face</code>,<br>
				<code>🔖 @namespace</code>,<br>
				<code>🔣 @charset</code>,<br>
				<code>!important 🚨</code>
			</td>
		</tr>
		<tr>
			<td>Sass</td>
			<td><img src="resources/scss-preview.png" title="SCSS" alt="SCSS"></td>
			<td>
				<code>✨ @mixin</code>,<br>
				<code>👟 @for</code>,<br>
				<code>👣 @each</code>,<br>
				<code>📖 @font-face</code>,<br>
				<code>📹 @keyframes</code>,<br>
				<code>🔧 @function</code>,<br>
				<code>🕯 @while</code>
			</td>
		</tr>
		<tr>
			<td>PHP</td>
			<td><img src="resources/php-preview.png" title="PHP" alt="PHP"></td>
			<td>
				<code>function🔧</code>,<br>
				<code>📰 output</code>,<br>
				<code>🔖 namespace</code>,<br>
				<code>interface 💿</code>,<br>
				<code>include 📥</code>,<br>
				<code>goto 🚀</code>
			</td>
		</tr>
		<tr>
			<td>Python</td>
			<td><img src="resources/python-preview.png" title="Python" alt="Python"></td>
			<td>
				<code>📦 import</code>,<br>
				<code>🔧 def</code>,<br>
				<code>class🏷</code>,<br>
				<code>🌍 global</code>,<br>
				<code>🌍 nonlocal</code>
			</td>
		</tr>
	</tbody>
</table>

## Icon Sets
_Note: not all emoji are supported in each of the custom sets yet!_
<table>
	<thead>
		<tr>
			<th style="width:15%;">Emoji style</th>
			<th>Preview</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Native</td>
			<td>
				<img src="https://cdn.rawgit.com/morkro/atom-emoji-syntax/0fde8866/resources/style-preview-native.png" alt="Native">
			</td>
		</tr>
		<tr>
			<td>Twemoji</td>
			<td>
				<img src="https://cdn.rawgit.com/morkro/atom-emoji-syntax/0fde8866/resources/style-preview-twemoji.png" alt="Twemoji">
			</td>
		</tr>
		<tr>
			<td>Noto Emoji</td>
			<td>
				<img src="https://cdn.rawgit.com/morkro/atom-emoji-syntax/0fde8866/resources/style-preview-noto-emoji.png" alt="Noto Emoji">
			</td>
		</tr>
		<tr>
			<td>EmojiOne™</td>
			<td>
				<img src="https://cdn.rawgit.com/morkro/atom-emoji-syntax/0fde8866/resources/style-preview-emojione.png" alt="EmojiOne™">
			</td>
		</tr>
	</tbody>
</table>

## Settings :wrench:

| Name                                                           | Default |                 Options                |
|:---------------------------------------------------------------|:-------:|:--------------------------------------:|
| **Emoji Style**: Lets you choose between different emoji icon sets | `Native`  | `Native, Twemoji, Noto Emoji, Emoji One` |

## Emoji Settings Page :wrench:
Emoji Syntax comes with its own settings page. There you can customise, activate and deactivate every emoji for each language. The settings page is available through `Packages > Emoji Syntax > Settings` or the `emoji-syntax:settings` command.

![Emoji Settings Page](https://cdn.rawgit.com/morkro/atom-emoji-syntax/master/resources/settingspage-preview.png)

Each language has its own section which you can deactivate. Doing that, the entire language won't have any emoji. The following options are available:

- `Emoji`: opens a modal of emoji to choose from
- `Position`: the position of the emoji around the keyword (e.g. `📦 import` or `import 📦 `)
- `Spacing`: adds spacing between emoji and keyword (e.g. `function 🔧 () {}` or `function🔧 () {}`)

## Contribution :family:

If you want to contribute by either extending/improving a language set, adding a new language, fixing a bug or anything else you can do that by simply sending a pull request.

[API documentation](https://doclets.io/morkro/atom-emoji-syntax/master) via Doclets.

## License :copyright:
The code is available under [MIT License](https://github.com/morkro/atom-emoji-syntax/blob/master/LICENSE).

#### Emoji graphics
- [Twemoji](https://github.com/twitter/twemoji) licensed under [CC-BY 4.0](https://github.com/twitter/twemoji/blob/gh-pages/LICENSE-GRAPHICS)
- [Noto Emoji](https://github.com/googlei18n/noto-emoji) licensed under [SIL Open Font License, version 1.1](https://github.com/googlei18n/noto-emoji/blob/master/fonts/LICENSE)
- [EmojiOne™](https://github.com/Ranks/emojione) licensed under [Creative Commons Attribution 4.0 International](https://github.com/Ranks/emojione/blob/master/LICENSE.md)
