# ストア素材（DO & DON'T）

- `play-icon-512.png` — Play 用アイコン（512×512）
- `feature-graphic/feature-<locale>.png` — フィーチャーグラフィック（1024×500・言語別）
- `screenshots/<locale>/<n>-<name>.png` — スクリーンショット（1080×1920・6枚 × 8言語）
  1-do / 2-dont / 3-records / 4-insights / 5-dark / 6-settings

Play Console の言語コード: ja-JP / en-US / ko-KR / es-419 (es-ES 同文) / de-DE / zh-TW / pt-BR / fr-FR
生成スクリプトはアプリリポの `scripts/store-screenshots/`（Web版を headless Chrome で撮影 → 合成）。
