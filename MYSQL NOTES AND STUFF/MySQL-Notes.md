# MySQL Notes

## Programming with Mosh

[Cheat Sheet](https://codewithmosh.lpages.co/sql-cheat-sheet/)
[MySQL Tutorial for Beginners (Full Course)](https://www.youtube.com/watch?v=7S_tz1z_5bA)

What is a Database?

        a collectin of data stored in a format that can easily be accessed

        use software application to manage them, called database management system

        DBMS query/modifies data

        relation vs non-relational or NOSQL DB's

Relational

        store data in tables that are linked to each other using relationships

        each table stores data about a specific type of object

        SQL, or Structured Query Language, is the language we use to work with / query / modify data

RDBMS

        MySQL - MySQL is most popular

        SQL Server

        Oracle

Non-Relational - don't understand SQL, have their own query language

Ess Que Elle or SEQUEL?

        Structured English Query Language, then changed to Structured Query Language

        People in Non-English people countries usually call it Ess Que Elle, but in the US, people call it SQL

        My Ess Que Elle > My Sequel lol wtf

How to Install:

        THIS WAS EXTREMELY COMPLICATED SO: [MOSH'S INSTALL METHOD HERE](https://youtu.be/7S_tz1z_5bA?t=590)

        NOTE: I can't install for VS Code for whatever reason, maybe because I'm using the free version

CREATING DATABASE:

        [ETC ETC ETC](https://youtu.be/7S_tz1z_5bA?t=910)

        [Resources from Mosh's Course Preview](https://codewithmosh.com/courses/complete-sql-mastery/lectures/9590092)

        okay, so I located Mosh's databases by finding his online course, and luckily they were included in part of his "preview" videos

        from there, I dl'd the DB scripts and ran these in MySQL WB

        when tables were caught "Fetching" for an eternity, I restarted WorkBench and the problem resolved!

DB NOTES:

        SELECT > FROM > WHERE > ORDER BY

        -- IS A COMMENT

MATH OPERATORS:

        SELECT

                last_name,
                first_name,
                points,
                (points + 10) * 100

                        -- ORDER OF OPERATORS
                        -- FIRST MULTIPLIED BY 10, THEN ADDED
                        -- + 10 * 100, first 10 multiplied by 100 then added
                        -- (points + 10) * 100, first 10 is added, then multiplied by 100

                (points + 10) * 100 AS discount_factor

                	-- AS discount_factor, give the column an ALIAS // NAME
                        -- AS 'discount factor' give the ALIAS a space

        SELECT DISTINCT

[LEFT OFF HERE](https://youtu.be/7S_tz1z_5bA?t=2302)
