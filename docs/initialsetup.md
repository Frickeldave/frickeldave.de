# Hugo

hugo installieren

```powershell
winget install Hugo.Hugo.Extended
```

Neue site bauen

```powershell
hugo new site frickeldave
```

Installiere das Cleanwhite theme

```powershell
git submodule add https://github.com/zhaohuabing/hugo-theme-cleanwhite.git themes/cleanwhite
```

Neue Seite anlegen

```powershell
hugo new post/firstpage.md
```

# jekyll
sudo apt-get install -y ruby-full build-essential zlib1g-dev git
gem install jekyll bundler

echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc

gem install jekyll bundler
