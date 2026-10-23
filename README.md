# Hekate – İşveren / İş Arayan Platformu (Django)

## Kurulum (Windows, VS Code terminali)
```
python -m venv venv
venv\Scripts\activate          # Mac/Linux: source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py seed          # demo verisi
python manage.py runserver
```
Tarayıcı: http://127.0.0.1:8000

Demo hesaplar (şifre: Demo12345!): işveren `otel_hr`, adaylar `aday1`, `aday2`
