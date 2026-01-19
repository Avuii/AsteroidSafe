# AsteroidSafe
Web dashboard that ingests NASA NeoWs / JPL SBDB data and classifies Near-Earth Objects as Potentially Hazardous (PHA) using a pretrained tabular foundation model (TabPFN), deployed via ONNX Runtime in .NET.

## Tech stack
- Frontend: React + TypeScript (Vite)
- Backend: ASP.NET Core Web API
- ML: Python (TabPFN + baselines)
- Deployment: ONNX Runtime (.NET)

## Architecture
- `frontend/` — dashboard UI
- `backend/` — REST API + ONNX inference
- `training/` — data ingestion + training + export to ONNX
- `docs/` — documentation and reports

## Roadmap
- M1: Data ingestion (NASA NeoWs / optional JPL SBDB) + caching
- M2: Dataset & feature engineering + PHA label
- M3: TabPFN training + baseline comparison
- M4: Export to ONNX + .NET inference endpoint
- M5: Dashboard UI (list + details + charts)
- M6: Docs + demo + v1.0 release
