# 韓国語フラッシュカード PWA

## GitHubでの公開手順

### 1. GitHubにリポジトリを作成
1. https://github.com にアクセス
2. 右上の「+」→「New repository」
3. リポジトリ名: `korean-flashcard`（なんでもOK）
4. Public を選択
5. 「Create repository」をクリック

### 2. ファイルをアップロード
1. 作成したリポジトリのページで「uploading an existing file」をクリック
2. このフォルダの3ファイルをドラッグ＆ドロップ
   - index.html
   - manifest.json
   - sw.js
3. 「Commit changes」をクリック

### 3. GitHub Pagesを有効化
1. リポジトリの「Settings」タブ
2. 左メニューの「Pages」
3. Source を「Deploy from a branch」に設定
4. Branch を「main」、フォルダを「/ (root)」に設定
5. 「Save」をクリック

### 4. URLが発行される（1〜2分待つ）
`https://あなたのユーザー名.github.io/korean-flashcard/`

### 5. iPhoneでホーム画面に追加
1. Safariでそのアドレスを開く
2. 画面下の「共有」ボタン（四角から矢印が出てるアイコン）
3. 「ホーム画面に追加」→「追加」

これでアプリとして使えます！

## アイコンについて
manifest.jsonにアイコン設定がありますが、icon-192.png / icon-512.pngがなくても動作します。
アイコンを設定したい場合は、PNG画像を用意してリポジトリに追加してください。
