# csvToSql
this program was created to convert large cvs files to mysql queries, it is optimized to do it faster and without consuming excessively ram.

It was created with netbeans and maven, you need to build it and it will generate a file called “csvToSqlMaven-1.0-jar-with-dependencies.jar” in the folder target.


to run it open a console, move to the project path an execute the next command

$java -jar target/csvToSqlMaven-1.0-jar-with-dependencies.jar Path/fileToConvert.csv tableName
