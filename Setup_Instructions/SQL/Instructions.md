## Instructions for SQL setup (server and client) for the lab.
Prepared by **Florian Titze**

- Everybody needs a working SQL server and a client (preferably MySQL Workbench - not SequelPro, because that's buggy) - as explained in the Prework section of your student portal

- Everybody in that client software needs to have imported

  * the **Sakila movie database** for your labs (Run a test query, e.g. ```select * from sakila.actor;``` and make sure it runs successfully and returns rows). If you chose a full install of MySQL workbench, this database is already included. If not, use the ```sakila-schema.sql``` attached first, and run it in MySQL workbench. After that, run the ```sakila-data.sql``` )
  * the **czech bank database** for the lecture (Run a test query, e.g. ```select * from bank.account;``` and make sure it runs successfully and returns rows). Use the ```mysql_dump.sql``` file (in MySQL workbench via Sever -> Data Import -> Import from Dump Project Folder.... select the folder in which the dump file is in, -> Start Import)

After every import of databases, you need to press the tiny refresh button in the SCHEMAS field.

You can find the files in this folder. put it at best into a folder called "databases" with corresponding subfolders fo every db. The Czech bank database dumpfile is big file and you download it via this [link](https://github.com/raafat-hantoush/IH_RH_DA_FT_MAR_2022/blob/main/Class_Materials/SQL_MYSQL/SQL_DATA_Dump_Bank.sql)
