# HTML5

![image](https://github.com/seungheondev/HTML5-CSS3/assets/170543088/be63cd49-f9b7-44ea-8fdd-1407b47580b7)

1.Tag : \<h1>\</h1><br><br>

2.Element : \<h1>Hello World\</h1> 全体を意味する。<br><br>

3.\<h1>\</h1> 見出し要素

・h1タグは最上位の見出し、複数のh1タグを使うことはよくない。<br>

・異なるレベルの見出しを飛び越えないように。<br><br>

4.\<p>\</p> 段落要素<br><br>

5.\<hr>, \<br> void要素<br>

・タグの中に内容を入れることが禁止されている。<br>

・段落要素を別に作る代わりに、改行タグを使うことはよくない。<br><br>


6.\<ul>\</ul>, \<li>\</li>, \<ol>\</ol> リスト要素<br><br>

7.\<a>\</a> アンカー要素<br><br>

8.\<img src="" alt="" /> 画像要素<br><br>

9.File Path
    
・絶対ファイルパス：コンピュータのルートから持ってくる。

・相対パス：フォルダを移動しても常に有効<br><br>

10.\<!DOCTYPE html> : どのバージョンのHTMLで書かれたかをブラウザに知らせる。<br><br>

11.\<div>\</div> コンテンツ分割要素
   
・CSSを適用するしない限り完全に不可視。<br><br>


# CSS3
1.CSS追加方法

・Inline : \<tag style="css" />, HTMLページ上の１つの要素だけにCSSを追加する時に使う。→ 非効率的

・Internal : \<style>css</style>, 他の要素にもCSSが適用される。

・External : \<link href="style.css" />, WEB開発に一般的に使われているもの。<br><br>

2.CSSセレクター

・クラスセレクター：指定したクラスにCSSを適用する。(グループ化)<br>
![image](https://github.com/seungheondev/HTML5-CSS3/assets/170543088/0cddbb37-f14c-47f0-bea9-ad3deeb28e85)

・属性セレクター：特定の属性や特定の属性値を持った要素にCSSを適用する。<br>
![image](https://github.com/seungheondev/HTML5-CSS3/assets/170543088/1759f8dd-2628-423e-9c02-8023195da0d4)<br><br>

3.CSSプロパティ

・カラープロパティ<br>
![image](https://github.com/seungheondev/HTML5-CSS3/assets/170543088/93544fbf-d5b5-496f-a131-b26b8ff5f4e5)

・テキストプロパティ<br>
![image](https://github.com/seungheondev/HTML5-CSS3/assets/170543088/62f3260b-1e0a-441b-a3ee-b7b39176e7eb)

1px : 1/96th inch(0.26mm)

1pt : 1/72nd inch(0.35mm)

1em : 100% of parent(親タグのサイズ)

1rem : 100% of root(ルートからの相対的なサイズ)

・ボックスモデル

padding : 要素とborderの間にスペースを追加する。

margin : borderの外側にスペースを追加する。<br><br>

4.CSSカスケード

Position < Specificity < Type < Importance

・位置(Position)：blueが適用される。

![image](https://github.com/seungheondev/HTML5-CSS3/assets/170543088/a2886f7c-1035-4c3b-b4e9-7923b4941c2d)


・特異性(Specificity)：最後のidで指定したCSSが適用される。

![image](https://github.com/seungheondev/HTML5-CSS3/assets/170543088/b8da4cf3-f8ee-4908-a79f-2841a88cda1c)


・タイプ(Type)：inlineが最優先される。

![image](https://github.com/seungheondev/HTML5-CSS3/assets/170543088/bafb03f7-975a-4874-b487-88c94f5b32f2)


・重要度(Importance)：greenが適用される。

![image](https://github.com/seungheondev/HTML5-CSS3/assets/170543088/8d6d2a3f-da58-4858-a441-148640e2e1f2)


5.CSSセレクタの組み合わせ

・グループルール

![image](https://github.com/seungheondev/HTML5-CSS3/assets/170543088/a5d496fa-d65f-4964-a9ea-49a943c2ce07)

・子セレクタ

![image](https://github.com/seungheondev/HTML5-CSS3/assets/170543088/cb5d6a99-df97-448c-a65b-cc0ef7f3ed3d)

・子孫セレクタ

![image](https://github.com/seungheondev/HTML5-CSS3/assets/170543088/fc9b80a4-ed1a-48a3-a143-272896020ec8)

・連鎖セレクタ

![image](https://github.com/seungheondev/HTML5-CSS3/assets/170543088/66fc1142-77a4-4069-9cd3-0e1ec24675f5)







