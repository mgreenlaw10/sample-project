# Cartograph coordination branch

This branch holds **collaboration metadata only** — tasks, module reservations,
agent session history and integration requests. It deliberately contains no
project source code, and it is an orphan branch, so it shares no history with
your code branches.

Cartograph reads and writes these files without ever checking this branch out,
so it cannot disturb your working tree.

Do not edit these files by hand while the application is running: it merges
them by value and will overwrite a hand edit it did not expect. Nothing here is
secret, but nothing here is authenticated either — Git author names are
attribution, not identity. Repository access is controlled by your Git host.
