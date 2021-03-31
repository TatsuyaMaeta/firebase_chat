GitHub へアップロードしてはいけない API キー等がある場合に
ファイルを別ディレクトリに切り分けておいくことで、
何度も削除して上げ直し等をしなくてもいい

env_firebase_chatについては別のディレクトリにて
同じ様な開発案件があった場合に分かりやすくする為

<ディレクトリ構成>
.
│  
├── env
│   └── env_firebase_chat
│       └── env.js
└── firebase_chat
    ├── css
    │   ├── reset.css
    │   └── style.css
    ├── images
    ├── index.html
    ├── js
    │   └── app.js
    └── readme.md
