## 2.9.4 (2021-12-02)

Fix psycopg2 connection.cursor() stub (#6470)

Adds `scrollable=` argument missing since psycopg2 2.5 and prevents `Any` from being hinted when `cursor_factory=` is passed.

## 2.9.3 (2021-11-30)

psycopg2: use Error and Warning from _psycopg.pyi in errors.pyi (#6454)

## 2.9.2 (2021-11-23)

Move abstract methods to AbstractConnectionPool (#6340)

## 2.9.1 (2021-10-12)

Add star to all non-0.1 versions (#6146)

