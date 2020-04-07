# Visual Studio for Mac のアンインストール

このガイドを使用すると、関連するセクションに移動することで、Visual Studio for Mac の各コンポーネントのすべてをアンインストールすることができます。

## Use
アンインストール スクリプトを使うと、Visual Studio と Xamarin コンポーネントを一度にアンインストールできます。
このアンインストール スクリプトには、この記事で説明されているほとんどのコマンドが含まれます。 
外部依存関係の可能性のためにスクリプトからは次の 3 つが除外されています。 




1. このブロジェクトをご利用の Mac 上にファイルを保存します。
1. ターミナルを開き、スクリプトをダウンロードした場所に作業ディレクトリを変更します。  
1. スクリプトを実行可能にして、sudo で実行します。  
1. 最後に、アンインストール スクリプトを削除し、ドックから Visual Studio for Mac を削除します (ある場合)。


```bash:Terminal Command
cd /location/of/file
chmod +x ./uninstall-vsmac.sh  
sudo ./uninstall-vsmac.sh
```
