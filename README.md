# Magical Reading

GitHub Pages で公開する静的ビルドです（ver. 1.2.0）。開発の正本は Muse 上のアーティファクトで、この repo にはビルド済みの静的ファイル（index.html と assets）を置きます。

- データの保存先は Supabase（Marks Tools プロジェクト／magical_reading スキーマ）で、アプリが使うのは anon キーのみです
- スラッシュ付け・チャンク訳・全文訳は、利用者自身の外部AI（Gemini／ChatGPT／Claude 等）が担当し、アプリは共通形式（[CHUNKS] 英文 | 訳 ＋ [FULL] 全文訳）で結果を受け取ります
