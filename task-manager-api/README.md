# Task Manager API

    # Demo App

    Quickstart:
    ```bash
    pip install -r requirements.txt
    python manage.py migrate
    python manage.py runserver
    ```


## 🚀 Deploy to Render
1. Push this repo to GitHub.
2. On Render, click **New → Blueprint** and select this repo.
3. Render will detect `render.yaml` and provision:
   - A **PostgreSQL database** (DATABASE_URL injected automatically)
   - A **Web Service** running `gunicorn project.wsgi`
4. Set `DJANGO_SECRET_KEY` (auto-generated) and ensure `DEBUG=False`.
5. Deploy. Your app will be available at a public URL.
