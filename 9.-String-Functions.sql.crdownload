-- STRING FUNCTIONS

-- LENGTH
SELECT LENGTH('skyfall');

SELECT first_name, LENGTH(first_name)
FROM employee_demographics
ORDER BY 2
;

-- UPPER/LOWER
SELECT UPPER('sky');
SELECT LOWER('SKY');

SELECT first_name, UPPER(first_name)
FROM employee_demographics
;

-- TRIM
SELECT TRIM('         sky           ');
SELECT LTRIM('               sky                    ');
SELECT RTRIM('               sky                    ');

-- SUBSTRING
SELECT first_name, LEFT(first_name, 4)
FROM employee_demographics
;

SELECT first_name,
LEFT(first_name, 4),
RIGHT(first_name, 4)
FROM employee_demographics
;

SELECT first_name,
LEFT(first_name, 4),
RIGHT(first_name, 4),
SUBSTRING(first_name,3,2) #third position, how many characters from the position
FROM employee_demographics
;

SELECT first_name,
LEFT(first_name, 4),
RIGHT(first_name, 4),
SUBSTRING(first_name,3,2),
birth_date,
SUBSTRING(birth_date,6,2) AS birth_month
FROM employee_demographics
;

-- REPLACE
SELECT first_name, REPLACE(first_name, 'a','z') # what you're going to replace, what to replace it with
FROM employee_demographics
;

-- LOCATE
SELECT LOCATE('x','Alexander'); # to find the position

SELECT first_name, LOCATE('An', first_name)
FROM employee_demographics
;

-- CONCAT
# combining columns into one column
SELECT first_name, last_name,
CONCAT(first_name,' ',last_name) AS full_name
FROM employee_demographics
;













