# Service Assets

サービスごとのブランドアセットを管理するディレクトリです。

## Navigation

| Path | 内容 |
| --- | --- |
| [`../`](../) | リポジトリ全体のREADME |
| [`databuddy/`](databuddy/) | Databuddy のブランドアセット |
| [`databuddy/README.md`](databuddy/README.md) | Databuddy アセットのファイル一覧とサイズ |
| [`layerdraw/`](layerdraw/) | LayerDraw のブランドアセット |
| [`layerdraw/README.md`](layerdraw/README.md) | LayerDraw アセットのファイル一覧とサイズ |

## Directory Structure

```text
services/
  service-name/
    README.md
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

## Service List

- [`databuddy/`](databuddy/): Databuddy のブランドアセット
- [`layerdraw/`](layerdraw/): LayerDraw のブランドアセット

## Placement Rules

新しいサービスアセットを追加する場合は、サービス名ごとにディレクトリを作成してください。

各サービス配下には、そのサービス固有の `README.md` を置き、以下を記載してください。

- アセットの種類
- ファイル形式
- サイズ
- 命名ルール
- サービス固有の注意事項

## Naming Rules

サービスアセットのファイル名は、以下の形式を推奨します。

```text
ServiceName-logo-{variant}-{layout}.{ext}
ServiceName-icon-{variant}.{ext}
```

- `variant`: `light`, `dark`, `white` など
- `layout`: `horizontal`, `vertical` など
- `ext`: `svg`, `png`, `jpg` など

## Format Policy

- `svg/`: 標準SVG
- `svg-transparent/`: 透過SVG
- `png/`: 標準PNG
- `png-transparent/`: 透過PNG
- `jpg/`: JPG

必要な形式だけを追加してください。空ディレクトリを残す必要がある場合のみ `.gitkeep` を置いてください。
