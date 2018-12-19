# Financial_Data_Acuiring_Server

My single person program. Enchanting my understanding in multiple Java areas including: Socket-based Server-Client transition, Multi-Threading-Server, MySQL database management with SQL commands and Internet Crawling with Jsoup.

## Some Instructions

Original repository at <https://github.com/Master-Alcy/StevensCodes/tree/master/Java-2018/501/CS-501-Final-Project>

### Compile and run

Put all .java files in src/ and all .jar files in lib/ together in same folder.

Compile all files:  
javac -cp jsoup-1.11.3.jar;mysql-connector-java-8.0.13.jar *.java  

Set-up Database:  
java -cp mysql-connector-java-8.0.13.jar;. Setup  

Run Server:  
java -cp jsoup-1.11.3.jar;mysql-connector-java-8.0.13.jar;. Server  

Open another command window, then run Client:  
java -cp mysql-connector-java-8.0.13.jar;. Client  

### How to Test

1. I used default setting to setup my database and tables. In case things don't work out for you, I attached a short .mp4 video demonstrating the test.
2. You Only Need to enter SYMBOL of companies in Client. Server send back data for every input.
3. I don't have enough time to handle every possible errors, so the symbols should be valid.
4. You can keep entering symbols, or enter 'bye' to exit.
5. Multiple Clients are allowed, but the 'bye' can't close other clients