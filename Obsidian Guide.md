---
aliases:
  - Obsidian Tips and Tricks
---
#### Linking

Add a link by wrapping text in double brackets. 
- `[[Link Text Here]]` 
- Ex: [[Obsidian Guide]]



#### Using Templates

Access templates by using the shortcut Alt + \`. This shortcut can be changed in Settings -> Hotkeys -> Search for Template.
This will open a search box where you can enter the name of the template. All templates are stored in the z_Templates folder. 
Anything created in the z_Templates folder can be used as a template.




#### Adding/Resizing Images

Images can be added by copy and pasting. This will create a new image file in Obsidian. Usually store image files in z_Assets folder. 

To use an image that already has a file, use the link command for the file preceded by an !.
- `![[image.jpg]]`
- Ex: ![[testImage.png]]

Images can also be resized by adding a pipe `|` to the end of the link and specifying pixel value.
- `![[image.jpg|100]]`
- ![[testImage.png|100]]



#### Aliases - AKA Renaming Links

If you want to use a different name than the page name for a link, there are two options. For a single instance, you can rename using a pipe separator `|` after the link and adding the new name.
- `[[Obsidian Guide|Helpful Tips]]`
- Ex: [[Obsidian Guide|Helpful Tips]]

For frequently used aliases, you can add as a file property so they show up as a searchable/linkable option automatically.

File properties can be accessed by clicking the three dots in the top right and clicking "Add file property".
![[Pasted image 20251028204714.png]]

You can add a property called "aliases" and then add the different names you want the file to have. Click enter after typing the name to add it to the aliases list. Files can have multiple aliases.
![[Pasted image 20251028204822.png]]
- Try adding link and search for Tips and Tricks! 