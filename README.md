# sms_api


To init:

check  project/migrations/env.py (import models)
alembic revision --autogenerate -m "init"
alembic upgrade head

Tu upgrade:
Change model, or add
alembic revision --autogenerate -m "comment"
alembic upgrade head
