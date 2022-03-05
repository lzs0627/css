# css
css関する情報纏め

## リセットCSS

#### 参考：

https://web-camp.io/magazine/archives/30817#:~:text=%E3%83%AA%E3%82%BB%E3%83%83%E3%83%88CSS%E3%81%A8%E3%81%AF%E3%80%81%E3%83%96%E3%83%A9%E3%82%A6%E3%82%B6,CSS%E3%82%92%E6%8C%81%E3%81%A3%E3%81%A6%E3%81%84%E3%81%BE%E3%81%99%E3%80%82

#### 代表的なリセットCSS

* [Eric Meyer’s “Reset CSS” 2.0](https://meyerweb.com/eric/tools/css/reset/)
* [HTML5 Doctor CSS Reset](http://html5doctor.com/html-5-reset-stylesheet/)
* [Yahoo! (YUI 3) Reset CSS](https://yuilibrary.com/yui/docs/cssreset/)
* Universal Selector ‘*’ Reset
* [Normalize.css](https://github.com/necolas/normalize.css/blob/master/normalize.css)
* [ress](https://github.com/filipelinhares/ress)
* [sanitize.css](https://csstools.github.io/sanitize.css/)


## ::before、::afterを使いこなせる

#### 参考：

https://www.asobou.co.jp/blog/web/before-after

#### POINT

* beforeは指定した要素内にあるコンテンツの直前に、afterは指定した要素内にあるコンテンツの直後に配置
** <div>::before コンテンツ::after</div>
* 要素内にコンテンツが存在しないタグにはbeforeとafterは配置することができません
* z-indexを指定していない状態だと、beforeとafterは要素の上に配置されます


## min-width、max-widthを使いこなせる

#### 参考：

https://saruwakakun.com/html-css/basic/max-min-width

## メディアクエリーの意味を理解して使いこなせる

#### 参考：

https://wemo.tech/839

#### POINT

- HTMLでCSSファイルを読み込むlinkタグにmedia属性を記述する
> ＜link rel="stylesheet" href="./css/mobile.css" media="screen and (max-width: 600px)"＞
- CSS内で@importする
> @import url('mobile.css') screen and (max-width: 600px);
- CSS内で@mediaを記述

> @media screen and (max-width: 600px) {
> 
>   div{ width: 100%; }
>   
> }


## vw、vhの単位を使いこなせる
## line-height、letter-spacingを使いこなせる
## overflow:hidden、overflow-x、overflow-yを使いこなせる
## word-breakの使い方がわかる
## padding-topを用いて縦横比を維持して拡大・縮小する要素をつくれる（最近はaspect-ratioのプロパティもあります）
## flexレイアウトを用いた要素の上下左右中央揃えができる
## positionとtransformを用いた要素の上下左右中央揃えができる
## emのrem単位を理解している
## margin: 0 auto;を使いこなせる
## transition、animationを使ったことがある
## transformを一通り理解している
## :hover、:active、:focusの意味がわかる
## フクロウセレクタ（* + *）の意味がわかる
## :not(:first-child)の意味がわかる
## :not(:nth-of-type(3n-2))の意味がわかる
## flex-direction: column;やflex-wrap: wrap;を日頃から使っている
## flex: none;、flex: auto;などの使い方がわかる
## Sass(SCSS)、Less、Stylusのいずれかの使い方がわかる
## クラスの命名規則（BEMなど）について理解がある
## CSS設計について調べたことがある（OOCSS、SMACSS、ECSSなど）
## 印刷用CSSを書いたことがある
## calc()を使ったことがある
## counter-reset、counter-increment、counter()を知っている
## CSSのminifyをしたことがある
## 文章の縦書きをCSSで設定できる
## cursorプロパティを使える
## pointer-events、visiblity、opacity、display: none;の挙動の違いがわかる
## rgba（）を使っている
## CSSで三角形が作れる
## background-size、background-repeat、background-imageがわかる
## linear-gradient、radial-gradientがわかる
## https://caniuse.com/を知っている
## flexレイアウト内のmarginの挙動が理解できている
## position: relative;とposition:absolute;とposition: fixed;の違いがわかっている
## CSSにData URIで画像を埋め込んだことがある
## box-sizingの挙動を理解している
## list-style: none;を使ったことがある
## font-familyの設定の仕方がわかる
（英字と日本語フォントを分けて指定する、句読点や括弧を文字づめするなど）
## Gridレイアウト、gapを使える
## Purge CSSを知っている
## stylelint、またはCSS combを知っている
## border-radius: 9999pxの使い方がわかる
## ウェブフォント（Google Fonts、Adobe Fontsを使ったことがある）
## Tailwind CSS、Bootstrapを使ったことがある
## Fontawesomeでアイコンを使用したことがある（Bootstrap Iconsなどでもよい）
## SVGを操作するfillプロパティやclip-pathを知っている
## filterプロパティを知っている
