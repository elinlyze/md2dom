# md2dom — From Markdown to Clean, Shareable HTML

## Disclaimer
This project makes use of [marked.js](https://marked.js.org/) (included in ./lib/) and some browser-native JavaScript tools.  
  
## Overview
**md2dom** is a lightweight, browser-based tool that converts Markdown into clean, self-contained HTML.  
It’s designed for developers, writers, and open-source maintainers who want an easy way to turn documentation or notes into web pages — without build steps, dependencies, or command-line tooling.  
Here is a live version I am hosting on the web: https://md2dom.elinlyze.com/

## Why It Exists
Markdown is beautiful in its simplicity, but getting it onto the web often involves too much ceremony.  
Static site generators, CI pipelines, and templating systems can be overkill when you just need a readable page.  
**md2dom** was built to bridge that gap, to take your Markdown and generate a standards-compliant, portable HTML document in seconds.

## Key Principles
- **Open and transparent:** Everything runs in your browser. No servers, no tracking, no uploads.  
- **Accessible design:** Dark and light themes, adjustable typography, and minimal layout options keep output readable everywhere.  
- **Safe by default:** HTML sanitization ensures exported documents are secure and clean.  
- **Portable:** Export as plain HTML or HTML + CSS, ready to host anywhere or embed in any project.

## Use Cases
- Publishing small documentation pages or project READMEs.  
- Quickly prototyping or previewing Markdown-based content.  
- Sharing static HTML versions of text files without additional tooling.  
- Teaching or demonstrating Markdown rendering in educational settings.

## Community and Collaboration
**md2dom** is open source because the web should stay open.  
You’re invited to fork it, modify it, or integrate its logic into your own tools.  
Contributions, issues, and discussion are always welcome, improvements grow best in the open.  
[Source Code](https://github.com/elinlyze/md2dom)
  
## A Note on Development
This project was created with a lot of curiosity, patience, and even some help from AI tools along the way for code clarity (sorry).  
I’m not an HTML, JS or frontend expert. **md2dom** is the result of learning by doing, experimenting and the help of people much smarter than me.  
  
If you spot issues, have ideas for improvements or just want to help make it cleaner, I’d love your feedback and contributions.  
Every suggestion helps make this a better little open-source utility.  
  
## License Notes  
Released under the [MIT License](./LICENSE).  
Includes [Marked](https://marked.js.org/), also released under MIT.  
© 2011–2018 [Christopher Jeffrey](https://github.com/chjj/), © 2018–present [MarkedJS](https://github.com/markedjs/).

