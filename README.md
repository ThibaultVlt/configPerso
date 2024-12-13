# Projet

Mise en place de ficher de configurations utiles pour développer de futurs projets.

## Description du projet

Création et configurations d'un dossier de base de configurations avec des techno que je suis
susceptible d'utiliser dans mes différents projets. Le but n'étant pas de faire un simple copier /
coller dans mes projets. Le but premier est d'avoir un dossier de base, qui sera utilisé, mais
surtout modifié en fonction des technos utilisées durant les projets. Les éléments ne sont pas
définitifs, ils évoluent en permanence et les parties non-utiles sont à retirer afin de ne pas
polluer le projet d'éléments qui ne sont pas nécessaires.

## Table des matières

- [Projet](#projet)
  - [Description du projet](#description-du-projet)
  - [Table des matières](#table-des-matières)
  - [Outils](#outils)
    - [VS Code](#vs-code)
    - [Les navigateurs](#les-navigateurs)
      - [**_Extensions pour les navigateurs_**](#extensions-pour-les-navigateurs)
        - [**_Axe DevTools_**](#axe-devtools)
        - [**_Lighthouse_**](#lighthouse)
        - [**_SeoQuake_**](#seoquake)
        - [**_Wave_**](#wave)
    - [NodeJS](#nodejs)
      - [**_Extensions VS Code pour NodeJS_**](#extensions-vs-code-pour-nodejs)
    - [Git](#git)
      - [**_Extensions VS Code pour Git_**](#extensions-vs-code-pour-git)
  - [Les extensions non liées à un langage](#les-extensions-non-liées-à-un-langage)
    - [Pour le formatage](#pour-le-formatage)
      - [**_EditorConfig_**](#editorconfig)
      - [**_Prettier_**](#prettier)
    - [Pour la qualité du code](#pour-la-qualité-du-code)
      - [**_Webhint_**](#webhint)
        - [**_Extensions pour les navigateurs pour Webhint_**](#extensions-pour-les-navigateurs-pour-webhint)
      - [**_LightHouse_**](#lighthouse-1)
        - [**_Extensions pour les navigateurs pour LightHouse_**](#extensions-pour-les-navigateurs-pour-lighthouse)
      - [**_SonarLint_**](#sonarlint)
      - [**_Axe_**](#axe)
        - [**_Extensions pour les navigateurs pour Axe_**](#extensions-pour-les-navigateurs-pour-axe)
    - [Pour le développement](#pour-le-développement)
      - [**_Live server_**](#live-server)
      - [Todo Tree](#todo-tree)
      - [Code Spell Checker](#code-spell-checker)
      - [Gremlins tracker for Visual Studio Code](#gremlins-tracker-for-visual-studio-code)
      - [:emojisense:](#emojisense)
      - [Partial Diff](#partial-diff)
      - [Browserslist](#browserslist)
    - [Autres](#autres)
  - [Les langages](#les-langages)
    - [Markdown](#markdown)
      - [**_Extensions VS Code pour Markdown_**](#extensions-vs-code-pour-markdown)
      - [**_Formatage pour Markdown_**](#formatage-pour-markdown)
      - [**_Linter pour Markdown_**](#linter-pour-markdown)
    - [JSON](#json)
      - [**_Extensions VS Code pour JSON_**](#extensions-vs-code-pour-json)
      - [**_Formatage pour JSON_**](#formatage-pour-json)
      - [**_Linter pour JSON_**](#linter-pour-json)
    - [HTML](#html)
      - [**_Extensions VS Code pour HTML_**](#extensions-vs-code-pour-html)
      - [**_Extensions pour les navigateurs pour HTML_**](#extensions-pour-les-navigateurs-pour-html)
      - [**_Formatage pour HTML_**](#formatage-pour-html)
      - [**_Linter pour HTML_**](#linter-pour-html)
    - [CSS](#css)
      - [**_Extensions VS Code pour CSS_**](#extensions-vs-code-pour-css)
      - [**_Formatage pour CSS_**](#formatage-pour-css)
      - [**_Linter pour CSS_**](#linter-pour-css)
      - [**_Documentation pour CSS_**](#documentation-pour-css)
    - [SASS](#sass)
      - [**_Extensions VS Code pour SASS_**](#extensions-vs-code-pour-sass)
      - [**_Formatage pour SASS_**](#formatage-pour-sass)
      - [**_Linter pour SASS_**](#linter-pour-sass)
      - [**_Automatisation pour SASS_**](#automatisation-pour-sass)
      - [**_Documentation pour SASS_**](#documentation-pour-sass)
    - [JS](#js)
      - [**_Extensions VS Code pour JS_**](#extensions-vs-code-pour-js)
      - [**_Formatage pour JS_**](#formatage-pour-js)
      - [**_Linter pour JS_**](#linter-pour-js)
      - [**_Documentation pour JS_**](#documentation-pour-js)
    - [PHP](#php)
      - [**_Extensions VS Code pour PHP_**](#extensions-vs-code-pour-php)
  - [Les frameworks CSS](#les-frameworks-css)
    - [Bootstrap](#bootstrap)
      - [**_Extensions VS Code pour Bootstrap_**](#extensions-vs-code-pour-bootstrap)
  - [Les frameworks JS](#les-frameworks-js)
    - [React](#react)
      - [**_Extensions VS Code pour React_**](#extensions-vs-code-pour-react)
  - [DOCKER](#docker)
    - [Description DOCKER](#description-docker)
    - [Structure des fichiers](#structure-des-fichiers)
    - [Prérequis](#prérequis)
    - [Installation et Utilisation](#installation-et-utilisation)
    - [Configuration des Conteneurs](#configuration-des-conteneurs)
      - [Conteneur PHP](#conteneur-php)
      - [Conteneur MySQL](#conteneur-mysql)
      - [Conteneur phpMyAdmin](#conteneur-phpmyadmin)
      - [Volumes](#volumes)
      - [Notes](#notes)
      - [Quelques points à retenir](#quelques-points-à-retenir)
  - [TODO](#todo)

## Outils

### VS Code

Vs Code est un éditeur de code source qui peut être utilisé avec une variété de langages de
programmation, communément appelé un "IDE" (environnement de développement intégré).

Installez VS Code via le [site officiel](https://code.visualstudio.com/)

Tapez `@recommended` dans le filtre des extensions ou `Show recommended extensions` dans la palette
pour voir la liste des extensions recommandées.

Une icône en forme de nuage permet des les installer.
![nuage pour installer toutes les extension recommandées](/mark/recommande.png)

### Les navigateurs

Les navigateurs utilisés seront :

- [Firefox Developer Edition](https://www.mozilla.org/fr/firefox/developer/)
- [Chrome for developers](https://www.google.com/intl/fr/chrome/dev/)
- [Edge](https://developer.microsoft.com/fr-fr/microsoft-edge/)

_(Liste non-exhaustive si vous préférez d'autres navigateurs)._

#### **_Extensions pour les navigateurs_**

##### **_Axe DevTools_**

Axe DevTools est un vérificateur d'accessibilité.

- [Firefox](https://addons.mozilla.org/fr/firefox/addon/axe-devtools/)
- [Chrome](https://chrome.google.com/webstore/detail/axe-devtools-web-accessib/lhdoppojpmngadmnindnejefpokejbdd)
- [Edge](https://microsoftedge.microsoft.com/addons/detail/axe-web-accessibility-t/kcenlimkmjjkdfcaleembgmldmnnlfkn)

##### **_Lighthouse_**

Lighthouse est un outil automatisé open source permettant d'améliorer les performances, la qualité
et l'exactitude de vos applications Web.

- [Firefox](https://addons.mozilla.org/en-US/firefox/addon/google-lighthouse/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search)
- [Chrome](https://chromewebstore.google.com/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk)

##### **_SeoQuake_**

SEOquake vous fournit les principales métriques de référencement ainsi que d'autres outils utiles
tels que l'Audit SEO.

- [Firefox](https://addons.mozilla.org/fr/firefox/addon/seoquake-seo-extension/)
- [Chrome](https://chrome.google.com/webstore/detail/seoquake/akdgnmcogleenhbclghghlkkdndkjdjc)

##### **_Wave_**

WAVE est un outil d'évaluation de l'accessibilité Web.

- [Firefox](https://addons.mozilla.org/fr/firefox/addon/wave-accessibility-tool/)
- [Chrome](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh)
- [Edge](https://microsoftedge.microsoft.com/addons/detail/wave-evaluation-tool/khapceneeednkiopkkbgkibbdoajpkoj?hl=fr)

Pour un retour à la [Table des matières](#table-des-matières)

### NodeJS

Installez-le depuis le [site officiel](https://nodejs.org) en choisissant de préférence la version
LTS et en évitant de cocher la case demandant d'installer les outils supplémentaires pour compiler
des sources (Chocolatey).

Vous pouvez simplement taper `npm i` ou `npm install` dans le terminal pour installer tous les
packages et avoir un projet fonctionnel.

Sinon, renommer, déplacer ou supprimer les fichiers `package.json`, `package_lock.json` et continuez
la lecture.

Dans le terminal, tapez `npm init` et répondez aux questions ou `npm init -y` pour accepter les
réponses par défaut.

#### **_Extensions VS Code pour NodeJS_**

- npm intellisense _(publiée par : Christian Kohler)_
- Node.js Modules Intellisense _(publiée par : Zongmin Lei)_
- Red Hat Dependency Analytics _(publiée par : Red Hat)_

Dans le fichier `.vscode/settings.json`, ajoutez :

```json
{
  "redhat.telemetry.enabled": false
}
```

Pour un retour à la [Table des matières](#table-des-matières)

### Git

Installez-le depuis le [site officiel](https://git-scm.com/downloads).

Si c'est votre première installation de Git, dans le terminal, tapez :

```shell
git config --global core.editor "code --wait"
git config --global core.autocrlf input
git config --global user.name "Prénom NOM"
git config --global user.email prenom.nom@domain.ext
git config --global alias.br branch
git config --global alias.co checkout
git config --global alias.ci commit
git config --global alias.fe fetch
git config --global alias.lg "log --graph --date=relative --pretty=tformat:'%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%an %ad)%Creset'"
git config --global alias.me merge
git config --global alias.pl pull
git config --global alias.ps push
git config --global alias.st status
git config --global alias.sw switch
```

Dans le terminal, tapez `git init` pour initialiser le projet.

#### **_Extensions VS Code pour Git_**

- GitLens — Git supercharged _(publiée par : GitKraken)_
- GitHub Pull Requests _(publiée par : GitHub)_
- Git Graph _(publiée par : mhutchie)_
- gitignore _(publiée par : CodeZombie)_
- GitHub Repositories _(publiée par : GitHub)_

Pour un retour à la [Table des matières](#table-des-matières)

## Les extensions non liées à un langage

### Pour le formatage

#### **_EditorConfig_**

Installez l'extension pour VS Code `EditorConfig for VS Code` _(publié par : EditorConfig)_ puis
faites un clic droit à un endroit vide dans l'explorateur de fichiers et cliquez sur
`Generate .editorconfig` ou tapez `Generate .editorconfig` dans la palette.

Un exemple de configuration serait :

```ini
root = true

[*]
charset = utf-8
end_of_line = lf
trim_trailing_whitespace = true
insert_final_newline = true
max_line_length = 100
# Indentation
indent_style = space
indent_size = 2

[*.{css,js,ts,json,scss}]
indent_size = 4

[*.md]
end_of_line = lf

```

L'ensemble des options est disponible sur le [site d'EditorConfig](https://spec.editorconfig.org/).

Pour un retour à la [Table des matières](#table-des-matières)

#### **_Prettier_**

Installez l'extension pour VS Code `Prettier - Code formatter` _(publié par : Prettier)_ puis dans
le fichier `.vscode/settings.json`, ajoutez :

```json
{
  "editor.defaultFormatter": "esbenp.prettier-vscode"
}
```

Installez le package `prettier` en tapant dans le terminal `npm i -D prettier` ou
`npm install --save-dev prettier`.

Le fichier de configuration doit se nommer `.prettierrc` et être à la racine du projet. Un exemple
de configuration serait :

```json
{
  "proseWrap": "always",
  "htmlWhitespaceSensitivity": "ignore"
}
```

L'ensemble des options est disponible sur le
[site de Prettier](https://prettier.io/docs/en/options.html).

Si des fichiers ou des dossiers doivent être ignorés, il faut créer un fichier `.prettierignore` à
la racine du projet. Un exemple de configuration serait :

```text
docs
node_modules
reports
```

Ajoutez dans le fichier `package.json` :

```json
{
  "scripts": {
    "format": "npx prettier --check --loglevel log .",
    "format-css": "npx prettier --check --loglevel log **/*.css",
    "format-html": "npx prettier --check --loglevel log **/*.html",
    "format-js": "npx prettier --check --loglevel log **/*.js",
    "format-json": "npx prettier --check --loglevel log **/*.json",
    "format-md": "npx prettier --check --loglevel log **/*.md",
    "format-scss": "npx prettier --check --loglevel log **/*.scss",
    "format-ts": "npx prettier --check --loglevel log src/ts/**/*.ts"
  }
}
```

Vous pourrez lancer depuis le terminal `npm run format` pour vérifier le formatage des fichiers du
projet ou `npm run format-css` pour limiter aux CSS par exemple.

Pour un retour à la [Table des matières](#table-des-matières)

### Pour la qualité du code

#### **_Webhint_**

Installez l'extension pour VS Code `webhint` _(publié par : webhint)_.

Installez les packages `hint` et `open-cli` en tapant dans le terminal `npm i -D hint open-cli` ou
`npm install --save-dev hint open-cli`.

Le fichier de configuration doit se nommer `.hintrc` et être à la racine du projet. Le plus simple
est de tapez `npm init hintrc` et de choisir "predefined" puis "web-recommended" dans les options
pour avoir une configuration comme :

```json
{
  "extends": ["web-recommended"]
}
```

L'ensemble des options est disponible sur le
[site de Webhint](https://webhint.io/docs/user-guide/configuring-webhint/summary/).

Si des fichiers ou des dossiers doivent être ignorés, il faut ajouter une option au fichier
`.hintrc` à la racine du projet. Un exemple de configuration serait :

```json
{
  "extends": ["web-recommended"],
  "ignoredUrls": [
    {
      "domain": "cdn\\.jsdelivr\\.net/.*",
      "hints": ["*"]
    },
    {
      "domain": "fonts\\.googleapis\\.com/.*",
      "hints": ["*"]
    },
    {
      "domain": "fonts\\.gstatic\\.com/.*",
      "hints": ["*"]
    }
  ],
  "hints": {
    "html-checker": "error",
    "meta-viewport": "error"
  }
}
```

Ajoutez dans le fichier `package.json` :

```json
{
  "scripts": {
    "webhint": "npx mkdirp reports/webhint && npx hint http://localhost:5500/ --output ./reports/webhint && npx open-cli http://localhost:5500/reports/webhint/http-localhost-5500.html"
  }
}
```

Vous pourrez lancer depuis le terminal `npm run webhint` pour vérifier la qualité des fichiers du
projet.

##### **_Extensions pour les navigateurs pour Webhint_**

- [Edge](https://microsoftedge.microsoft.com/addons/detail/webhint/mlgfbihcfnkaenjpdcngdnhcpkdmcdee)
- [Firefox](https://addons.mozilla.org/fr/firefox/addon/webhint/) _(Non surveillé par la sécurité de
  Mozilla)_
- [Chrome](https://chrome.google.com/webstore/detail/webhint/gccemnpihkbgkdmoogenkbkckppadcag?hl=fr)
  _(Non disponible)_

  Pour un retour à la [Table des matières](#table-des-matières)

#### **_LightHouse_**

Installez le package `lighthouse` en tapant dans le terminal `npm i -D lighthouse` ou
`npm install --save-dev lighthouse`.

L'ensemble des options est disponible sur le
[site de LightHouse](https://github.com/GoogleChrome/lighthouse#cli-options).

Ajoutez dans le fichier `package.json` :

```json
{
  "scripts": {
    "lighthouse": "npx mkdirp reports/lighthouse && npx lighthouse http://localhost:5500/ --output-path ./reports/lighthouse/index.html --view"
  }
}
```

Vous pourrez lancer depuis le terminal `npm run lighthouse` pour vérifier la qualité des fichiers du
projet.

##### **_Extensions pour les navigateurs pour LightHouse_**

- [Firefox](https://addons.mozilla.org/fr/firefox/addon/google-lighthouse/)
- [Chrome](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk/related?hl=fr)

Pour plus d'information sur l'extension `Lighthouse`, aller sur
[la page de l'extension sur Chrome](https://developers.google.com/web/tools/lighthouse/).

#### **_SonarLint_**

Installez l'extension pour VS Code `SonarLint` _(publiée par : SonarSource)_ puis dans le fichier
`.vscode/settings.json`, ajoutez :

```json
{
  "sonarlint.disableTelemetry": true
}
```

#### **_Axe_**

Installez l'extension pour VS Code `axe Accessibility Linter` _(publiée par : Deque Systems)_.

##### **_Extensions pour les navigateurs pour Axe_**

- [Firefox](https://addons.mozilla.org/fr/firefox/addon/axe-devtools/)
- [Chrome](https://chrome.google.com/webstore/detail/axe-devtools-web-accessib/lhdoppojpmngadmnindnejefpokejbdd)
- [Edge](https://microsoftedge.microsoft.com/addons/detail/axe-web-accessibility-t/kcenlimkmjjkdfcaleembgmldmnnlfkn)

Pour un retour à la [Table des matières](#table-des-matières)

### Pour le développement

#### **_Live server_**

Installez l'extension pour VS Code `Live Server` _(publiée par : Ritwick Dey)_ puis dans le fichier
`.vscode/settings.json`, ajoutez :

```json
{
  "liveServer.settings.useWebExt": true
}
```

#### Todo Tree

Installez l'extension pour VS Code `Todo Tree` _(publiée par : Gruntfuggly)_ puis dans le fichier
`.vscode/settings.json`, ajoutez :

```json
{
  "todo-tree.general.tags": ["BUG", "HACK", "FIXME", "TODO", "XXX", "[ ]"]
}
```

#### Code Spell Checker

Installez l'extension pour VS Code `Code Spell Checker` _(publiée ar : Street Side Software)_.

Installez les packages `cspell`, `@cspell/dict-fr-fr` et `@cspell/dict-lorem-ipsum` en tapant dans
le terminal `npm i -D cspell @cspell/dict-fr-fr @cspell/dict-lorem-ipsum` ou
`npm install --save-dev cspell @cspell/dict-fr-fr @cspell/dict-lorem-ipsum`, puis :

```shell
npx cspell link add @cspell/dict-fr-fr
npx cspell link add @cspell/dict-lorem-ipsum
```

Le fichier de configuration doit se nommer `.cspell.json` et être à la racine du projet. Un exemple
de configuration serait :

```json
{
  "ignorePaths": [
    "**/node_modules/**",
    "**/docs/**",
    "**/.git/**",
    "**/reports/**",
    ".vscode",
    ".*rc",
    "package.json",
    "package-lock.json"
  ],
  "language": "fr-fr,en,lorem-ipsum",
  "version": "0.2"
}
```

L'ensemble des options est disponible sur le [site de cspell](https://cspell.org/configuration/).

Pour un retour à la [Table des matières](#table-des-matières)

#### Gremlins tracker for Visual Studio Code

Installez l'extension pour VS Code `Gremlins tracker for Visual Studio Code` _(publiée par : Nicolas
Hoizey)_ puis dans le fichier `.vscode/settings.json`, ajoutez :

```json
{
  "gremlins.showInProblemPane": true
}
```

#### :emojisense:

Installez l'extension pour VS Code `:emojisense:` _(publiée par ; Matt Bierner)_ puis dans le
fichier `.vscode/settings.json`, ajoutez :

```json
{
  "emojisense.languages": {
    "git-commit": true,
    "html": true,
    "markdown": true,
    "plaintext": {
      "emojiDecoratorsEnabled": false,
      "markupCompletionsEnabled": false
    },
    "scminput": true
  }
}
```

#### Partial Diff

Installez l'extension pour VS Code `Partial Diff` _(publiée par : Ryuichi Inagaki)_ puis dans le
fichier `.vscode/settings.json`, ajoutez :

```json
{
  "partialDiff.enableTelemetry": false
}
```

Pour un retour à la [Table des matières](#table-des-matières)

#### Browserslist

Installez l'extension pour VS Code `browserslist` _(publiée par : webben)_.

Installez les packages `browserslist`, `update-browserslist-db` `@github/browserslist-config` en
tapant dans le terminal `npm i -D browserslist update-browserslist-db @github/browserslist-config`
ou `npm install --save-dev browserslist update-browserslist-db @github/browserslist-config`.

Le fichier de configuration doit se nommer `.browserslistrc` et être à la racine du projet. Un
exemple de configuration serait :

```ini
defaults
maintained node versions

extends @github/browserslist-config
```

L'ensemble des options est disponible sur le [site de browserslist](https://browsersl.ist/).

Vous pourrez lancer depuis le terminal `npx browserslist` pour vérifier la liste des navigateurs
supportés par le projet, ou bien `npx update-browserslist-db` pour mettre à jour la liste des
navigateurs supportés par le projet.

### Autres

- indent-rainbow _(publiée par : oderwat)_
- IntelliCode _(publiée par : Microsoft)_
- Output Colorizer _(publiée par : IBM)_
- Path Intellisense _(publiée par : Christian Kohler)_
- SVG _(publiée par : jock)_
- TabOut _(publiée par : Albert Romkes)_

Dans le fichier `.vscode/settings.json`, ajoutez :

```json
{
  "editor.codeActionsOnSave": {
    "source.addMissingImports": true,
    "source.fixAll": true,
    "source.organizeImports": true
  },
  "editor.formatOnSave": true,
  "editor.linkedEditing": true,
  "editor.stickyScroll.enabled": true,
  "editor.unicodeHighlight.invisibleCharacters": false,
  "editor.wordWrap": "wordWrapColumn",
  "editor.wordWrapColumn": 120,
  "telemetry.telemetryLevel": "off",
  "terminal.integrated.defaultProfile.windows": "Command Prompt",
  "window.commandCenter": true,
  "workbench.editor.wrapTabs": true
}
```

Pour un retour à la [Table des matières](#table-des-matières)

## Les langages

### Markdown

#### **_Extensions VS Code pour Markdown_**

- Markdown All in One _(publiée par : Yu Zhang)_
- markdownlint _(publiée par : David Anson)_

Dans le fichier `.vscode/settings.json`, ajoutez :

```json
{
  "markdown.validate.enabled": true
}
```

#### **_Formatage pour Markdown_**

`Prettier` prend en charge Markdown.

#### **_Linter pour Markdown_**

Installez le package `markdownlint-cli` en tapant dans le terminal `npm i -D markdownlint-cli` ou
`npm install --save-dev markdownlint-cli`.

Le fichier de configuration doit se nommer `.markdownlintrc` et être à la racine du projet. Un
exemple de configuration serait :

```json
{
  "default": false
}
```

L'ensemble des options est disponible sur le
[site de markdownlint-cli](https://github.com/igorshubovych/markdownlint-cli#configuration).

Si des fichiers ou des dossiers doivent être ignorés, il faut créer un fichier `.markdownlintignore`
à la racine du projet. Un exemple de configuration serait :

```text
docs
node_modules
reports
```

Ajoutez dans le fichier `package.json` :

```json
{
  "scripts": {
    "lint-md": "npx markdownlint-cli --fix **/*.md"
  }
}
```

Vous pourrez lancer depuis le terminal `npm run lint-md` pour vérifier le code des fichiers Markdown
du projet.

Pour un retour à la [Table des matières](#table-des-matières)

### JSON

#### **_Extensions VS Code pour JSON_**

- json _(publiée par : ZainChen)_

#### **_Formatage pour JSON_**

`Prettier` prend en charge JSON.

#### **_Linter pour JSON_**

Installez le package `@prantlf/jsonlint` en tapant dans le terminal `npm i -D @prantlf/jsonlint` ou
`npm install --save-dev @prantlf/jsonlint`.

Le fichier de configuration doit se nommer `.jsonlintrc` et être à la racine du projet. Un exemple
de configuration serait :

```json
{
  "check": true,
  "comments": true,
  "compact": true,
  "continue": true,
  "diff": true,
  "in-place": false,
  "log-files": true,
  "no-duplicate-keys": true,
  "patterns": ["**/*.json", "**/.*rc", "!**/.browserlistrc", "!**/node_modules"],
  "sort-keys": false,
  "trailing-commas": false,
  "trailing-newline": true,
  "trim-trailing-commas": true
}
```

L'ensemble des options est disponible sur le
[site de jsonlint](https://github.com/prantlf/jsonlint#options).

Ajoutez dans le fichier `package.json` :

```json
{
  "scripts": {
    "lint-json": "npx jsonlint"
  }
}
```

Vous pourrez lancer depuis le terminal `npm run lint-json` pour vérifier le code des fichiers JSON
du projet.

Pour un retour à la [Table des matières](#table-des-matières)

### HTML

#### **_Extensions VS Code pour HTML_**

- HTML CSS Support _(publiée par : ecmel)_
- HtmlHint _(publiée par : HTMLHint)_

#### **_Extensions pour les navigateurs pour HTML_**

- [Firefox](https://addons.mozilla.org/fr/firefox/addon/html-validator/)
- [Chrome](https://chrome.google.com/webstore/detail/html-validator/mpbelhhnfhfjnaehkcnnaknldmnocglk?hl=fr)

#### **_Formatage pour HTML_**

`Prettier` prend en charge HTML.

#### **_Linter pour HTML_**

Installez le package `htmlhint` en tapant dans le terminal `npm i -D htmlhint` ou
`npm install --save-dev htmlhint`.

Le fichier de configuration doit se nommer `.htmlhintrc` et être à la racine du projet. Un exemple
de configuration serait :

```json
{
  "doctype-first": true,
  "doctype-html5": true,
  "html-lang-require": true,
  "head-script-disabled": true,
  "style-disabled": true,
  "script-disabled": false,
  "title-require": true,
  "attr-lowercase": true,
  "attr-no-duplication": true,
  "attr-no-unnecessary-whitespace": true,
  "attr-unsafe-chars": true,
  "attr-value-double-quotes": true,
  "attr-value-not-empty": true,
  "attr-sorted": true,
  "attr-whitespace": true,
  "alt-require": true,
  "input-requires-label": true,
  "tags-check": true,
  "tag-pair": true,
  "tag-self-close": true,
  "tagname-lowercase": true,
  "tagname-specialchars": true,
  "empty-tag-not-self-closed": false,
  "src-not-empty": true,
  "href-abs-or-rel": "abs",
  "id-class-ad-disabled": true,
  "id-class-value": "hump",
  "id-unique": true,
  "inline-script-disabled": true,
  "inline-style-disabled": true,
  "space-tab-mixed-disabled": "space",
  "spec-char-escape": true
}
```

L'ensemble des options est disponible
[sur le site de HtmlHint](https://htmlhint.com/docs/user-guide/list-rules).

Ajoutez dans le fichier `package.json` :

```json
{
  "scripts": {
    "lint-html": "npx htmlhint **/*.html --ignore docs/**/*.html reports/**/*.html"
  }
}
```

Vous pourrez lancer depuis le terminal `npm run lint-html` pour vérifier le code des fichiers HTML
du projet.

Installez les packages `html-w3c-validator` et `start-server-and-test` en tapant dans le terminal
`npm i -D html-w3c-validator start-server-and-test` ou
`npm install --save-dev html-w3c-validator start-server-and-test`.

Le fichier de configuration doit se nommer `.html-w3c-validatorrc.json` et être à la racine du
projet. Un exemple de configuration serait :

```json
{
  "urls": ["http://127.0.0.1:5500/"]
}
```

L'ensemble des options est disponible
[sur le site de html-w3c-validator](https://github.com/Divlo/html-w3c-validator#%EF%B8%8F-configuration).

Ajoutez dans le fichier `package.json` :

```json
{
  "scripts": {
    "start": "serve \"./index.html\"",
    "validate-html": "start-server-and-test \"start\" \"http://127.0.0.1:5500\" \"html-w3c-validator\""
  }
}
```

Vous pourrez lancer depuis le terminal `npm run validate-html` pour vérifier la conformité du code
des fichiers HTML du projet.

Pour un retour à la [Table des matières](#table-des-matières)

### CSS

#### **_Extensions VS Code pour CSS_**

- IntelliSense for CSS class names in HTML _(publiée par : Zignd)_
- Stylelint _(publiée par : Stylelint)_

Dans le fichier `.vscode/settings.json`, ajoutez :

```json
{
  "css.lint.compatibleVendorPrefixes": "warning",
  "css.lint.duplicateProperties": "warning",
  "css.lint.ieHack": "error",
  "css.lint.important": "warning",
  "css.lint.importStatement": "warning",
  "css.lint.universalSelector": "warning",
  "css.lint.unknownVendorSpecificProperties": "warning",
  "css.lint.zeroUnits": "warning",
  "css.validate": false,
  "html-css-class-completion.enableEmmetSupport": true,
  "scss.lint.compatibleVendorPrefixes": "warning",
  "scss.lint.duplicateProperties": "warning",
  "scss.lint.ieHack": "error",
  "scss.lint.important": "warning",
  "scss.lint.importStatement": "warning",
  "scss.lint.universalSelector": "warning",
  "scss.lint.unknownVendorSpecificProperties": "warning",
  "scss.lint.zeroUnits": "warning",
  "scss.validate": false,
  "stylelint.snippet": ["css", "less", "postcss", "sass"],
  "stylelint.validate": ["css", "less", "postcss", "sass"]
}
```

#### **_Formatage pour CSS_**

`Prettier` prend en charge CSS.

#### **_Linter pour CSS_**

Installez le package `stylelint` en tapant dans le terminal `npm i -D stylelint` ou
`npm install --save-dev stylelint`.

Le fichier de configuration doit se nommer `.stylelintrc` et être à la racine du projet. Le plus
simple est de tapez `npm init stylelint` pour avoir une configuration comme :

```json
{
  "extends": ["stylelint-config-standard"]
}
```

L'ensemble des options est disponible sur le
[site de Stylelint](https://stylelint.io/user-guide/configure).

Si des fichiers ou des dossiers doivent être ignorés, il faut créer un fichier `.stylelintignore` à
la racine du projet. Un exemple de configuration serait :

```text
docs
node_modules
reports
```

Ajoutez dans le fichier `package.json` :

```json
{
  "scripts": {
    "lint-css": "npx stylelint **/*.css --formatter verbose"
  }
}
```

Vous pourrez lancer depuis le terminal `npm run lint-css` pour vérifier le code des fichiers CSS du
projet.

#### **_Documentation pour CSS_**

Installez les packages `styledown`, `mkdirp` et `foreach-cli` en tapant dans le terminal
`npm i -D styledown mkdirp foreach-cli` ou `npm install --save-dev styledown mkdirp foreach-cli`.

Le fichier de configuration doit se nommer `config.md` et être à la racine du projet. Le plus simple
est de tapez `npx styledown --conf > config.md` puis d'ajouter les CSS de votre projet pour avoir
une configuration comme :

```markdown
# Styleguide options

### Head

    <meta name='viewport' content='width=device-width, initial-scale=1' />
    <script src='https://cdn.rawgit.com/styledown/styledown/v1.0.7/data/styledown.js'></script>
    <link rel='stylesheet' href='https://cdn.rawgit.com/styledown/styledown/v1.0.7/data/styledown.css' />
    <link rel='stylesheet' href='/dist/css/desktop.css' />
    <link rel='stylesheet' href='/dist/css/mobile.css' />
    <link rel='stylesheet' href='/dist/css/print.css' />

### Body

    <div class='sg-container' sg-content></div>
```

Ajoutez dans le fichier `package.json` :

```json
{
  "scripts": {
    "document-css": "npx mkdirp docs/css && npx foreach --glob src/css/**/*.css --execute \"npx styledown #{path} config.md > docs/css/#{name}.html\""
  }
}
```

Vous pourrez lancer depuis le terminal `npm run document-css` pour documenter les fichiers CSS du
projet.

Pour un retour à la [Table des matières](#table-des-matières)

### SASS

#### **_Extensions VS Code pour SASS_**

- Live Sass Compiler _(publiée par : Glenn Marks)_
- SCSS IntelliSense _(publiée par : mrmlnc)_
- vscode-sassdoc _(publiée par : rafikis75)_
- SCSS Formatter _(publiée par : Sibiraj)_

Dans le fichier `.vscode/settings.json`, ajoutez :

```json
{
  "[scss]": {
    "editor.defaultFormatter": "sibiraj-s.vscode-scss-formatter"
  },
  "liveSassCompile.settings.autoprefix": true,
  "liveSassCompile.settings.formats": [
    {
      "extensionName": ".css",
      "format": "compressed",
      "savePath": "/dist/css/",
      "savePathReplacementPairs": null
    }
  ],
  "liveSassCompile.settings.showOutputWindowOn": "Warning",
  "liveSassCompile.settings.useNewCompiler": true,
  "liveSassCompile.settings.watchOnLaunch": true
}
```

#### **_Formatage pour SASS_**

`Prettier` prend en charge SASS.

#### **_Linter pour SASS_**

`Stylelint` prend en charge SASS.

Ajoutez dans le fichier `package.json` :

```json
{
  "scripts": {
    "lint-scss": "npx stylelint **/*.scss --formatter verbose"
  }
}
```

Vous pourrez lancer depuis le terminal `npm run lint-scss` pour vérifier le code des fichiers SASS
du projet.

#### **_Automatisation pour SASS_**

Installez le package `sass` en tapant dans le terminal `npm i -D sass` ou
`npm install --save-dev sass`.

Ajoutez dans le fichier `package.json` :

```json
{
  "scripts": {
    "compile-css": "npx sass --style=compressed --watch src/scss:dist/css"
  }
}
```

Vous pourrez lancer depuis le terminal `npm run compile-css` pour compiler le code des fichiers SASS
du projet en fichiers CSS. L'option `--watch` surveille les modifications et recompile à la volée.

**ATTENTION : il ne faut pas activer l'extension Live Sass Compiler et lancer `npm run compile-css`
en même temps.**

#### **_Documentation pour SASS_**

Installez le package `sassdoc` en tapant dans le terminal `npm i -D sassdoc` ou
`npm install --save-dev sassdoc`.

Le fichier de configuration doit se nommer `.sassdocrc` et être à la racine du projet. Un exemple de
configuration serait :

```json
{
  "dest": "./docs/scss/",
  "strict": true,
  "verbose": true
}
```

L'ensemble des options est disponible sur le
[site de sassdoc](http://sassdoc.com/configuration/#options).

Ajoutez dans le fichier `package.json` :

```json
{
  "scripts": {
    "document-scss": "npx sassdoc src/scss"
  }
}
```

Vous pourrez lancer depuis le terminal `npm run document-scss` pour documenter les fichiers SASS du
projet.

Pour un retour à la [Table des matières](#table-des-matières)

### JS

#### **_Extensions VS Code pour JS_**

- JavaScript (ES6) code snippets _(publiée par : charalampos karypidis)_
- ESLint _(publiée par : Microsoft)_
- CodeMetrics _(publiée par : Kiss Tamás)_
- Document This _(publiée par : oouo-diogo-perdigao)_
- DevSkim _(publiée par : Microsoft DevLabs)_
- Import Cost _(publiée par : Wix)_

Dans le fichier `.vscode/settings.json`, ajoutez :

```json
{
  "MS-CST-E.vscode-devskim.rules.enableBestPracticeSeverityRules": true,
  "MS-CST-E.vscode-devskim.rules.enableManualReviewSeverityRules": true
}
```

#### **_Formatage pour JS_**

ESLint, installé juste après, prend en charge le formatage de JS. Dans le fichier
`.vscode/settings.json`, ajoutez :

```json
{
  "[javascript]": {
    "editor.defaultFormatter": "dbaeumer.vscode-eslint"
  },
  "eslint.format.enable": true
}
```

#### **_Linter pour JS_**

Installez les packages `eslint`, `eslint-config-prettier` et `eslint-plugin-compat` en tapant dans
le terminal `npm i -D eslint eslint-config-prettier eslint-plugin-compat` ou
`npm install --save-dev eslint eslint-config-prettier eslint-plugin-compat`.

Le fichier de configuration doit se nommer `.eslintrc` et être à la racine du projet. Le plus simple
est de tapez `nx eslint --init` et de choisir :

- To check syntax, find problems, and enforce code style
- JavaScript modules (import/export)
- None of these
- No
- Sélectionner Browser et désélectionner Node
- Use a popular style guide
- Standard
- JSON
- Yes
- Npm

dans les options pour avoir une configuration comme :

```json
{
  "env": {
    "browser": true,
    "es2021": true
  },
  "extends": "standard",
  "overrides": [],
  "parserOptions": {
    "ecmaVersion": "latest",
    "sourceType": "module"
  },
  "rules": {}
}
```

puis ajouter :

```json
{
  "plugins": ["compat"],
  "extends": ["standard", "plugin:compat/recommended", "prettier"]
}
```

L'ensemble des options est disponible sur le
[site de eslint](https://eslint.org/docs/latest/use/configure/).

Si des fichiers ou des dossiers doivent être ignorés, il faut créer un fichier `.eslintignore` à la
racine du projet. Un exemple de configuration serait :

```text
docs
node_modules
reports
```

Ajoutez dans le fichier `package.json` :

```json
{
  "scripts": {
    "lint-js": "npx eslint --fix **/*.js"
  }
}
```

Vous pourrez lancer depuis le terminal `npm run lint-js` pour vérifier le code des fichiers JS du
projet.

#### **_Documentation pour JS_**

Grâce à l'extension `Document This` _(publiée par : oouo-diogo-perdigao)_, il suffit de taper `/**`
au-dessus d'une classe ou d'une fonction pour auto-générer une partie de la documentation.

Installez le package `jsdoc` en tapant dans le terminal `npm i -D jsdoc` ou
`npm install --save-dev jsdoc`.

Le fichier de configuration doit se nommer `.jsdocrc.json` et être à la racine du projet. Un exemple
de configuration serait :

```json
{
  "opts": {
    "destination": "docs/js",
    "template": "templates/default",
    "encoding": "utf8",
    "recurse": true,
    "verbose": true
  },
  "templates": {
    "monospaceLinks": true
  }
}
```

L'ensemble des options est disponible sur le
[site de jsdoc](https://jsdoc.app/about-configuring-jsdoc.html).

Ajoutez dans le fichier `package.json` :

```json
{
  "scripts": {
    "document-js": "npx jsdoc --configure .jsdocrc.json src/js/"
  }
}
```

Vous pourrez lancer depuis le terminal `npm run document-js` pour documenter les fichiers JS du
projet.

Pour un retour à la [Table des matières](#table-des-matières)

### PHP

FIXME Partie PHP à compléter

#### **_Extensions VS Code pour PHP_**

- PHP IntelliSense _(publiée par : Damjan Cvetko)_
- PHP Intelephense _(publiée par : Ben Mewburn)_
- PHP Extension Pack _(publiée par : Xdebug)_
- PHP DocBlocker  _(publiée par : Neil Brayfield)_
- PHP Namespace Resolver  _(publiée par : Mehedi Hassan)_
- php cs fixer  _(publiée par : junstyle)_

Dans le fichier `.vscode/settings.json`, ajoutez :

```json
{

}
```

## Les frameworks CSS

### Bootstrap

#### **_Extensions VS Code pour Bootstrap_**

- Bootstrap 5 Icon Snippets _(publiée par : oouo-diogo-perdigao)_
- Bootstrap 5 Quick Snippets _(publiée par : Joshua Needham)_

## Les frameworks JS

### React

#### **_Extensions VS Code pour React_**

FIXME Chercher plus de renseignements pour BABEL
FIXME A voir [lien vers site pour configurer babel](https://medium.com/@ns-tech-learn/how-to-install-babel-and-config-in-react-js-project-39c953527560)

- Babel JavaScript _(publiée par : Michael McDermott)_

Créez un fichier de configuration Babel nommé `.babelrc` à la racine de votre projet. Ajoutez le
contenu suivant :

```json
{
  "préréglages": ["@babel/preset-env", "@babel/preset-react"]
}
```

Ce fichier de configuration indique à Babel d'utiliser les préréglages spécifiés
(`@babel/preset-env` et `@babel/preset-react`) lors de la transpilation de votre code.

Ouvrez votre fichier `package.json` et ajoutez un champ `babel` pour spécifier le fichier de
configuration Babel. Ajoutez ou mettez à jour la section `scripts` comme suit :

```json
"scripts" : {
"start" : "start-scripts",
"build" : "build-scripts",
"test" : "test-scripts",
"eject" : "eject-scripts",
"babel" : "babel src -d build"
},
```

Dans cet exemple, un script "babel" est ajouté pour exécuter Babel sur le répertoire "src" et
générer le code transpilé dans le répertoire "build".

L'ensemble des options est disponible sur le [site de babel](https://babeljs.io/)

Pour un retour à la [Table des matières](#table-des-matières)

## DOCKER

Configuration Docker pour Développement Web

Ce projet fournit une configuration Docker prête à l'emploi pour un environnement de développement web. Il inclut des conteneurs pour un serveur PHP, une base de données MySQL et une interface phpMyAdmin, afin de faciliter le développement et le test d'applications web.

### Description DOCKER

- **Serveur PHP** : Utilise PHP 8.3 avec Apache.
- **Base de données MySQL** : MySQL 8.4.3 avec un volume persistant pour stocker les données.
- **phpMyAdmin** : Fournit une interface web pour gérer la base de données MySQL.

La configuration est idéale pour les développeurs web souhaitant travailler rapidement sur des projets PHP avec une base de données relationnelle.

---

### Structure des fichiers

- **`php/`** : Répertoire où placer les fichiers PHP de votre projet.
- **`docker-compose.yml`** : Fichier de configuration Docker Compose.
- **`DockerFile`** : Fichier de construction pour le conteneur PHP avec Apache.

---

### Prérequis

- [Docker Desktop](https://www.docker.com/products/docker-desktop) installé sur votre machine.
- [Visual Studio Code](https://code.visualstudio.com/) (facultatif mais recommandé).
- Docker Compose intégré.

---

### Installation et Utilisation

1. **Assurez-vous que Docker Desktop est lancé** et prêt à exécuter les conteneurs.
2. Assurez-vous que les image ne sont pas utilisé dans un autres conteneur, si c'est le cas, supprimer le conteneur.
3. Ouvrez le projet dans VS Code ou un terminal.
4. Exécutez la commande suivante pour construire les images Docker :

    ```bash
    docker-compose build
    ```

5. Lancez les conteneurs avec la commande :

    ```bash
    docker-compose up
    ```

6. Une fois les conteneurs démarrés :

   - Accédez au serveur PHP sur [port 8000](http://localhost:8000).
   - Accédez à phpMyAdmin sur [port 8081](http://localhost:8081).

7. Arrêter les Conteneurs

- Pour arrêter les conteneurs, utilisez la commande suivante :

    ```bash
    docker-compose build
    ```

### Configuration des Conteneurs

#### Conteneur PHP

- Image : php:8.3-apache
- Port exposé : 8000
- Dossier synchronisé : ./php vers /var/www/html dans le conteneur.
- Modules installés : mysqli, pdo, pdo_mysql.

#### Conteneur MySQL

- **Image :** mysql:8.4.3
- **Port exposé :** 3307
- **Variables d'environnement :**
  - MYSQL_ROOT_PASSWORD: root
  - MYSQL_DATABASE: test
  - MYSQL_USER: user
  - MYSQL_PASSWORD: password
- **Volume :** dbdata pour persister les données de la base de données.

#### Conteneur phpMyAdmin

- **Image :** phpmyadmin/phpmyadmin
- **Port exposé :** 8081
- **Configuration :**
  - Hôte MySQL : mysql
  - Mot de passe root : root

#### Volumes

- dbdata : Stocke les données de MySQL de manière persistante.

#### Notes

Assurez-vous que les ports utilisés (8000, 8081, 3307) ne sont pas déjà occupés par d'autres services.
Si vous souhaitez modifier la configuration (comme les mots de passe ou les ports), mettez à jour le fichier docker-compose.yml avant de démarrer les conteneurs.

#### Quelques points à retenir

- Si tu veux ajouter ou personnaliser un autre point, fais-le-moi savoir !
- Le projet à pour but de parfaire mes configurations et il se peut qu'il évoluera

---

## TODO

Cette partie est utile afin de garder en tête des éléments manquants et des potentielles
améliorations à ajouter.

TODO Faire les config PHP et mySQL

TODO Faire les settings via les paramètres VS code (ctrl + ,)

TODO Ajouter les settings dans le Readme.md

TODO ncu

FIXME si erreur :ncu : Impossible de charger le fichier C:\Users\Thibault\AppData\Roaming\npm\ncu.ps1, car
l’exécution de scripts est désactivée sur ce système. Pour plus d’informations, consultez
about_Execution_Policies à l’adresse https://go.microsoft.com/fwlink/?LinkID=135170.
Au caractère Ligne:1 : 1
+ ncu
+ ~~~
    + CategoryInfo          : Erreur de sécurité : (:) [], PSSecurityException
    + FullyQualifiedErrorId : UnauthorizedAccess

alors faire la commande : Set-ExecutionPolicy Unrestricted -Scope CurrentUser -Force ,dans powershell

TODO Config pour react

TODO Babel JavaScript _(publiée par : Michael McDermott)_

TODO voir gulp et grunt

TODO Autoprefixer

---

Pour un retour à la [Table des matières](#table-des-matières)
