# README

## About

This is a *lightweight* webpage framework aimed to be easily implemented at your own website!

It aims to support: 

- Single file implementation
- Syntax Highlightning
- Styling modifications
- Repository listing
- Index, blog and devlog layouts
## How it works:

1. You create a directory named "projects" in your project.
2. In there, create a file named "index.html" and include a link to a script, from *my* site
3. The linked script then checks for a file named "config.mul"
4. If not found, it will use the [default.mps](default.mps) config located at *my* site
5. It will then check if there exists directories containing syntax (inside /repos)
6. Then, diplay them as projects in index.html similar to Github repositories

- "www.your-site.com/projects" - example url diplaying projects
- "www.your-site.com/projects/my-repo/" - example url diplaying a project
- "www.your-site.com/projects/my-repo/code.c" - example url diplaying the syntax of file of a project

### config.mul?

**MPS** - "Multipurpose Syntax" - so far a simple markup/config language I created.

## Implementation:

### Alternative 1 (not tested yet):
1. Create a directory named "projects" in your directory
2. Inside, create "index.html"
3. Copy the following content to **YOUR** index.html inside a directory named "repos":
```html
<!-- ADD TO BOTTOM OF BODY -->
  <script src="https://sibjor.se/url/script.js" defer></script>
</body>
```

### Alternative 2:
1. Make a fork out of (this repository)[https://github.com/sibjor/url/]
2. Add your own projects as submodules in the "projects" directory of the fork
3. Add your fork as a submodule inside your website repository

## Done so far:

### Core:
[x] Initialize [Repository](https://github.com/sibjor/url/)
[x] [README](#readme) first version

## In progress:

### Core:

[ ] [Implementation 1](#implementation)
[ ] MUlang structure
[ ] Availible at my own website

### Syntax Highlighting:
[ ] **MPS**
[ ] **Markdown**
[ ] **HTML**
[ ] **CSS**
[ ] **Javascript**
[ ] **C**
[ ] **C++**
[ ] **C#**

#### Text Formatting:

[ ] **Index**
[ ] **Blog**
[ ] **Devlog**