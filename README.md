# ms-data-parser 仕様書

公開ページ: https://yuukamegai.github.io/ms-data-parser-spec/

MS-DIAL の出力を LLM から解析する MCP サーバ **ms-data-parser**（[systemsomicslab/Metabolomix_with_LLM](https://github.com/systemsomicslab/Metabolomix_with_LLM)）の仕様書です。
全 53 ツールの入出力、2 つの入口（GUI で解析済みのフォルダと、生データから MS-DIAL Console を回す pipeline）、統計エンジン（前処理・QC、PCA、moderated t による群間比較と changed / unchanged / inconclusive の判定）、定量（内部標準の正規化・極性の統合・特徴の選別）、同定と MS/MS 照合、アラインメントのキュレーション、図、パスウェイ投影（MSLipidMapper）、MCP リソース、エクスポート形式（差次的エクスポート v1・根拠バンドル v3）をまとめています。

- `index.html` は 1 ファイルで完結します（フォントのみ Google Fonts から読み込み）。
- 図中の「例示」と付いた数値・化合物名は説明用の架空の値です。
- 基準: Metabolomix_with_LLM `main@4a4eee3`（2026-11-09。2026-11 の構成見直しの後）。
