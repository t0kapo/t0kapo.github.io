+++
title = "GitHub PagesとHugo(テーマはBlowfish)でサイト作った"
date = 2025-08-30T16:20:00+09:00
showDateUpdated = true
+++

# GitHub Pagesでサイト公開したのでメモ
夏季休暇中に久しぶりに色々技術的なの触ってて(GeminiやChatGPTにほぼ頼ってたけど)、その延長でGitHub Pages・ActionsとHugo触ってサイト公開しました。今後はてなは使わないと思う(大学時の鬱日記残ってるので...)  
後で思い出せるようにちょっとメモ  

## 使ってるもの  
- GitHub Pages  
とりあえず管理が楽&簡単に公開できるので選定。  
- Hugo&Blowfish  
HugoはGeminiに良い静的サイトジェネレータ教えて〜って聞いて出てきた一つ。他にGatsbyなどを提案された。テーマのBlowfishはでもデモサイトなどを見てこれ良い！！ってなって選定。  
- GitHub Actions
ビルド・デプロイ用。使うの4・5年ぶりぐらい。

## 参考文献
ほぼ自力でやってない気がする。たまーにChatGPTに相談した。
https://blowfish.page/ja/  
https://qiita.com/yuubinnkyoku_mk/items/60fb608bc006a1c19f81  
https://zenn.dev/jolly96k/articles/f8d0e5eb247bf0  
https://zenn.dev/tamanegi/articles/5a44fbcda0f7c5  

## 色々
参考文献が足りてない気がするので後で追記。hugo.tomlやparam.tomlはもうちょっと弄って調整したい。  あと、公開日の自動出力ができなくて(0001/01/01みたいになる)、MarkDownに直接指定しているので、いつか解決したい。
