lint:
	flake8 .

test:
	pytest

format:
	black .

fix-lint:
	black . && flake8 .

all: format lint test