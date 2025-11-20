<!DOCTYPE html>
<html lang="en">
<head>
<h1>📚 Library Management System – MySQL Project</h1>

<p>This project is a complete <strong>Library Management System</strong> built using <strong>MySQL</strong>, designed to manage books, authors, borrowers, library branches, book copies, and loan transactions. It also includes <strong>SQL queries</strong> to answer real-world library management questions.</p>

<hr>

<h2>🗂️ Project Overview</h2>

<p>The project contains:</p>
<ul>
    <li>Database creation</li>
    <li>Table creation with primary & foreign keys</li>
    <li>Relationships between tables</li>
    <li>Practical queries for operations</li>
    <li>Use of JOINs, GROUP BY, HAVING, etc.</li>
</ul>

<hr>

<h2>🛢️ Database & Tables</h2>

<h3>📌 Database:</h3>
<code>MY_PROJECT</code>

<h3>📌 Tables Included:</h3>

<table>
    <tr>
        <th>Table Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>TBL_PUBLISHER</td>
        <td>Stores publisher details</td>
    </tr>
    <tr>
        <td>TBL_BOOK</td>
        <td>Stores books & publisher info</td>
    </tr>
    <tr>
        <td>TBL_BOOK_AUTHORS</td>
        <td>Stores authors of books</td>
    </tr>
    <tr>
        <td>TBL_LIBRARY_BRANCH</td>
        <td>Contains library branches</td>
    </tr>
    <tr>
        <td>TBL_BOOK_COPIES</td>
        <td>Tracks book copies in each branch</td>
    </tr>
    <tr>
        <td>TBL_BORROWER</td>
        <td>Stores borrower data</td>
    </tr>
    <tr>
        <td>TBL_BOOK_LOANS</td>
        <td>Tracks loaned books across branches</td>
    </tr>
</table>

<hr>

<h2>🔗 Database Schema Highlights</h2>
<ul>
    <li>Books linked to publishers</li>
    <li>Authors linked to books</li>
    <li>Copies linked to branches</li>
    <li>Borrowers linked to book loans</li>
    <li>Loans connect books, borrowers & branches</li>
</ul>

<hr>

<h2>📝 SQL Tasks Included</h2>

<p>This project answers several practical library queries. Examples:</p>

<h3>1️⃣ Copies of "The Lost Tribe" in Sharpstown Branch</h3>
<p>Counts copies of a specific book in a branch.</p>

<h3>2️⃣ Copies of "The Lost Tribe" in All Branches</h3>
<p>Shows copies in every library branch.</p>

<h3>3️⃣ Borrowers with No Books Checked Out</h3>
<p>Uses LEFT JOIN to find borrowers with zero loans.</p>

<h3>4️⃣ Loan Details for Sharpstown with Specific Due Date</h3>
<p>Retrieves borrower name, address, and book title.</p>

<h3>5️⃣ Total Books Loaned Out Per Branch</h3>
<p>Uses GROUP BY to aggregate loan count.</p>

<h3>6️⃣ Borrowers with More Than 5 Books Checked Out</h3>
<p>Uses GROUP BY + HAVING.</p>

<h3>7️⃣ Stephen King Books in Central Branch</h3>
<p>Shows number of copies of Stephen King books in Central branch.</p>

<hr>

<h2>🧠 Concepts Used</h2>
<ul>
    <li>Primary & Foreign Keys</li>
    <li>AUTO_INCREMENT</li>
    <li>Normalization</li>
    <li>INNER JOIN / LEFT JOIN</li>
    <li>GROUP BY & HAVING</li>
    <li>Aggregate Functions</li>
</ul>

<hr>

<h2>📂 Project File</h2>
<p><strong>SQL File:</strong> MYSQL Project - Library Management System.sql</p>
<p>Contains full database creation, table creation, and SQL tasks.</p>

<hr>

<h2>▶️ How to Run the Project</h2>

<pre><code>1. Install MySQL / open an online SQL editor.
2. Import or paste the SQL file.
3. Run:

CREATE DATABASE MY_PROJECT;
USE MY_PROJECT;

4. Execute table creation commands.
5. Run the task queries at the bottom of the script.
</code></pre>

<hr>

<h2>🚀 Skills Demonstrated</h2>

<ul>
    <li>SQL Query Writing</li>
    <li>Database Schema Design</li>
    <li>Working with Constraints</li>
    <li>JOIN Operations</li>
    <li>Real-world Data Analysis</li>
</ul>

<hr>

<h2>🙌 Acknowledgment</h2>
<p>This project was created as part of learning SQL and understanding database management systems.</p>

</body>
</html>
