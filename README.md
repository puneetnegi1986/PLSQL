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

-------------------------------------------------------
Creating Procedure
-------------------------------------------------------

create or  replace new_proc
as
begin 
dbms_output.put_line("Hello World");
end
