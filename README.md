# Arabic-Music-AI-Core

Arabic Music AI monorepository. This repository is being implemented with:

- `backend/`: FastAPI local AI API
- `frontend/`: React PWA
- `android/`: Kotlin Jetpack Compose application
- `database/`: SQLite migrations
- `audio-engine/`: real audio analysis and WAV export utilities
- `ai/`: model adapters and hardware validation
- `scripts/`: installation and verification tools
- `tests/`: backend, audio, integration, and Android checks
- `.github/workflows/`: reproducible build and APK validation

## Important status

No AI music model is bundled. Generation remains explicitly `MODEL_NOT_AVAILABLE` until a licensed model and verified weights are installed.

See `BUILD.md` and `docs/FEATURE_AUDIT.md` after implementation.
