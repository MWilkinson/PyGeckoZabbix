PyGeckoZabbix
=============

This project is intended to get some data from Zabbix and post into Geckoboard custom widgets. As we know,
Zabbix items are very customizable, and maybe one thing or another may not work correctly because of input and output
formats. I'm trying to make it the most "plug 'n playable" as possible, but if you find something that does not work,
please let me know so as I can fix it on a modular way that will work for others as well.

Also, feel free to fork and send pull requests to improve this "plug and play" capability.


Dependencies
------------

If you use the virtualenv that comes with whit project, you don won't need to install the dependencies, but if you need
ot install them anyway, you can install using the commands below:

  * pip install pyzabbix  # For querying zabbix API using Python
  * pip install requests  # For pushing stuff to Geckoboard