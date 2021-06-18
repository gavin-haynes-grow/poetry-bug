# Poetry issue

Run `poetry install; poetry run ./pytest.sh`

## Expected

Poetry should run pytest.sh as if in a shell, and should print "This is ./pytest.sh"

## Actual

Poetry simply runs the python module `pytest`

## Notes

Before running `poetry install`, things might work as expected

If you run `poetry run ./test.sh`, then you can see it run the actual script.

You can also run `poetry run ./python.sh` even though there is no such file, and it
will run python.
