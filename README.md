# FIFA 18 FUT Players Data

## What is the purpose of this script?
- The purpose of this repository is to have a script that autoamtically pulls down all players data from Futhead's website

## How to use it?
- Just run the fifa18.py script:

  `
python fifa18.py
  `
## Players data ouput format:
- After running the script the user will have the data saved in a MySQL database and a CSV file

# Requirements:
- Python 3.xx
- MySQL
- PIP

### You will need to use PIP to install the following libraries:
- pymysql
- bs4
- requests

#### Note:
- Make sure you create table fifa18 using the DDL in fifa.sql to be able to correctly encode latin literals when writing to the Database