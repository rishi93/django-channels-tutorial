# Django channels tutorial

## Built with:
- Django
- Django channels
- Redis queue
- Javascript WebSocket

## Steps to run example:
- Run Redis queue
```bash
docker run -p 6379:6379 redis
```
- Run Django channels app
```bash
pip install -r requirements.txt
python manage.py runserver
```
