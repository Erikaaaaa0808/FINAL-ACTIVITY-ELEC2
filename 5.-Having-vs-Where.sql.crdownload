-- HAVING VS WHERE

SELECT gender, AVG(age)
FROM employee_demographics
WHERE AVG(age) > 40
GROUP BY gender
;
# invalid. when finding with a group by function, the use of where clause is invalid because a group function must start first.

SELECT gender, AVG(age)
FROM employee_demographics
GROUP BY gender
HAVING AVG(age) > 40
;
# if finding a numerical value, having function must use after the group by function

SELECT occupation, AVG(salary)
FROM employee_salary
WHERE occupation LIKE '%manager%'
GROUP BY occupation
HAVING AVG(salary) > 75009
;





