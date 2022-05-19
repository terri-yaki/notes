SELECT * FROM _table

CREATE TABLE _name ()

PRIMARY KEY / REFERENCES --FOREIGN KEY

ORDER BY (ASC/DESC)

DESCRIBE TABLE

INSERT into _table VALUES()

ALTER TABLE _table ADD/DROP rows/colums

UPDATE _table
SET _row/_column = xx

SELECT _rows/_columns AS _newname // changing rows name

FROM _table
WHERE _ LIKE '_' --number
LIKE '%' -- any character

DISTINCT _rows

//Functions

COUNT()
SUM()
AVG()

UNION //combine all together

SELECT _rows
FROM _table
JOIN _table2  //LEFT RIGHT JOIN
ON _sharedkey (condition)

WHERE _asbn IN () //nested loop

LIMIT (number)