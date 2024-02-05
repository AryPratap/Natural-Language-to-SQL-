


<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h1 align="center"> Natural Language to SQL</h1>

  <p align="center">
  </p>
</p>



<!-- ABOUT THE PROJECT -->
## About The Project

This project deals with the implementation of Natural Language question to SQL query parser on QFabric dataset using Large Language Models. 

### Code structure
```
└───  README.md
└───  requirements.txt
└─── notebooks
    └─── NL_to_SQL_final.ipynb (Final Submission file)
    └─── geojson_to_sql.ipynb
    └─── zero_shot_vs_few_shot_NL_to_SQL.ipynb


```
### Installation
- Clone the github repo
```
git clone https://github.com/AryPratap/Natural-Language-to-SQL-.git
```
- Install requirements
```
pip install -r requirements.txt
```
### Dataset 
The NL to SQL parser is implemented over QFabric dataset. <br>
QFabric is an open-source change detection dataset with 450,000 change polygons annotated across 504 locations in 100 different cities covering a wide range of geographies and urban fabrics. QFabric is a temporal multi-task dataset with 6 change types and 9 change status classes.
<br>
- The original QFabric dataset is converted from geojson format to SQLite database format. The code for the same is present in <b><u>geojson_to_sql.ipynb</u></b>
- Database file size if large. Can be download through this [link](https://drive.google.com/file/d/1SL8EWz6_0T4Nz2vSnsP29TQ6uXKWjHQ2/view?usp=sharing)

 ### Notebooks 
 - <b><u>NL_to_SQL_final.ipynb</u></b> : The final assignment submission file. Contains the end to end NL to SQL parser.
 - <b><u>geojson_to_sql.ipynb</u></b> : This file contains the code for converting geojson dataset file to SQLite database file. It also presents a primary analysis of the QFabric dataset.
 - <b><u> zero_shot_vs_few_shot_NL_to_SQL.ipynb</u></b> : This file contains a comparative analysis of zero shot and few shot prompting for generation SQL queries from Natural language. 



