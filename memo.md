## タグ
- 詩: 創作、詩
- 作詞: 創作、作詞
- 考察: エッセイ、考察、感想

- 創作
  - 詩
  - 作詞
- エッセイ
  - 考察
  - 感想


## 記事追加方法
```
hugo new posts/2026/title.md
```


## RSSから除外
_build: -> list:local を使う。
現在は、プライバシーポリシーを除外している。

```
date: "2026-06-15T22:30:00+09:00"
draft: false
title: "プライバシーポリシー"
_build:
  list: local
```

## Bing Webmaster認証
- static/BingSiteAuth.xml


## Google Search Console認証
- static/googledcf140d3749d5a2c.html
