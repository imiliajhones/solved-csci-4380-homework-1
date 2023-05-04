Download Link: https://assignmentchef.com/product/solved-csci-4380-homework-1
<br>
Database Systems

Relational Model and SQL DDL

This homework will focus on the concepts of the relational model, as well as the use of relational algebra to query a relational schema.

<ol>

 <li>You’re building the database for a tech company that wants to keep track of the conferences it offers, and the people who register to attend.</li>

</ol>

You need to store information about each conference: its name, location, start date, end date, and cost to attend. You also need to keep track of the names, birthday, email addresses, current job title, and current employer of each attendee, as well as a record of which conferences they register to attend. Finally, each of the conferences has an arbitrary number of corporate sponsors, and you will need to keep track of the company name, which conferences they sponsor, and the amount they paid to sponsor them.

<ul>

 <li>(12 points) Create the schemas for four relations to store data about the conferences (conference), attendees (people), conference registration (registration), and corporate sponsors (sponsors). Make sure to define keys for each relation (if appropriate), but do not create any artificial keys.</li>

 <li>(2 points) Give two example tuples for the Conference relation:</li>

 <li>(6 points) Give three example tuples for the Sponsor relation, representing that one company sponsored two different conferences and one conference had two different sponsors:</li>

</ul>

<ol start="2">

 <li>(15 points) For each of the relations you created in part (a) above, write a CREATE TABLE statement in SQL to create the table, including appropriate keys. Assume that no two people share the same email, and that no two people have both the same name and birthday. Upload your solutions in a separate homework-1.sql file.</li>

</ol>