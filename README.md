# lammps
Vim syntax highlighting for LAMMPS files, taken from the LAMMPS distribution and made into a package.

These files can be found in the `tools/vim` directory of the LAMMPS source code.

To install using a package manager such as Vundle, place the following in your `~/.vimrc`:

```vim
Plugin 'tommason14/lammps.vim'
```

Then run `:PluginInstall` and `:so $MYVIMRC` to install and activate the plugin.

If you use the [tcomment](https://github.com/tomtom/tcomment_vim) package, also add the following line to your `~/.vimrc`:
```vim
let g:tcomment_types={'lammps': '# %s'}
```
