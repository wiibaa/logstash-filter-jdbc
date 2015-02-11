# About mixin definition

Whether it is for input/filter/output, communicating with a database through JDBC should be very similar as it would require common capabilities:

* connection pool
* transaction
* ...

but it can be implemented with different libraries:

* Ruby: Sequel, Activerecords,...
* Java: Plain JDBC, Apache commons- DBCP, c3p0 ...

This filter contains a mixin proposal based on Sequel
