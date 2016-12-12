# Awesome Draft.js [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[Draft.js](https://facebook.github.io/draft-js/) is a framework for building rich text editors in React.

**Table of Contents**

- [Community](https://github.com/nikgraf/awesome-draft-js#community)
- [Presentations](https://github.com/nikgraf/awesome-draft-js#presentations)
- [Projects on Top of Draft.js](https://github.com/nikgraf/awesome-draft-js#projects-on-top-of-draftjs)
- [Common Utilities](https://github.com/nikgraf/awesome-draft-js#common-utilities)
- [Blog Posts & Articles](https://github.com/nikgraf/awesome-draft-js#blog-posts--articles)
- [Live Demos](https://github.com/nikgraf/awesome-draft-js#live-demos)
- [License](https://github.com/nikgraf/awesome-draft-js#license)

## Community

* [Slack channel](https://draftjs.herokuapp.com/)

## Presentations
* [Rich Text Editing with React @ React.js Conf 2016 by Isaac Salier-Hellendag ](https://www.youtube.com/watch?v=feUYwoLhE_4)
* [Rich text editing with Draft.js & DraftJS Plugins by Nik Graf](https://www.youtube.com/watch?v=gxNuHZXZMgs)
* [React Ep. 37: Draftjs by What I Learned Today – Atomic Jolt](https://www.youtube.com/watch?v=0k9suXgCtTA)
* [008 - Draft.js Plugins @ React30](https://www.youtube.com/watch?v=w-PqnpMizcQ)
* [Draft.js at HubSpot by Ben Briggs](http://product.hubspot.com/blog/tech-talk-at-night-react-meetup)

## Projects on Top of Draft.js

* [Draft WYSIWYG](https://github.com/bkniffler/draft-wysiwyg) - WYSIWYG editor that with drag&drop, resizing & tooltips.
* [Draft.js Editor](https://github.com/AlastairTaft/draft-js-editor/) - A Rich text editor inspired by Medium & Facebook Notes.
* [Draft.js Plugins](https://github.com/draft-js-plugins/draft-js-plugins) - A Plugin architecture on top of Draft.js
  - [Emoji](https://www.draft-js-plugins.com/plugin/emoji) - Slack-like emoji support
  - [Stickers](https://www.draft-js-plugins.com/plugin/sticker) - Facebook-like sticker support
  - [Hashtags](https://www.draft-js-plugins.com/plugin/hashtag) - Twitter-like hashtag support
  - [Linkify](https://www.draft-js-plugins.com/plugin/linkify) - Automatically turn links into anchor-tags.
  - [Mentions](https://www.draft-js-plugins.com/plugin/mention) - Twitter-like mention support
  - [Undo](https://www.draft-js-plugins.com/plugin/undo) - Undo & Redo button.
  - [Counter](https://www.draft-js-plugins.com/plugin/counter) - Character, word & line counting.
  - [Autolist](https://github.com/icelab/draft-js-autolist-plugin) - Automatic unordered/ordered list creation.
  - [Block Breakout](https://github.com/icelab/draft-js-block-breakout-plugin) - Break out of block types as you type.
  - [Markdown Shortcuts](https://github.com/ngs/draft-js-markdown-shortcuts-plugin/) - Markdown syntax shortcuts.
  - [Single Line](https://github.com/icelab/draft-js-single-line-plugin) - Restrict to a single line of input.
  - [RichButtons](https://github.com/jasonphillips/draft-js-richbuttons-plugin) - Add and customize rich formatting buttons.
* [React-RTE](https://github.com/sstur/react-rte/) - A full-featured textarea replacement similar to CKEditor or TinyMCE.
* [Draft.js Gutter](https://github.com/yepnamesjames/draft-js-gutter) - Compliments line number gutter.
* [Draft.js Basic HTML Editor](https://github.com/dburrows/draft-js-basic-html-editor) - Accept html as its input format, and return html to an onChange.
* [Facebook Notes Clone(ish)](https://github.com/andrewcoelho/react-text-editor) - Rich text editor similar to Facebook notes.
* [Megadraft](https://github.com/globocom/megadraft) - Rich text editor.
* [Medium Draft](https://github.com/brijeshb42/medium-draft) - Medium-like rich text editor with a focus on keyboard shortcuts.
* [Draft.js Prism](https://github.com/SamyPesse/draftjs-prism)- Highlight code blocks using Prism.
* [React-Draft-Wyiswyg](https://github.com/jpuri/react-draft-wysiwyg.git) - A WYISWYG editor, with various text editing options and corresponding HTML generation.
* [Draft.js Typeahead](https://github.com/dooly-ai/draft-js-typeahead) - Support for typeahead functionality.

## Common Utilities

* [BackDraft.js](https://github.com/evanc/backdraft-js) - Function to turn a rawContentBlock into a marked-up string.
* [Draft.js Exporter](https://github.com/rkpasia/draft-js-exporter) - Export and format the content from Draft.js.
* [Draft.js: Export ContentState to HTML](https://github.com/sstur/draft-js-export-html) - Export ContentState to HTML.
* [Redraft](https://github.com/lokiuz/redraft) - Renders the result of Draft.js convertToRaw using provided callbacks, works well with React
* [Draft.js exporter (Ruby)](https://github.com/ignitionworks/draftjs_exporter) - Export Draft.js content state into HTML.
* [Draft.js exporter (Python)](https://github.com/springload/draftjs_exporter) - Library to convert Draft.js raw ContentState to HTML
* [Draft.js AST Exporter](https://github.com/icelab/draft-js-ast-exporter) - Export content into an abstract syntax tree (AST).
* [Draft.js AST Importer](https://github.com/icelab/draft-js-ast-importer)- Emport an abstract syntax tree (AST) output from the companion draft-js-ast-exporter.
* [Draft.js Multidecorators](https://github.com/SamyPesse/draftjs-multidecorators) - Combine multiple decorators.
* [Draft.js SimpleDecorator](https://github.com/Soreine/draft-js-simpledecorator) - Easily create flexible decorators.
* [DraftJS Utils](https://github.com/jpuri/draftjs-utils.git) - Set of utility functions for DraftJS.
* [DraftJs to HTML](https://github.com/jpuri/draftjs-to-html.git) - Library for generating HTML for DraftJS editor content.

## Blog Posts & Articles

* [Facebook open sources rich text editor framework Draft.js](https://code.facebook.com/posts/1684092755205505/facebook-open-sources-rich-text-editor-framework-draft-js/)
* [This Blog Post Was Written Using Draft.js](https://dev.to/ben/this-blog-post-was-written-using-draftjs)
* [How Draft.js Represents Rich Text Data](https://medium.com/@rajaraodv/how-draft-js-represents-rich-text-data-eeabb5f25cf2#.7gd8psdvi)
* [A Beginner’s Guide to Draft.js](https://medium.com/@adrianli/a-beginner-s-guide-to-draft-js-d1823f58d8cc#.uufeulpl5)
* [Implementing todo list in Draft.js](http://bitwiser.in/2016/08/31/implementing-todo-list-in-draft-js.html)
* [Draft.js Pieces](https://cannibalcoder.com/2016/12/02/draft-js-pieces/)

## Live Demos

* [REACTing Codepen Comment Editor - Draft.js](http://codepen.io/rkpasia/full/jqbrpq)
* [Draft.js Examples - A Heroku app w/ several example Draft.js Editors from different projects](http://draftjs-examples.herokuapp.com/)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Nikolaus Graf](https://github.com/nikgraf/) has waived all copyright and related or neighboring rights to this work.
