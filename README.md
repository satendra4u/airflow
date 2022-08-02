# Airflow
The Airflow pipeline for ETL activities has greatly been used and it is gaining more tractions ever. In the below example I am demonstrating the Airflow caoabilities to simply do the API calling of open weather and does the data manupulation with an ease.

<H2>Requirements for Airflow 2.3.3 with docker: </H2>
<li>Python: 3.7, 3.8, 3.9, 3.10</li>
<li>PostgreSQL: 10, 11, 12, 13, 14</li>
<li>MySQL: 5.7, 8</li>
<li>SQLite: 3.15.0+</li>
<li>MSSQL(Experimental): 2017, 2019</li>
<li>Kubernetes: 1.20.2, 1.21.1, 1.22.0, 1.23.0, 1.24.0</li>

Some of the importnant code which makes the program eligible for DAG is as follows:

</br>from airflow import DAG
</br>from airflow.operators.dummy_operator import DummyOperator
</br>from airflow.operators.python_operator import PythonOperator





