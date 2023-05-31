admin@MacBook-Pro-admin ~ % cd Documents
admin@MacBook-Pro-admin Documents % mkdir hexlet && cd hexlet
admin@MacBook-Pro-admin hexlet % npm init -y
Wrote to /Users/admin/Documents/hexlet/package.json:

{
  "name": "hexlet",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC"
}


admin@MacBook-Pro-admin hexlet % nano package.json
admin@MacBook-Pro-admin hexlet % cat package.json
{
  "name": "hexlet",
  "type": "module",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC"
}
admin@MacBook-Pro-admin hexlet % npm install lodash

added 1 package, and audited 2 packages in 974ms

found 0 vulnerabilities
admin@MacBook-Pro-admin hexlet % touch index.js
admin@MacBook-Pro-admin hexlet % tree -L 1
.
├── index.js
├── node_modules
├── package-lock.json
└── package.json

2 directories, 3 files
admin@MacBook-Pro-admin hexlet % git clone git@github.com:kristinafrdx/hexlet_project.git
Клонирование в «hexlet_project»...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Получение объектов: 100% (3/3), готово.
admin@MacBook-Pro-admin hexlet % code
