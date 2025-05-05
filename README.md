# cse102-assignment-11-database-application-using-dynamic-data-structures-solved
**TO GET THIS SOLUTION VISIT:** [CSE102 Assignment 11-Database application using dynamic data structures Solved](https://www.ankitcodinghub.com/product/cse102-assignment-11-database-application-using-dynamic-data-structures-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101998&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE102 Assignment 11-Database application using dynamic data structures  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
In this homework, you will be implementing a simple database application using dynamic data structures. Your database can have any number of tables. Each table can have any number of columns and rows. All the operations such as creating database, tables, etc. reading (querying) or writing (inserting) from/to a table will be in memory. However, we would like to able to run the database with previous one. Therefore, only one time you must save your information on the file. In other words, when your program ends, for testing, we will be able to create a new database, related tables and row data again. Also, we may run with the previous one. Be careful that this is not an assignment that requires a development of a database depend on the multiple files as tables.

You are free to design and implement these operations as mentioned above in order to test your structure. Since this is the final homework assignment for this semester, you are free to use your programming knowledge and skills that has been improving throughout the semester.

<ol>
<li>Read from a file</li>
<li>Write to a file</li>
</ol>
You may use the following structure, also any reasonable changes or insertions (if you commented in detail) will be accepted.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
typedef struct database {

tables * tList; /* to be implemented as a linked list */

int n; /* num of entries */ char * name; /* table name */ } database;

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
typedef struct tables { tables *next;

table * t;

} tables;

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
typedef struct table { char **field;

char **type; bool *isNull; bool *isKey; } table;

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
For each table;

<ul>
<li>1st row of the table is the name of the fields(columns) with their type. (e.g. name | char (20))</li>
<li>Other rows can be the different types such as char, int, float, double, char [64].
The database application will have a similar functionality as MySQL database; therefore, you would like to see the web page: MySQL
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Functionality

Create a new database if not exists

Show tables on a database by names

</div>
<div class="column">
MySQL command examples

mysql&gt; CREATE DATABASE &lt;name&gt;;

mysql&gt; SHOW TABLES;

</div>
<div class="column">
C program function name

void create_database(char *name); void show_table(database *d);

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Describe tables

Create a new table with columns on a database Remove a table from a database

Insert a key on a table

</div>
<div class="column">
mysql&gt; DESCRIBE &lt;name&gt;;

mysql&gt; CREATE TABLE pet (name VARCHAR (20), owner

VARCHAR (20), species VARCHAR (20)); mysql&gt; DROP TABLE &lt;name&gt;;

mysql&gt; ALTER TABLE contacts

ADD CONSTRAINT contacts_pk

PRIMARY KEY (contact_id);

</div>
<div class="column">
void desc_table(database *d, table *t); void insert_table(database *d, table *t);

</div>
</div>
<div class="layoutArea">
<div class="column">
void remove_table(database

*name);

Void insert_key(database *d, table *t, key_value )

</div>
</div>
<div class="layoutArea">
<div class="column">
*d, char

</div>
</div>
<div class="layoutArea">
<div class="column">
Once your database, tables and all operations ready, write a test driver and test your program by creating databases, tables, keys, and all the functions.

Submit all of your implementations including driver program and your output screens, files, reports if any, and any documentation that you write or used.

NOTE: You are free to change the design or implementation details (you must obey the linkedlist structure) that are reasonable for you if you comment on them.

</div>
</div>
</div>
