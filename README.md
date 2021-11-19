# 🎉First_Step_to_git

git勉強会用レポジトリです

わからないことはぜひ聞いてみてください、私も一緒に考えます(((完璧に答えられるとは言ってない)))

# 💥Caution  git勉強会に伴うお願い💥

## __参加者の皆様はご自身の開発環境に合わせて以下の内容を事前に実行してください。__

gitが開発環境上にすでに存在する、又は使ったことのある方はそのままで結構です。

確認方法は[自環境にgitがあるかを確認する方法](#自環境にgitがあるかを確認する方法)を確認してください

# 🔥事前実行必須事項🔥
## __1. githubのアカウントの作成をお願いします__
Sign Upからメールアドレスとパスワードの設定をお願いします。

URL => https://github.com/

## __2. 開発環境へのgitの導入について__

### __2.1. 🪟 Windowsの方へ__

以下に記載されているgitの初期設定まで事前に実行をお願いします。

https://prog-8.com/docs/git-env-win

### __2.2. 🍎🐧Mac, Wsl, Ubuntu(Linuxディストリビューション)をお使いの方へ__

ターミナルを開くことのできる方は以降の手順に従ってください

1. __パッケージ管理ツールHomebrewをインストールします__

	[Homebrew 公式ページ](https://brew.sh/index_ja)

	ターミナル上で以下のコマンドを実行してください。

	(```brew -v```でバージョンが表示される方は飛ばして大丈夫です。)
	```sh
	bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
	```

2. __Homebrewを使ってgitをインストールします__

	ターミナル上で以下のコマンドを実行してください。

	(```git --version```でバージョンが表示される方は飛ばして大丈夫です。)
	```sh
	brew install git
	```
3. 補足事項

	ここまでやってもgitが追加されていない場合は、パスが通っていない(インストールしたgitの場所が環境変数に追加されていない)可能性があります。

	その場合はお手数ですが私までお問い合わせください。

### __3. ◁vscodeのインストールをお願いします__

vscode(Visual Studio Code)とはMicrosoftが開発しているWindows、Linux、macOS用の無料のソースコードエディタです。

一番最初の導入操作として使いやすいと考え今回はvscodeによるgit操作を扱います。

[vscode 公式](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)

## __3.1. 🪟 Windowsの方へ__

1. Windowsをお使いの方は以下のURLに記載された内容を最後まで実行してください。

	[WindowsにVisual Studio Codeをインストールする](https://qiita.com/suke_masa/items/91fddf0728a290b72fc4)

## __3.2. 🍎🐧Mac, Wsl, Ubuntu(Linuxディストリビューション)をお使いの方へ__

1. Macの方は以下のURLに記載された番号7までを実行してください。

	URL : [MacOSでVisual Studio Codeをインストールする手順](https://qiita.com/watamura/items/51c70fbb848e5f956fd6
)

2. Linuxディストリビューションの方は以下のページを実行してください。

	(Arch Linux等ご使用の方はお手数ですがご自身でvscodeの導入方法をお調べいただけますと幸いです。そのうえで不具合が生じた場合はお尋ねください。)

	URL : [Ubuntu20.04 VScodeをインストールする](https://mebee.info/2020/03/18/post-7546/)


不明点、ターミナルを開くことができない等ありましたらお気軽にお問い合わせください。

# 🔍自環境にgitがあるかを確認する方法

1. Windowsの方へ

	スタートメニューから```git bash```と検索してください。

	以下のようにヒットがあれば自環境にgitが存在しているとみなして構いません。
	![git bash](https://user-images.githubusercontent.com/58177127/142365075-f870a8b2-1630-4bb0-b7ca-a9af31bc86e4.jpg)

2. Wsl, Ubuntu(Linuxディストリビューション)をお使いの方へ

	ターミナルを開き、以下のコマンドを実行してください
	```sh
	git --version
	```

	この時
	```sh
	git version "任意のバージョン"
	```
	となっていればお使いの環境にgitが存在します。

	表示されない場合でも環境変数にgitが追加されていないだけで正常にインストールされている場合があります、「あれ？」と思った場合はお気軽にお尋ねください。

# 🔎自環境にvscodeがあるかを確認する方法

アプリケーションの検索欄からvscodeと入力した際に表示があればインストール済みです。
