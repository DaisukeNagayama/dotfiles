" dotfiles リポジトリの作成手順

" dotfiles 
mkdir dotfiles && cd dotfiles



" シンボリックリンクを設定する
ln -s ~/dotfiles/vimrc/_vimrc ~/.vimrc
ln -s ~/dotfiles/vimrc/_gvimrc ~/.gvimrc