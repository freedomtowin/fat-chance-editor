<h1 align="center">
  <a href="https://pola.rs">
    <img src="https://raw.githubusercontent.com/freedomtowin/fat-chance-editor/master/readme_assets/fat_chance.ico" alt="Fat Chance Icon">
  </a>
</h1>

<div align="center">
<h1 style="font-family: 'Monaco, Inter, sans-serif'; font-size: 36px;">Fat Chance Editor</h1>
</div>


Fat Chance Editor is designed for fast context switching, processing content with AI queries. The file tree, editor, terminal are tightly integrated, allowing the terminal to access the data in the editor and file tree.

The editor uses a "cloud-style" strategy to process content with the built-in command line tool. The command line tool allows users to read, write, and apply transformations in the following formats:

1) Markdown content
2) Directory of Markdown files or REGEX split content (as a list)
3) Cached AI queries or REGEX split content in JSON format
4) A directory of Cached transformation (as a list)

Commands can be piped into other commands like in the Terminal, allowing for complex pipelines to be plainly represented and executed.

For comfort, the editor has fully reactive navigation with the directional arrow keys, reducing the number of mouse clicks and interruptions to flow states. 

A light green selection overlay shows which view is selected. Entering and escaping a view is intuitive with the Enter and Escape keyboard keys. 
 
The element views have been paired-down with unused views being hidden to improve overall focus.Shortcuts to file paths enable fast context switching. 
