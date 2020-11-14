# JNF
Josh's Note Format

I made my own note taking format because it helped me to read my notes better.

Example:
	![Image of gnome terminal with note taking format shown](https://github.com/drgnomage/JNF/blob/main/Screenshot%20from%202020-11-13%2023-59-13.png)

Deploy:
	mkdir ~/.nano
	curl https://raw.githubusercontent.com/drgnomage/JNF/main/notes.nanorc -o .nano/notes.nanorc
	Add the following to your nanorc file:
		include "~/.nano/*.nanorc"
