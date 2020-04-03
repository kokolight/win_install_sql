win_install_sql
=========

This role is created for making installation of SQL Server 2016 automated.

Requirements
------------

No prerequisits for this role.

Role Variables
--------------

You can find the role variables in var folder:
* ssms_download_url - The url of the SSMS download
* mssql_download_url - The url of the MSSQL download
* installation_path - The path to install the SQL to
* sql_instance_name - The name of the instance
* download_path - The path to download all files to


Example Playbook
----------------

Including an example of how to use your role, the variables will be in the vars folder.

<pre>- name: Download SQL Server 2016
   hosts: windows
   tasks:
     - include_role:
         name: win_install_sql</pre>

License
-------

MIT free license
