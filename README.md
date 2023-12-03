<br><br>
<p align="center">
  <a href="https://revealjs.com">
  <img src="https://hakim-static.s3.amazonaws.com/reveal-js/logo/v1/reveal-black-text-sticker.png" alt="reveal.js" width="500">
  </a>
  <br><br>
</p>

Reveal.js is an open source HTML presentation framework. It enables anyone with a web browser to create beautiful presentations for free. Check out the live demo at [revealjs.com](https://revealjs.com/).

The framework comes with a powerful feature set including [nested slides](https://revealjs.com/vertical-slides/), [Markdown support](https://revealjs.com/markdown/), [Auto-Animate](https://revealjs.com/auto-animate/), [PDF export](https://revealjs.com/pdf-export/), [speaker notes](https://revealjs.com/speaker-view/), [LaTeX typesetting](https://revealjs.com/math/), [syntax highlighted code](https://revealjs.com/code/) and an [extensive API](https://revealjs.com/api/).

Want to create reveal.js presentation in a graphical editor? Try <https://slides.com>. It's made by the same people behind reveal.js.<br><br>



# Table of Contents
- [Installation](#installation)
  - [Basic installation](#basic-installation)
  - [Full installation](#full-installation)
- [Configuration](#configuration)
  - [Start new presentation](#start-new-presentation)



# Installation

## Basic installation
1. [Click here](#) to download **zip file**.
2. Extract the **zip file**. 
```bash
unzip reveal.js.zip
```
3. Enter in `reveal.js` directory.
```bash
cd reveal.js
```
4. Open Python http server
```bash
python3 -m http.server 8000 # Adding the port is optional
```
Now, you can open Reveal.js on your browser : `http://localhost:8000`

## Full installation
```bash
# Download the source code
git clone https://github.com/shinydisk/reveal.js.git

# Enter to the repository
cd reveal.js

# Open Python http server
python3 -m http.server
```
Now, you can open Reveal.js on your browser : `http://localhost:8000`


# Configuration

## Start new presentation

To start a **new presentation**, duplicate default template (`/templates`) in `/presentations` directory.

1. **Step 1**
Open your terminal and copy the default template to `/presentations` folder.
```bash
cp -r templates/tmp-default presentations/YourPPTName
```

2. **STEP 2**
Launch `http://localhost:8000/presentations/YourPPTName/index.html`
Be sure to replace `YouPPTName` with the one of your choice.

3. **STEP 3**
Now you can open your code editor to configure your presentation.
```bash
code .
```

## Custom Template

Coming soon ...

<div align="center">
  MIT licensed | Copyright © 2023 Shinydisk
</div>