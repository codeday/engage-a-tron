# Engage-A-Tron
A bot to track engagement of students on the CodeDay discord server


### A few notes
1. For the dockerfile, please remember to use the psycopg2-binary package instead of just psycopg2 in requirements.txt, as this avoids a failure when compiling from source.]
2. The env var `API_SECRET` is needed if you want the API to require a secret, to use provide a url arg called `secret` with the secret. If no env var is provided, then do not provide the `secret` argument.
3. The nomad file assumes there is a postgres server running, and that it has been brought up to the alembic head. Ping me on something if you need some help. 
