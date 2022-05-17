# DesignADatabase
 1st Project

CREATE TABLE store (id INTEGER PRIMARY KEY, name TEXT, quantity INTEGER, price INTEGER, coo TEXT);

INSERT INTO store VALUES (1, "Apples", 4, 6, "Mexico");
INSERT INTO store VALUES (2, "Bananas", 18, 1, "Cuba");
INSERT INTO store VALUES (3, "Cherries", 3, 5, "Japan");
INSERT INTO store VALUES (4, "Kiwis", 12, .4, "Tibet");
INSERT INTO store VALUES (5, "Oranges", 15, 2, "USA");
INSERT INTO store VALUES (6, "Almonds", 9, 3, "USA");
INSERT INTO store VALUES (7, "Cashews", 7, .7, "Canada");
INSERT INTO store VALUES (8, "Peanuts", 8, .2, "Russia");
INSERT INTO store VALUES (9, "Grapes", 10, .6, "Canada");
INSERT INTO store VALUES (10, "Pumpkin", 1, .9, "Spain");
INSERT INTO store VALUES (11, "Onions", 70, .4, "USA");
INSERT INTO store VALUES (12, "Cucumber", 30, 1.1, "Yemen");
INSERT INTO store VALUES (13, "Watermelon", 80, 2.2, "China");
INSERT INTO store VALUES (14, "Celery", 40, 7.2, "Japan");
INSERT INTO store VALUES (15, "Carrot", 90, 6.5, "USA");

SELECT name,price FROM store ORDER BY price;
SELECT coo, AVG(price) FROM store GROUP BY coo;
