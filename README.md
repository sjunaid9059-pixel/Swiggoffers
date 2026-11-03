# SJ Cash Mini App (FLAT)

Owner: @sjnd88

## Render — important

**Python version must be 3.11 or 3.12** (not 3.14).

Use `runtime.txt` → `python-3.11.9`

### Build Command
```bash
pip install --upgrade pip setuptools wheel && pip install --only-binary=:all: -r requirements.txt || pip install -r requirements.txt
```

### Start Command
```bash
python main.py
```

### Env
- WEBAPP_URL=https://YOUR.onrender.com
- BOT_TOKEN=9230441788:AAEGUm94Mb4J7bn_kj7kJW6BJpEtErRHz2Q
- ADMIN_IDS=5427735251
- CARGO_HOME=/tmp/cargo
- RUSTUP_HOME=/tmp/rustup

If build still tries Rust: Settings → Environment → add Python version **3.11** manually.
