# 練習その1

この配布物には、 `users` というディレクトリがあります。

```bash
$ tree users
users
├── __init__.py
└── sample.py
```

1. 各自この中にある `sample.py` ファイルを**自身のユーザー名**のスクリプトファイルにコピーして下さい(リネームではない)。
2. コピーしたファイルを開き、その中の下線部部分を書き換えてください。
3. その状態をコミットし(メッセージは適当でOK)、プッシュしてください。

たとえばユーザー名`densuke`の場合、ファイル名 `densuke.py` とコピーします。

```bash
$ tree users
users
├── __init__.py
├── densuke.py
└── sample.py
```

そして `users/densuke.py` の下線部を書き換えます。

```file:users/densuke.py
def hello():
    # 下線部の所は自分のユーザー名に書き換えてください
    print('Hello from __________ !') # ←ここを書き換え
```

```file:users/densuke.py
def hello():
    # 下線部の所は自分のユーザー名に書き換えてください
    print('Hello from densuke!')
```

保存後、適当な名目でコミットし、プッシュをしてみましょう。

1. 何が起きましたか?(手際の良さと運がからみます)
2. プッシュさせるにはどうしたら?

