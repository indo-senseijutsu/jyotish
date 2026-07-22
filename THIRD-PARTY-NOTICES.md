# サードパーティ・ライセンス表記

本アプリの配布ファイル（`index.html`）は、ビルド時に以下のオープンソースソフトウェアを含んだ形で生成されています。
最小化処理によりファイル内のライセンスコメントが削除されているため、その著作権表示をここに記載します。

---

## React / React DOM / Scheduler

Copyright (c) Meta Platforms, Inc. and affiliates.

Licensed under the MIT License.

```
MIT License

Copyright (c) Meta Platforms, Inc. and affiliates.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## Vite

ビルド成果物の先頭に、Vite が生成する `modulepreload` ポリフィルのコードが含まれています。

Copyright (c) 2019-present, Yuxi (Evan) You and Vite contributors

Licensed under the MIT License.

```
MIT License

Copyright (c) 2019-present, Yuxi (Evan) You and Vite contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 同梱していない外部リソース

以下は配布ファイルには含まれておらず、実行時にブラウザが外部から読み込みます。再配布にあたるものではありませんが、参考として記載します。

- **Noto Sans JP**（Google Fonts 経由で読み込み）
  SIL Open Font License 1.1 のもとで提供されています。
  https://fonts.google.com/noto/specimen/Noto+Sans+JP

---

## 計算方式の出典

以下は本アプリの天文計算の参考文献です。数式・アルゴリズムそのものはソフトウェアの同梱ではありませんが、出典として明記します。

- Paul Schlyter, *Computing planetary positions — a tutorial with worked examples*
  惑星位置の算出（ケプラー軌道要素＋主要摂動項）に使用。
- Jean Meeus, *Astronomical Algorithms*, 2nd edition, Chapter 47 "Position of the Moon"
  月の高精度計算（周期項60項）の係数および算法の出典。
