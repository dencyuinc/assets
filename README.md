# DENCYU Inc. Assets

DENCYU Inc. と各サービスのブランドアセットを管理するリポジトリです。

## Navigation

| Path | 内容 |
| --- | --- |
| [`company/`](company/) | DENCYU Inc. 本体のブランドアセット |
| [`company/README.md`](company/README.md) | 会社アセットの構成、命名規則、利用ガイドライン |
| [`services/`](services/) | サービスごとのブランドアセット |
| [`services/README.md`](services/README.md) | サービスアセット共通の配置ルール |
| [`services/databuddy/`](services/databuddy/) | Databuddy のブランドアセット |
| [`services/databuddy/README.md`](services/databuddy/README.md) | Databuddy アセットのファイル一覧とサイズ |

## Directory Structure

```text
company/
  README.md
  logo/
  icon/
services/
  README.md
  databuddy/
    README.md
    logo/
    icon/
```

## Asset Groups

`company/` には DENCYU Inc. 本体のロゴ、アイコン、ブランドカラー、利用ガイドラインを置きます。

`services/` にはサービス単位のブランドアセットを置きます。サービス固有のファイル一覧や補足ルールは、各サービス配下の `README.md` に記載します。

## Format Policy

基本構成は以下の形式別ディレクトリです。

- `svg/`: 標準SVG
- `svg-transparent/`: 透過SVG
- `png/`: 標準PNG
- `png-transparent/`: 透過PNG
- `jpg/`: JPG

必要な形式だけを追加できます。ベクターで扱える用途では SVG を優先してください。

## License

このリポジトリ内のアセットは、DENCYU Inc. または各サービスの知的財産です。利用時は、該当する配下READMEのガイドラインと利用条件に従ってください。

## Contact

ブランドアセットの利用に関する質問や承認が必要な場合は、以下まで連絡してください。

- info@dencyu.co.jp
