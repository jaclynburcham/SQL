# SQL
CREATE TABLE store (id INTEGER PRIMARY KEY, name TEXT, cost REAL, favourites INTEGER, fruit TEXT);

INSERT into store VALUES (1, "Passionberry", 5.50, 6, "passionfruit");
INSERT into store VALUES (2, "Apple Pie", 6.00, 4, "Apple");
INSERT into store VALUES (3, "Mangodream", 4.75, 7, "Mango");
INSERT into store VALUES (4, "OrangeUGlad", 5.75, 5, "Orange");
INSERT into store VALUES (5, "Pineapple Tea", 8.50, 9, "Pineapple");
INSERT into store VALUES (6, "Cherry Delight", 7.50, 1, "Cherry");
INSERT into store VALUES (7, "Vanilla Love", 6.00, 3, "Vanilla");
INSERT into store VALUES (8, "Peary Fairy", 5.00, 8, "Pear");
INSERT into store VALUES (9, "Cheeky Peachy", 9.00, 2, "Peach");
INSERT into store VALUES (10, "Spin Dip", 4.50, 15, "Spinach");
INSERT into store VALUES (11, "Pom Daddy", 9.75, 10, "Pommagranite");
INSERT into store VALUES (12, "Coco-Nutty", 6.50, 12, "Coconut");
INSERT into store VALUES (13, "Green Dude", 7.50, 14, "Any Greens");
INSERT into store VALUES (14, "Burberry", 6.00, 11, "Blueberries");
INSERT into store VALUES (15, "Rassppy", 8.25, 13, "Raspberries");

SELECT * from STORE;

what are options that are less expensive then $7.00?
SELECT * FROM store WHERE cost < 7.00;

what is everyone's least to most favourite smoothies?
SELECT * FROM store ORDER BY favourites DESC;

what is the most expensive smoothie?
SELECT MAX(cost) FROM store;
