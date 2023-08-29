# Twitter Mock - Study

## Version
- Java 17.0.6
- Gradle 7.6.1
- Frameworks
    - Vue 
    - Spring Framework boot 3.1.3

## 環境構築手順
- Git https://git-scm.com/download/win
    - 設定はとりあえず全部Nextでいい
    - インストール後、プロジェクトをclone。
- Java11(JDK 17.0.*) https://www.oracle.com/java/technologies/downloads/#java17
    - 17.0.6 (JDK 17.0.*)をZipダウンロード
    - 解凍して`jdk-17.0.*`を`C:\Program Files\Java`に移動
    - システム環境変数を設定`C:\Program Files\Java\jdk-17.0.*\bin`し1番上に持ってくる
- Gradle（gradle-8.2.1）
    - https://gradle.org/install/
    - gradle-8.2.1をbinary-onlyでインストール
    - 手順`Installing manually`に沿ってインストール
- Intellij
    - https://www.jetbrains.com/ja-jp/idea/download/?section=windows
    - 下のCommunity Editionをインストール
    - Gitの手順でcloneしたプロジェクト配下のmockモジュールをIntellijで開く
    - File > Project structureで使用するJava 17を選択
    - Settingsからbuild toolにGradle8.2.1を選択

## 



