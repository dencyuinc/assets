# DENCYU Inc. Company Assets

DENCYU Inc. 本体のブランドアセットを管理するディレクトリです。

## Navigation

| Path | 内容 |
| --- | --- |
| [`logo/`](logo/) | フルロゴ（ロゴマーク + テキスト） |
| [`icon/`](icon/) | アイコン（ロゴマークのみ） |
| [`../services/`](../services/) | サービス別ブランドアセット |

## Brand Colors

DENCYU Inc. のブランドアイデンティティを維持するため、以下の公式カラーを使用してください。

- **Primary**: `#373a3d` - メインカラー、主要なデザイン要素に使用
- **Secondary**: `#c8c5c2` - セカンダリカラー、アクセントや補助的な要素に使用
- **White-like**: `#f3f2f3` - ライト背景や境界線に使用

## Directory Structure

```text
company/
  logo/
    svg/
    svg-transparent/
    png/
    png-transparent/
    jpg/
  icon/
    svg/
    svg-transparent/
    png/
    png-transparent/
    jpg/
```

## Logo

`logo/` はフルロゴ（ロゴマーク + テキスト）のファイルです。

各形式には以下のバリエーションがあります。

- `DENCYU-logo-dark-horizontal`: ダーク背景用・横型
- `DENCYU-logo-dark-vertical`: ダーク背景用・縦型
- `DENCYU-logo-light-horizontal`: ライト背景用・横型
- `DENCYU-logo-light-vertical`: ライト背景用・縦型
- `DENCYU-logo-white-horizontal`: 白背景用・横型
- `DENCYU-logo-white-vertical`: 白背景用・縦型

## Icon

`icon/` はアイコン（ロゴマークのみ）のファイルです。

各形式には以下のバリエーションがあります。

- `DENCYU-icon-dark`: ダーク背景用
- `DENCYU-icon-light`: ライト背景用
- `DENCYU-icon-white`: 白背景用

## Naming Rules

ファイル名の背景指定と表示色の対応は以下です。

- `*-dark-*`: ダーク背景用。ロゴまたはアイコンはライトカラーで表示
- `*-light-*`: ライト背景用。ロゴまたはアイコンはダークカラーで表示
- `*-white-*`: 白背景用。ロゴまたはアイコンはダークカラーで表示
- `*-horizontal`: 横型レイアウト
- `*-vertical`: 縦型レイアウト

## Usage Guidelines

1. **最小サイズ**: ロゴは最小推奨サイズ（SVG版では64px、PNG版では128px）以上で表示してください。
2. **クリアスペース**: ロゴの周囲には、ロゴの高さの20%以上の余白を確保してください。
3. **背景の選択**: 背景色に合わせて `dark`, `light`, `white` の適切なバージョンを使用してください。
4. **アスペクト比の維持**: ロゴやアイコンの縦横比を変更しないでください。
5. **色の変更禁止**: 提供されたカラーバリエーション以外の色に変更しないでください。

## Quality Guidelines

- 可能な限りSVG形式を使用してください。
- ウェブ用途ではSVG、印刷用途では高解像度PNGを推奨します。
- SVGが使えない環境では、用途に合ったサイズのPNGを使用してください。

## License

これらのアセットは DENCYU Inc. の知的財産であり、著作権により保護されています。
