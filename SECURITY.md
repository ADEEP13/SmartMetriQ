# Deployment security

Set `SMARTMETRIQ_SECRET_KEY` to a persistent, high-entropy value before deployment. Set `SMARTMETRIQ_SECURE_COOKIES=1` when serving over HTTPS.

The included `admin/admin123` and `consumer/consumer123` credentials are demo-only and must not be exposed on a public deployment.

Runtime database files, uploaded evidence, and generated reports are excluded from version control. Install the pinned dependencies with `python -m pip install -r requirements.txt` before running the app.
