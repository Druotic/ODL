Team:
James Beavers
Shivani Angane
Pallavi Mahajan


Contributions breakdown:
---James Beavers---
-Initial start menus and Oracle login
-Physician (Health Professional) menus, associations, viewing patient info and assignment, etc.

---Pallavi Mahajan---
-Patient Menus
-Triggers, Alerts

---Shivani Angane---
-Login validation
-Patient Menus
-HealthFriend


Running the application:
1. Connect to an eos machine (ssh, etc) and copy files to the machine.
2. Add jdk, `add jdk`
3. Set environment variable, `setenv CLASSPATH .:/ncsu/oracle10g/.install/i386_linux26/OraHome1/jdbc/lib/ojdbc14_g.jar`
4. From inside the project directory, compile the files using `javac ui/ODLCLI.java lib/DBAPI.java`
5. Start the application `java ui/ODLCLI`
