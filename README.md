# dotfiles
Various useful files that belong in a home folder and should be synced across multiple computers.

Note that the `.aliases-*` scripts should be included in your `.bashrc` with the `.` command; for example, `. .aliases-git`. They are separated so that you can include only the relevant files.

You can clone this repository directly into your home folder, or clone it somewhere else and create symlinks to the files you want to use. The downside of cloning it to your home folder is that everything underneath your home folder becomes part of this git repository. The actual files will be ignored, but text editors and other programs will still detect the presence of a repository. Thus can cause unexpected behavior with certain features, like autocompletion of filenames.
