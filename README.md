# Poetry issue

Run `poetry install; poetry run ./pytest.sh`

## Expected

Poetry should run pytest.sh as if in a shell, and should print "This is ./pytest.sh"

## Actual

Poetry simply runs the python module `pytest`

## Notes

Before running `poetry install`, things might work as expected
