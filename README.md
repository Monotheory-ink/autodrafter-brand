<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="logo-with-wordmark/autodrafter-logo-wordmark-white.svg">
    <img src="logo-with-wordmark/autodrafter-logo-wordmark.svg" alt="AutoDrafter" width="360">
  </picture>
</p>

# AutoDrafter Brand Assets

AutoDrafter のロゴ素材（SVG）です。正三角形を 1 : ½ : ¼ の比率で組み合わせたマーク（外形・切り欠き・核）を基本形としています。

## ファイル

| 用途 | ファイル | プレビュー |
|---|---|---|
| ロゴ（マーク） | [`logo/autodrafter-logo.svg`](logo/autodrafter-logo.svg) | <img src="logo/autodrafter-logo.svg" height="40"> |
| ロゴ（マーク・白） | [`logo/autodrafter-logo-white.svg`](logo/autodrafter-logo-white.svg) | 濃色背景用 |
| ロゴ＆ワードマーク | [`logo-with-wordmark/autodrafter-logo-wordmark.svg`](logo-with-wordmark/autodrafter-logo-wordmark.svg) | <img src="logo-with-wordmark/autodrafter-logo-wordmark.svg" height="32"> |
| ロゴ＆ワードマーク（白） | [`logo-with-wordmark/autodrafter-logo-wordmark-white.svg`](logo-with-wordmark/autodrafter-logo-wordmark-white.svg) | 濃色背景用 |
| アプリアイコン（512×512） | [`icon/autodrafter-icon.svg`](icon/autodrafter-icon.svg) | <img src="icon/autodrafter-icon.svg" height="48"> |
| ファビコン | [`icon/favicon.svg`](icon/favicon.svg) | ライト／ダークモードで自動的に色が切り替わります |

## カラー

| 名前 | HEX | 用途 |
|---|---|---|
| Ink | `#0E1525` | 基本色（白・明るい背景の上） |
| White | `#FFFFFF` | 濃色背景の上 |

## 使い方のルール

- **余白**：ロゴの周囲には、マークの高さの 1/4 以上の余白を空けてください。
- **最小サイズ**：マークは高さ 24px 以上で使用してください。それより小さい場合は、脚と核を太らせた `icon/favicon.svg` を使用してください。ロゴ＆ワードマークは幅 120px 以上で使用してください。
- **変形しない**：縦横比の変更、回転、影やグラデーションの追加はしないでください。

### ファビコンの設定例

```html
<link rel="icon" href="/favicon.svg" type="image/svg+xml">
```

## ワードマークの書体

ワードマークは [Outfit](https://github.com/Outfitio/Outfit-Fonts)（SIL Open Font License 1.1）の Regular（Auto）と Bold（Drafter）を、字間 -0.02em で組み、アウトライン化しています。フォントがインストールされていない環境でも同じ形で表示されます。

## ライセンス

ロイヤリティフリーです。個人・商用を問わず、無償で使用・改変・再配布できます。クレジット表記は不要です。ただし、AutoDrafter からの推奨や提携を示唆する使い方はできません。詳しくは [LICENSE](LICENSE) を参照してください。
