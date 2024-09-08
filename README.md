# Dataview Index

This repository contains a sample to generate a dynamic
[JDex](https://johnnydecimal.com/10-19-concepts/11-core/11.05-the-index/).

Features:

 - Index is generated automatically, based on index notes.
 - The index is "clickable"; you can click a given area/category/ID to navigate
   to the associated index note. You can preview by hovering.
 - Index notes for IDs ("ID notes") will automatically list files in its
   directory. (In Obsidian)
 - ID notes has option to define one or multiple locations, which are listed in
   `00.00 Index`.
 - Templates for index notes (area, category and IDs) are located in
   `00-09 System/05 Templates/05.10 System templates`.

It looks like this, but the formatting is customizable:

https://github.com/user-attachments/assets/c340b31f-dab2-400c-860c-29bac3506286

## Instructions

You can download the repository as an Obsidian vault and use that as a starting
point.

If you want to integrate it into your current system, the instructions are
below.

1. Install plugin Dataview, and optionally Templater.
2. Enable JavaScript for Dataview.
3. Optional: Set `00-09 System/05 Templates/` as the template folder for
   Templater
4. Copy the `00-09 System` folder to your vault.
5. Optional: Customize the formatting of the index by modifying the code in
   [[00.00 Index]].
6. Delete/rename/add files to `00-09 System/00 Index` as appropriate for you.

`00-09 System/00 Index/00.00 Index` contains the file that generates the
  index.


### Plugins

- Dataview
- Templater (optional)

## Known issues

- If a category or area doesn't have any ID notes for it, it will not appear in
  the generated JDex.
- It's not super robust; incorrect spelling or renaming may break it.
