# これは何ですか？

ライフゲームを初めて書いたものです。  
また、typescriptで作ったほぼ初めてのまともなアプリケーションです。  
特に参考にしたコードはなく、外部サイトからのコピペ部分はありません。  

typescriptについては以下ページを参考にしました。
https://qiita.com/uhyo/items/e2fdef2d3236b9bfe74a


## 目的

ライフゲームを自力実装してみたかったこと、tsに慣れることが目的です。  
フレームワークは何でもよかったのですが、最近書いていてしっくり来るReactにしました。  


## 感想
  
とりあえず動くとこまで書きました。  
コンポーネント設計や読みやすさは要リファクタ。  
関数型を意識したせいか、型付けはさほど苦労しませんでした。が、いくつか無駄っぽいところもあります。  
tsを導入したのが途中からのため、より型を意識して書くには最初から導入するといいと思います。  
隣接判定に苦戦して何度か書き直しました。今もだいぶ力技で、 `./src/utils/boardHelpers.ts` につらみが詰まっています。  
コンポーネント設計がっつり意識した、hooksやReduxバージョンもそのうち作ろうかな。  