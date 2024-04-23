# Hands-On Introduction: Data Engineering
This is the repository for learning Hands-On introduction to Data Engineering using Airflow.

![Hands-On Introduction: Data Engineering][lil-thumbnail-url] 

Today’s world is flooded with data, which puts businesses up to task. In response, organizations, companies, and employees around the world have adopted data-driven decision-making techniques. However, the vast majority of new data practitioners haven’t been formally trained. They don’t know how to build and construct stable data pipelines that can function effectively at speed and scale. Moreover, they haven't been given the framework(s) to distill data-oriented tasks into discrete components.

In this course, instructor Vinoo Ganesh gives you an overview of the fundamental skills you need to know to solve complex data problems in a scalable, productive way. Explore the core principles of the data engineer toolkit—including ELT, OLTP/OLAP, orchestration, DAGs, and more—as well as how to set up a local Apache Airflow deployment and full-scale data engineering ETL pipeline. Along the way, Vinoo helps you boost your technical skill set using real-world, hands-on scenarios.


chmod 777 install_airflow.sh
./install_airflow.sh
airflow db init
airflow users create 
airflow users create --username admin --password password --email irudayambics@gmail.com --firstname Irudaya --lastname Raj --role Admin