# 土木学会論文集 LaTeX テンプレート
土木学会のページ[各種書式](http://committees.jsce.or.jp/jjsce/pform)より，LaTeXテンプレートを展開，Linux(Ubuntu)で動作するように修正しました．  
pLaTeX 2e 用のディレクトリのみ抽出し，編集しています．

## 使い方
動作確認環境は，Ubuntu 16.04 LTS および 18.04 LTSです．  
以下のコマンドを実行すると，PDFが作成されます．
```shell
make ronbun # ronbun-j.pdf
make man    # jsce-man.pdf
make bib    # bibtex-j.pdf
make soufu  # soufuhyo2e.pdf
```
また `make all` および `make`は， `make ronbun`と同じです．

## 注意点
「2018年7月18日改訂」版を編集し作成されています．今後書式が更新される可能性があります．  
環境によって，元のPDFファイルと異なった書式になる可能性があります．  
元のPDFファイルを確認したい場合は， 最初のコミット時点のファイルを参照してください．  
最初のコミットは，土木学会がアップロードしているzipファイルを展開したものと同じです．  

## ライセンス等
各`*.sty` `*.cls`ファイルの著作権は，ファイル内に記述されている通りです．  
オリジナルのパッケージについては土木学会が権利を所有しています．  
個人利用は自由です．ただし，本リポジトリを使用したことによる損害（リジェクト，査読評価等）について，本リポジトリ作成者は何ら責任を負わないものとします．

## 作成者
宮下 卓也 (Takuya Miyashita)  
miyashita (at) hydrocoast.jp
