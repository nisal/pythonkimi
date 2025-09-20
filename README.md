Single-file style
SQLite schema
371 topics, 12 emotions, 1 topic per call
hard-coded Kimi key (swap the placeholder)
self-restarts after every topic (CLI) or auto-refreshes (Flask) until finished
Save as haiku.py, drop your key in, and:

bash
  pip install requests  # (only external dep)
  python haiku.py

It will keep looping in the terminal until all 4 452 haiku are in haikuclock.sqlite.


Usage
  pip install requests (once)
  python haiku.py

Leave the terminal open – the script re-invokes itself after every topic until the DB is complete.
