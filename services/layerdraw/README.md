# LayerDraw Assets

LayerDraw のブランドアセットを管理するディレクトリです。

## Navigation

| Path | 内容 |
| --- | --- |
| [`../../`](../../) | リポジトリ全体のREADME |
| [`../`](../) | サービスアセット共通README |
| [`logo/`](logo/) | LayerDraw ロゴ |
| [`icon/`](icon/) | LayerDraw アイコン |
| [Brand Kit（layerdraw リポジトリ）](https://github.com/dencyuinc/layerdraw/tree/main/brand) | ブランド正本（ガイドライン、SVG、tokens.json） |

## Directory Structure

```text
services/layerdraw/
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

## Naming Rules

LayerDraw アセットのファイル名は以下の形式です。

```text
LayerDraw-logo-{variant}-horizontal.{ext}
LayerDraw-icon.{ext}
```

- `variant`: `light`, `dark`
- `ext`: `svg`, `png`, `jpg`

アイコンは単一バリアント（紫グラデーション地に白マーク、明暗どちらの背景でも使える）のため、variant サフィックスを持ちません。縦型（vertical）ロゴは存在しないため作成しません。

> **注意**: SVG の正本は [layerdraw リポジトリの `brand/`](https://github.com/dencyuinc/layerdraw/tree/main/brand) です。`svg-transparent/` は正本をそのまま取り込んだもの、`svg/` はそれに背景を追加したものです。修正が必要な場合は正本側を更新してから取り込み直してください。

## Size Rules

- 横ロゴ（`horizontal`）は `1880 x 400 px` に統一しています。
- アイコンは `1500 x 1500 px` です。
- SVGの横ロゴは `width=1931`, `height=505`（viewBox `1448.25 x 378.75`）です。
- SVGのアイコンは `width=2000`, `height=2000`（viewBox `1500 x 1500`）です。

## Assets

### logo/svg-transparent/

- `LayerDraw-logo-light-horizontal.svg` - width 1931, height 505
- `LayerDraw-logo-dark-horizontal.svg` - width 1931, height 505

### logo/svg/

- `LayerDraw-logo-light-horizontal.svg` - width 1931, height 505（背景色: `#FFFFFF`）
- `LayerDraw-logo-dark-horizontal.svg` - width 1931, height 505（背景色: `#373A3D`）

### logo/png-transparent/

- `LayerDraw-logo-light-horizontal.png` - 1880 x 400 px
- `LayerDraw-logo-dark-horizontal.png` - 1880 x 400 px

### logo/png/

- `LayerDraw-logo-light-horizontal.png` - 1880 x 400 px（背景色: `#FFFFFF`）
- `LayerDraw-logo-dark-horizontal.png` - 1880 x 400 px（背景色: `#373A3D`）

### logo/jpg/

- `LayerDraw-logo-light-horizontal.jpg` - 1880 x 400 px（背景色: `#FFFFFF`）
- `LayerDraw-logo-dark-horizontal.jpg` - 1880 x 400 px（背景色: `#373A3D`）

### icon/svg-transparent/

- `LayerDraw-icon.svg` - width 2000, height 2000

### icon/svg/

- `LayerDraw-icon.svg` - width 2000, height 2000（背景色: `#FFFFFF`）

### icon/png-transparent/

- `LayerDraw-icon.png` - 1500 x 1500 px

### icon/png/

- `LayerDraw-icon.png` - 1500 x 1500 px（背景色: `#FFFFFF`）

### icon/jpg/

- `LayerDraw-icon.jpg` - 1500 x 1500 px（背景色: `#FFFFFF`）

## License

LayerDraw は source available なプロダクトです。LayerDraw アセットの利用条件と名称・商標の扱いは、このリポジトリ共通の Usage Policy ではなく、layerdraw リポジトリ側の定義に従ってください。

- [Trademark Policy](https://github.com/dencyuinc/layerdraw/blob/main/docs/legal/trademarks.md) - 名称・商標の利用条件
- [LICENSE](https://github.com/dencyuinc/layerdraw/blob/main/LICENSE) - プロダクト本体のライセンス
