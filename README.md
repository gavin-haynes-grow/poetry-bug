# Poetry issue

Run `poetry install; poetry run ./pytest.sh`

## Expected

Poetry should run pytest.sh as if in a shell

## Actual

Poetry runs `pytest` and the PYTHONPATH is wrong

## Notes

Before running `poetry install`, things might work as expected
