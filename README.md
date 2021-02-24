# dotfiles
Various useful files that belong in a home folder and should be synced across multiple computers.

Note that the `.aliases-*` scripts should be included in your `.bashrc` with the `.` command; for example, `. .aliases-git`.

You can clone this repository directly into your home folder, or clone it somewhere else and create symlinks to the files in this repository that you want to use. The downside of cloning it to your home folder is that everything underneath your home folder becomes part of this git repository. The files will be ignored due to the gitignore, but text editors and other programs will still detect the repository.