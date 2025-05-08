# Qt support for Vim

Simple Qt support for Qt-based projects. Forked from https://github.com/cpiger/vim-qt.

## Installation

#### vim-plug
```vim
Plug 'jclsn/vim-qt'
```

#### Vundle
```vim
Plugin 'jclsn/vim-qt'
```

#### Pathogen
```vim
git clone https://github.com/jclsn/vim-qt ~/.vim/bundle/vim-qt
```

### Filetypes

* C++
* qmake
* qml
* qbs
* qrc -- xml
* ui -- xml
* ts -- xml

## Status

| Language | File Type Detection | File Type Plugin |       Syntax       |     Indent    | Compiler | Plugin |
| :------- | :-----------------: | :--------------: | :----------------: | :-----------: | :------: | :----: |
|  Qt C++  |  **+** (extend cpp) |                  | **+** (extend cpp) |               |          |        |
|  qmake   |        **+**        |      **+**       |        **+**       |               |          |        |
|   qml    |        **+**        |                  |        **+**       |     **+**     |          |        |
|   qbs    |        **+**        |      **+**       |        **+**       |               |          |        |
|   qrc    |     **+** (xml)     |                  |                    |               |          |        |
|    ui    |     **+** (xml)     |                  |                    |               |          |        |
|    ts    |     **+** (xml)     |                  |                    |               |          |        |


## Commands

* ``:QtAssist`` searches the word under the cursor in [Qt Assistant](https://doc.qt.io/qt-6/assistant-quick-guide.html), if installed. 
The path must be provided as ``let g:vimqt_assistant = '/usr/bin/assistant'``.

## Related works:

* https://github.com/vim-scripts/cpp.vim
* https://github.com/Townk/vim-qt
* https://github.com/kosl90/qt-highlight-vim
* https://github.com/vim-scripts/Qt.vim
* https://github.com/edlanglois/vim-qrc
* https://github.com/vim-scripts/qt2vimsyntax
* https://github.com/pavel-belikov/vim-qtcreator-tasks
* https://github.com/vim-scripts/qmake--syntax.vim
* https://github.com/pavel-belikov/vim-qmake
* https://github.com/artoj/qmake-syntax-vim
* https://github.com/suy/vim-qmake
* https://bitbucket.org/JohnKaul/qbs.vim
* https://github.com/tiamat18/vim-qmake
* https://github.com/listenerri/vim-qt-assistant

## Todo:

* Add supported syntaxes to syntax menu
* QtDoc

## Recommended Vim LSP clients for C++
Vim:
* https://github.com/neoclide/coc.nvim
* https://github.com/ycm-core/YouCompleteMe
* https://github.com/yeggapan/lsp
* https://github.com/prabirshrestha/vim-lsp

Neovim:
* https://neovim.io/doc/user/lsp.html
* https://github.com/neoclide/coc.nvim
