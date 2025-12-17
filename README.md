# Data Analyst Portfolio

データアナリスト向けのポートフォリオサイトです。

## ファイル構成

```
.
├── index.html      # メインHTMLファイル
├── style.css       # スタイルシート
└── README.md       # このファイル
```

## GitHub Pagesで公開する方法

### ⚠️ 重要: ファイルの準備

現在、`index.html`と`style.css`はディレクトリ内にあります。GitHub Pagesで動作させるには、**ルートディレクトリに直接配置**する必要があります。

以下のファイルをルートディレクトリにコピーしてください：
- `index.html/index.html` → `index.html`（ルートに）
- `style.css/style.css` → `style.css`（ルートに）

または、既に作成されている以下のファイルをリネームしてください：
- `index_for_github.html` → `index.html`にリネーム
- `style_for_github.css` → `style.css`にリネーム

### 1. GitHubリポジトリを作成

1. GitHubにログインして、新しいリポジトリを作成します
2. リポジトリ名は任意（例: `portfolio`、`my-portfolio`など）

### 2. ファイルをアップロード

以下のいずれかの方法でファイルをアップロードします：

#### 方法A: GitHub Webインターフェースから

1. リポジトリページで「Add file」→「Upload files」をクリック
2. **ルートディレクトリにある** `index.html`と`style.css`をドラッグ&ドロップ
   - ⚠️ `index.html/index.html`や`style.css/style.css`ではなく、ルートの`index.html`と`style.css`をアップロード
3. 「Commit changes」をクリック

#### 方法B: Gitコマンドから

```bash
# リポジトリをクローン（作成後、GitHubから表示されるURLを使用）
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

# ファイルをコピー（ルートディレクトリに）
# Windowsの場合:
copy "index.html\index.html" "index.html"
copy "style.css\style.css" "style.css"

# または、既に準備されたファイルをリネーム:
# ren index_for_github.html index.html
# ren style_for_github.css style.css

# コミット&プッシュ
git add index.html style.css
git commit -m "Initial commit: Add portfolio site"
git push origin main
```

### 3. GitHub Pagesを有効化

1. リポジトリの「Settings」タブを開く
2. 左メニューから「Pages」を選択
3. 「Source」で「Deploy from a branch」を選択
4. 「Branch」で「main」（または「master」）を選択
5. 「/ (root)」を選択
6. 「Save」をクリック

### 4. サイトにアクセス

数分待つと、以下のURLでサイトにアクセスできます：

```
https://your-username.github.io/your-repo-name/
```

## カスタマイズ

- **個人情報の更新**: `index.html`内の名前、メールアドレス、SNSリンクを編集
- **プロジェクトの追加**: `index.html`の`#projects`セクションに新しいプロジェクトカードを追加
- **スキルの更新**: `index.html`の`#skills`セクションを編集
- **スタイルの変更**: `style.css`のCSS変数（`:root`セクション）を編集して色を変更

## ライセンス

このプロジェクトは個人のポートフォリオサイトとして自由に使用・改変できます。

