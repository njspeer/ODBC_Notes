# ODBC_Notes

Based on this how-to guide https://apporbit.com/how-to-install-oracle-odbc-driver/


1 go to https://www.oracle.com/database/technologies/instant-client.html
  and download the Oracle SDK package for your system, as well as the ODBC package

2 put both zip files in C:\oracle and unzip

3 add folder to PATH (i.e. C:\oracle\instantclient_xx_x)

3 run "C:\oracle\instantclient_21_3\odbc_uninstall.exe" as admin
  (it won't produce a window or give you any feedback)

4 run the application 'ODBC Data Sources' and 
  add ODBC driver 'MySQL ODBC 8.0 Unicode Driver'

5 use 'MySQL ODBC 8.0 Unicode Driver' for driver name and description