setup:
	python -m venv ~/.msds434

install:
	pip install -r requirements.txt


test:
	python -m pytest -vv --cov=hello tests/*.py
	#PYTHONPATH=. && py.test --nbval-lax notebooks/*.ipynb


lint:
	pylint disable=R.C hello


