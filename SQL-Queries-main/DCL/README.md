# DCL Queries


## 1. GRANT Command

-> Assigns new privileges to a user account, allowing access to specific database objects, actions, or functions.<br>

<b>Syntax</b><br>
GRANT privilege_type [(column_list)] ON [object_type] object_name TO user [WITH GRANT OPTION];<br>

## 2. REVOKE Command

-> Removes previously granted privileges from a user account, taking away their access to certain database objects or actions.<br>

<b>Syntax</b><br>
REVOKE [GRANT OPTION FOR] privilege_type [(column_list)] ON [object_type] object_name FROM user [CASCADE];<br>