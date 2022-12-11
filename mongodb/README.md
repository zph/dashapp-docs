# MongoDB 3.4 Docs

```
brew install dashing
cd ~/Downloads
wget https://docs.mongodb.com/v3.4/manual.tar.gz
tar -xvf ~/Downloads/manual.tar.gz
cd ~/Downloads/manual-v3.4.tar/
mv html mongodb-v3.4
cd mongodb-v3.4/
dashing create
# Edit settings
vim dashing.json
dashing build mongodb-v3.4
open .
# Doubleclick on the docset folder to load into Dash
```
