Generative Design コードパッケージ ([p5.js](https://p5js.org/)用)
=================================================================
ようこそ！　このGitHubリポジトリには、書籍『[Generative Design](http://www.generative-gestaltung.de) with [p5.js](https://p5js.org/) 』用のすべてのソースコードが含まれています。始めるには「[セットアップ](#セットアップ)」と「[スケッチを実行する](#スケッチを実行する)」を参照してください。それではお楽しみください！

***


**編著者**

- [Benedikt Groß](http://benedikt-gross.de/)
- [Hartmut Bohnacker](https://www.hartmut-bohnacker.de)
- [Julia Laub](http://www.onformative.com/)
- [Claudius Lazzeroni](http://www.lazzeroni.de/)

**協力**

- [Joey Lee](http://jk-lee.com/)
- [Niels Poldervaart](http://nielspoldervaart.nl/)


セットアップ
------------
1. [Node.js](https://nodejs.org/ja/)をインストールします（最新の安定板を選択してください）
2. ターミナルを開き、コンピュータに保存した `Code-Package-p5.js` フォルダに移動します：

  ```
  $ cd path/to/folder
  # e.g. cd /Users/GG/Documents/Code-Package-p5.js
  ```

3. 以下を実行します：

  ```
  $ npm install
  ```


スケッチを実行する
------------------
1. 以下のコマンドで、ローカルのウェブサーバ<sup>1</sup>（livereload機能付き）を起動します。このコマンドは `index.html` （すべてのスケッチの一覧）をブラウザの新しいウィンドウで開きます。

  ```
  $ npm start
  ```

2. 一覧表示されたスケッチへのリンク🔗をクリックして、スケッチと触れ合います。
3. 触れ合い、作り、保存し、そしてあなたの成果をシェアしてください！🌈`#GenerativeGestaltung #generativedesign #p5js`


<sup>1</sup>一部のスケッチはオンラインでの動作が前提になっています。これは、例えば外部のファイルの読み込みなど、一般的に「セキュリティ」上の懸念がある機能を利用しているためです。ウェブサーバを起動せずにローカルで閲覧する場合は、「cross-origin」のエラーが出てしまいます😭（ブラウザのコンソールを確認してみてください）。この問題を解決するには、これらのファイルを「[ローカルウェブサーバ](https://github.com/processing/p5.js/wiki/Local-server)」と呼ばれるもので配信します。これが前述の `npm start` で実行される内容です。


ライセンス
----------
書籍内のすべてのソースコードは、[Apache License Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)でライセンスされます。
