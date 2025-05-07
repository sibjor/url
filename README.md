# README

## About

This is a *lightweight* webpage framework aimed to be easily implemented at your own website!

It runs on **MPS** or **MUPUS** [(Multipurpose Syntax)](https://sibjor.se/repos/mps)

It aims to provide: 

- Single HTML element implementation
- Syntax Highlightning
- Website pages [layouts](#models)
- Configuration

## Installation:

1. In your website root, create a directory named exactly as one of the **[availible models](#models)**
2. Create a **index.html** in each one of those
3. Copy the following to **YOUR** root **index.html**:
```html
<!-- ADD TO TOP OF HEAD -->
 <head>
  <script src="https://sibjor.se/repos/url/script.js"></script>
```
## How it works:

1. The linked script loads as primary element at your first page (root **index.html**).
2. It then checks for a file named **config.mps** in the same directory
3. If not found, it will use the default **[config](https://sixten.se/projects/url/default.mps)** located at *my* site
4. It will then check if there exists directories or and/or files named as one of the [supported models](#models)
5. Then, diplay your website as preferred

## Work:

- [x] Initialize [Repository](https://github.com/sibjor/url)
- [x] [README](#readme) first version
- [ ] Initialize [MUPUS]()

### Models:

(Don't copy the **/** symbol)

- [ ] /projects
- [ ] /devlog
- [ ] /blog
- [ ] /game
- [ ] /docs
- [ ] status.html
- [ ] index.html

## Models Configuration:

First, create **config.mps** in website root directory

Then

### index.html:

### status.html:

### Projects:

```mupus
***
```
- "www.your-site.com/projects" - example url diplaying projects
- "www.your-site.com/projects/my-repo/" - example url diplaying a project
- "www.your-site.com/projects/my-repo/code.c" - example url diplaying the syntax of file of a project

### Devlog:

### Blog:

### Game:

### Docs:

### Wiki: