# MyDFIR 30-Day SOC Analyst Challenge Day 24
[Link to full briefing](https://www.youtube.com/watch?v=xgxQuLL33oU) of Day 24 </br>
Creator of Exercise: MyDFIR (Steven)

## Task:
To install and implement osTicket in a server as part of our SOC network. 

### Installation
As per [video](https://www.youtube.com/watch?v=xgxQuLL33oU). 

Quick things to note:
1. At the this point of the [video](https://youtu.be/xgxQuLL33oU?si=KY5NFgE8I9pTuwht&t=812), the admin user credentials are crucial. To log into the ticketing system,
these should be recalled easily or kept somewhere. 

2. Also, the Database settings, the username and the password should match the values in the config.php file that was modified earlier. 

3. After that installation works, two links to access the ticketing system will appear. The URL, that's of, http://IP-address-of-osTicket-Server/osticket/upload/scp, 
the URL into the Staff Control Panel, is the one you'll need your admin user credentials from #1. 

4. If after logging out of the server, and into the XAMPP server gives trouble, like this "corrupt xampp 'mysql.user' table", one work around is [this](https://stackoverflow.com/questions/57128891/how-repair-corrupt-xampp-mysql-user-table),
whereby repairing the table command could potentially help (it had in my case).

### Credits:
Full credits to MyDFIR (Steven) for putting together this exercise















