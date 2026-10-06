# AGENTS.md

- 所有回應一律使用繁體中文。
- 專案語言為 Python；使用 conda 管理套件，環境名稱為 `iem_python`（例：`conda activate iem_python`、`conda install <pkg>`）。不要改用 `pip`、`poetry`、`uv` 或另建 venv。
- Repo 狀態：課程 115-1 computer programming 的 codebase，目前僅追蹤 `README.md` + Python `.gitignore`，尚無 source、manifests、tests 或 CI。
- 尚無 build / test / lint / typecheck 指令；執行前先確認新增的設定，不要預設有 `pytest` 等工具。
- `.gitignore` 為 Python 標準模板（忽略 `__pycache__/`、`*.py[cod]`、`.venv/`、`venv/`、`.env`、`.pytest_cache/` 等），課程練習檔、venv 保持不追蹤。
- 新增第一份正式程式碼時，一併補上最小執行方式與單檔 / 單一測試的跑法。
