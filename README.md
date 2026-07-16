# SQL-Sprint-1
2 week sprint to learn SQL databases


# SQL Workout Log 

A simple SQLite database for tracking workouts — logging exercises, sets, reps, weight, and notes over time, and querying training volume trends

## Instructions for Build and Use

Steps to build and/or run the software:

1. Install SQLite (Windows/Linux: download from [sqlite.org/download.html](https://sqlite.org/download.html))
2.Open a terminal, navigate to your project folder, and run `sqlite3 workouts.db` to create/open the database
3.Paste the contents of `schema.sql` to create the `workouts` table

Instructions for using the software:

1. Insert a new workout with an `INSERT INTO workouts (...)` statement (see `sample_data.sql` for examples)
2. Run `.headers on` and `.mode column` for readable query output
3. Query your data — e.g. `SELECT * FROM workouts;` or use the volume-tracking queries in `queries.sql`

## Development Environment

To recreate the development environment, you need the following software and/or libraries with the specified versions:

* SQLite3 (version 3.0 or later)
* A terminal / command-line shell
* A SQL-friendly text editor, e.g. VS Code with a SQLite extension

## Useful Websites to Learn More

I found these websites useful in developing this software:

* [SQLite Documentation](https://sqlite.org/docs.html)
* [SQLite Online (browser-based SQLite sandbox)](https://sqliteonline.com)
* [DB Fiddle](https://www.db-fiddle.com)

## Future Work

The following items I plan to fix, improve, and/or add to this project in the future:

* [ ] First thing here
* [ ]
* [ ]
