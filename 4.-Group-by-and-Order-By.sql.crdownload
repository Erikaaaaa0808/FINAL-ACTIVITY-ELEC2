-- GROUP BY

SELECT *
FROM employee_demographics;


SELECT gender
FROM employee_demographics
GROUP BY gender
;

SELECT first_name
FROM employee_demographics
GROUP BY gender
;
# will not work,  the select has to match group by if we are not performing aggregate function on it

SELECT gender, AVG(age) # aggregate function
FROM employee_demographics
GROUP BY gender
;

SELECT gender, AVG(age), MAX(age), MIN(age), COUNT(age)
FROM employee_demographics
GROUP BY gender
;
# average - average value of the selected data
# max - maximum
# min - minimum
# count - count of how many values in the column/s

SELECT occupation, salary
FROM employee_salary
GROUP BY occupation, salary
;


-- ORDER BY
# order the selected data in ascending or descending order

SELECT *
FROM employee_demographics
ORDER BY first_name
;
# default is in ascending order

SELECT *
FROM employee_demographics
ORDER BY first_name DESC;


SELECT *
FROM employee_demographics
ORDER BY gender, age
;

SELECT *
FROM employee_demographics
ORDER BY gender, age DESC
;

# column position is important

SELECT *
FROM employee_demographics
ORDER BY 5, 4
;
# can be order by column number



