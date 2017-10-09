# asciidoctorによる文書ファイル作成

asciidoc形式のテキストファイルから公開用の各種ファイルを作成するにはasciidoctorを使う。  

## インストール

 > bundle install --path vender/bundler


## html出力
 > bundle exec asciidoctor plantuml_practice.adoc

## pdf出力
 > bundle exec asciidoctor-pdf plantuml_practice.adoc
