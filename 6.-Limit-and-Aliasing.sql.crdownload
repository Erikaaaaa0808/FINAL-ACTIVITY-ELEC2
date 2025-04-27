-- LIMIT & ALIASING

SELECT *
FROM employee_demographics
LIMIT 3
;

SELECT *
FROM employee_demographics
ORDER BY age DESC
LIMIT 3
;

SELECT *
FROM employee_demographics
ORDER BY age DESC
LIMIT 2, 1
;
# the top 2 and the one (number) that comes after the top 2


-- ALIASING
# to change the anme of the column

SELECT gender, AVG(age) AS avg_age
FROM employee_demographics
GROUP BY gender
HAVING avg_age > 40
;

# or can be used like this

SELECT gender, AVG(age) avg_age
FROM employee_demographics
GROUP BY gender
HAVING avg_age > 40
;


