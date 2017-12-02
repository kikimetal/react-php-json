# [React SPA] Node で SSR せずにSEO的に最低限は対応したい

よくあるレン鯖でも問題なく SPA を設置したい。

OGP などもページごとに適切に配置したい。

ビルド時に、babel-polyfill を食わせればとりあえずグーグルサーチコンソールで OK そうな雰囲気になる。(googleのクローラーが若干古いっぽいため)

**-> だから、html 全て SSR しなくても、問題なさそう。**
