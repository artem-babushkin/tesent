## SQLite schema ##

CREATE TABLE webusers ( id INTEGER PRIMARY KEY AUTOINCREMENT,
	email TEXT NOT NULL,
	passhash TEXT NOT NULL
);
