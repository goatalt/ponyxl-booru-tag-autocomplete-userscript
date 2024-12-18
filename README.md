This is a userscript for Violentmonkey/Tampermonkey that will autocomplete Booru tags when writing prompts for PonyXL. Tags are those that have over 100 results from danbooru.

How to:  
1. Install Violentmonkey: https://violentmonkey.github.io/
2. Add the script: https://raw.githubusercontent.com/goatalt/ponyxl-booru-tag-autocomplete-userscript/refs/heads/main/main.js
3. Type booru tags in html <textarea>'s for autocompletion

You can download the main.js file and edit the `@match *://*/*` to whatever address/sit you use it on, otherwise it'll be active on all sites which is unneeded.  
I wrote it for use with SwarmUI, works there and in ComfyUI nodes with a textarea.
