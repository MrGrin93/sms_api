# sms_api

1.Migrations
  1.To init:

<p>check  project/migrations/env.py (import models)<br>
alembic revision --autogenerate -m "init"<br>
alembic upgrade head</p>

  2.To upgrade:

<p>Change model, or add<br>
alembic revision --autogenerate -m "comment"<br>
alembic upgrade head</p>
