# BeThirtyMax Ortho — ZMK firmware

BeThirty Ortho の無線版。acdb ボード(nRF52840)、単4電池 2 本直列、40 キー
(格子 4 行 × 10 列の 39 キー + 一番上の小さいキー)。Keeb-On! Studio で設定する。

- `boards/shields/bethirtymax_ortho/` — マトリクス、物理レイアウト、設定
- `config/bethirtymax_ortho.keymap` — 初期キーマップ
- `build.yaml` — GitHub Actions で焼くファイル: `bethirtymax_ortho.uf2`、`settings_reset.uf2`

タグを push するとビルドされ、`.uf2` が GitHub Release に載る。
