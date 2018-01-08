# PLSQL
Basic of PLSQL


Basic Syntext of PL SQL is

Declaration 
Executable command
Exception Blcok
End 

<Variable Declaration>
Begin
<Executable command>
<Exception Block>
End;

Simple Hello world Pl Sql

DECLARE
message varchar(100) := "Hello wolrd !";

Begin
dbms_output.put_line(message);
End;

----------------------------------------------------------------------------
Creating Procedure
----------------------------------------------------------------------------

create or  replace new_proc
as
begin 
dbms_output.put_line("Hello World");
end
-----------------------------------------------------------------------------
How to Update millions or records in a table ?
-----------------------------------------------------------------------------
CREATE TABLE new_table as select <do the update "here"> from old_table; 

index new_table 
grant on new table 
add constraints on new_table 
etc on new_table 

drop table old_table 
rename new_table to old_table; 
------------------------------------------------------------------------------

http://www.naturalprogrammer.com/spring-framework-rest-api-validation/
https://lmonkiewicz.com/programming/get-noticed-2017/spring-boot-rest-request-validation/
