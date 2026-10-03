# AI Solar EV Charging Station — Vercel Edition

Static Vercel-ready presentation website for the LSTM-driven EV charging project.

## Deploy
1. Upload this folder to a GitHub repository.
2. Import the repository in Vercel.
3. Framework Preset: Other.
4. Build Command: leave empty.
5. Output Directory: `.`
6. Deploy.

The site uses a bundled dataset replay at `data/replay.json`, so it works without Flask.

Important: the charging animation and EMS values are presentation/simulation values. They are not live charger telemetry. The bundled replay uses project PV data; the forecast series is a lightweight presentation proxy and should not be reported as a newly trained LSTM result. Use the validated project metrics (R² 0.9271, MAE 1.171 kW, RMSE 2.221 kW) in reports.
