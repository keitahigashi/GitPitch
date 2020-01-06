### スライドタイトル
　  

　  
　  
　　　　　keita higashi
---
こんな感じのスライドが作れます。
---
１ページ目
---
２ページ目
---
画像を表示  
<img src="assets/sample.png">
---
### Fragment Slides
- １行ごとの表示単位でアニメーション|
- 要素の先頭を「\-」で記述 |
- 末尾に「\|」を記述 |
- １行ごとの表示単位でアニメーション|
---
### Code Presenting
コードブロックのハイライト
```perl
use feature qw(say switch);
given ($foo) {
    when (1)          { say "\$foo == 1" }
    when ([2,3])      { say "\$foo == 2 || \$foo == 3" }
    when (/^a[bc]d$/) { say "\$foo eq 'abd' || \$foo eq 'acd'" }
    when ($_ > 100)   { say "\$foo > 100" }
    default           { say "None of the above" }
}
```
@[1](ハイライト行の解説)
@[2-8](コメントは[]の右に記述します。)
---
### Gist

---?gist=arinyan/f90dec730feee8e9129b
---
### URL 
　  
https://gitpitch.com/<ユーザ名>/<リポジトリ名>  

---
ブランチでもOK 

https://gitpitch.com/<ユーザ名>/<リポジトリ名>/<ブランチ名>  
