newtype
=======

There are two scripts I made for adding new filetypes to vim, `newtype` and `removetype`

`newtype file-extension filetype` creates an appropriate file of file-extension.vim in ~/.vim/ftdetect to detect \*.file-extension files as filetype. It then opens your default editor to ~/.vim/ftplugin/filetype/file-extension.vim. It will ask for confirmation if you're overwriting the file in ~/.vim/ftdetect.

`removetype file-extension filetype` undoes what newtype does. It will always ask for confirmation.

To install in your ~/.vim/ftplugin directory, run `./install`
