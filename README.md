dotfiles
========

Use [GNU Stow](http://www.gnu.org/software/stow/) to symlink the config for each
application to their corresponding folder. For instance, `stow vim`.

GTK Theme:

- GTK2: [Greybird](https://github.com/shimmerproject/Greybird)
- GTK3: [Minwaita](https://github.com/godlyranchdressing/Minwaita)

*P.S.* do NOT stow `other`, as it's not meant to be copied/symlinked in the home
folder. Some should be copied to a location in root, or just be run to perform
setup. I should revisit the structure of `other` some time to make it consistent
with the rest of repo.
