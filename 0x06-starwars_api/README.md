# 0x06. Star Wars API
![star wars](https://camo.githubusercontent.com/a6b9a7c5ddb35d947dc7807ab90167c931c70920be0ee73493dcac1b88db7306/68747470733a2f2f7777772e746865646174617363686f6f6c2e636f6d2e61752f77702d636f6e74656e742f75706c6f6164732f323032322f30392f3630366534653230396631303763613366623635323834665f53637265656e2d53686f742d323032312d30342d30372d61742d382e32382e30312d504d2e706e67)

### Install Node 10
```
$ curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
$ sudo apt-get install -y nodejs
```
### Install semi-standard
[Documentation](https://github.com/standard/semistandard)
```
$ sudo npm install semistandard --global
```
### Install `request` module and use it
[Documentation](https://github.com/standard/semistandard)
```
$ sudo npm install request --global
$ export NODE_PATH=/usr/lib/node_modules
```
## Tasks
### 0. Star Wars Characters
mandatory

Write a script that prints all characters of a Star Wars movie:

+ The first positional argument passed is the Movie ID - example: `3` = “Return of the Jedi”
+ Display one character name per line **in the same order as the “characters” list in the `/films/` endpoint**
+ You must use the [Star wars API](https://swapi-api.alx-tools.com/)
+ You must use the `request` module
```
alexa@ubuntu:~/0x06$ ./0-starwars_characters.js 3
Luke Skywalker
C-3PO
R2-D2
Darth Vader
Leia Organa
Obi-Wan Kenobi
Chewbacca
Han Solo
Jabba Desilijic Tiure
Wedge Antilles
Yoda
Palpatine
Boba Fett
Lando Calrissian
Ackbar
Mon Mothma
Arvel Crynyd
Wicket Systri Warrick
Nien Nunb
Bib Fortuna
alexa@ubuntu:~/0x06$ 
```
