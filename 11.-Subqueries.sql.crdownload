-- SUBQUERIES
-- a query in another query

SELECT *
FROM employee_demographics;
SELECT *
FROM employee_salary;
SELECT *
FROM parks_departments;

SELECT *
FROM employee_demographics
WHERE employee_id IN
				(SELECT employee_id
					FROM employee_salary
                    WHERE dept_id = 1)
;
# the operand should only have one column


SELECT first_name, salary, 
	(SELECT AVG(salary)
	FROM employee_salary)
FROM employee_salary
;


SELECT gender, AVG(age), MAX(age), MIN(age), COUNT(age)
FROM employee_demographics
GROUP BY gender
;

SELECT AVG(`MAX(AGE)`)
FROM
	(SELECT gender, AVG(age), MAX(age), MIN(age), COUNT(age)
	FROM employee_demographics
	GROUP BY gender) AS agg_table
;

SELECT AVG(max_age)
FROM
	(SELECT gender,
    AVG(age) AS avg_age,
    MAX(age) AS max_age,
    MIN(age) AS min_age,
    COUNT(age) AS count_age
	FROM employee_demographics
	GROUP BY gender) AS agg_table
;









