```
curl https://raw.githubusercontent.com/gogotanaka/dotfiles/master/.gitconfig > ~/.gitconfig

curl https://raw.githubusercontent.com/gogotanaka/dotfiles/master/.zshrc.shared > ~/.zshrc.shared
```

```
echo 'source ~/.zshrc.shared' >> ~/.zshrc
touch ~/.zshrc.config
echo 'source ~/.zshrc.config' >> ~/.zshrc
```
