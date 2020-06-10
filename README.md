## Mermaid

Mermaid is great!  Unfortunately the live editor only exports to SVG.
Confluence sucks!  It doesn't support SVG.
Let's use "mermaid.cli" to create PNGs.
We can still use the live editor to create views and embed them into confluence via iframe, if we want hyperlinks.
The live editor can still be used for easy editing.

## Copy to my own repo

* `git clone --depth 1 https://github.com/msde/mermaid-png;cp mermaid-png/.gitignore .;cp mermaid-png/* .;rm -rf mermaid-png`

## Installing

* npm install 

## Converting a mermaid spec to a png

For spec "login.txt" run the following:
  * `npm run png example.txt`
  * `open example.txt.png`

## Appendix

* https://knsv.github.io/mermaid/
* http://knsv.github.io/mermaid/live_editor/
* https://github.com/mermaidjs/mermaid.cli

