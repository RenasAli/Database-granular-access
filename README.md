# Database-granular-access
## Setup
- Clone this repository
- Have MySQL-server installed.
- Use a a bash shell.
- In the bash shell navigate to the folder, where dumpfile.sql is located.
- Run the command:
  	1. <code> mysql -u root -p < dumpfile.sql </code>
   	2. set the password for your root.
- Run this command in bash shell to connect to the database:
  
	1. <code> mysql -u hello -p </code>
- Than you need the password:
  	1. <code>@Renas@42926624</code>
- Run this command to use the database:
    	1. <code>USE user_db; </code>

Så you are able to use the database....
## Table permissions
you have the following permissions.
### admin
- You can read every thing in this table.
- you can create, update and delete every this in this table.


### student
- you can read every thing in this table.
- you can not create, delete or update any thing in this table.

### users
- you can read user_name and user_address, but you can not read user_password in this table.
- you can only update user_address in this table.
- you can not create or delete any thing in this table.


