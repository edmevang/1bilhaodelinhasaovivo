# 1bilhaodelinhasaovivo

16 de julho

# Comandos no terminal
poetry init
pyenv local 3.12.4
poetry env use 3.12.4
poetry shell
clear

python create_measurements.py
python etl.py

git add .
git commit - m 'segue meu código'
git push

poetry shell
poetry add pandas

python etl_pandas.py
poetry run python etl_pandas.py

poetry add tqdm

poetry add duckdb

poetry run python etl_duckdb.py

poetry add streamlit

streamlit run dashboard/meu_dashboard_errado.py

poetry run python using_duckdb_to_save_parquet.py