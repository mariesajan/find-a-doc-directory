## FindADoc Directory

This application is to find the details of different doctors across different categories.

The user can filter the doctors based on the **Locations** or the **Departments** which they are working for.

Database used here is Cassandra. So [download cassandra](http://www.planetcassandra.org/cassandra/)


Save the **myscript.cql** in your local path. Then open the cql shell and execute the myscript.cql using the command:
> source '/filepath/myscript.cql';

This script file is for saving the keyspaces and the required tables in the database.

After that, start the server using the command:
> npm start

Invoke the website at port 3000.
