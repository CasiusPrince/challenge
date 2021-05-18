# challenge

show databases;
use world;
show tables;
SELECT count(id) from city where countrycode= "USA";
describe city; 
select * from city where name= "new york";
select population, lifeexpectancy from country where name='argentina';
select c.name from city c join country co on co.capital=c.id where co.name='spain';
SELECT cl.language FROM countrylanguage cl JOIN country co ON cl.countrycode = co.code where name='southeast asia';
SELECT NAME FROM city WHERE NAME = 'f' ORDER BY NAME ASC LIMIT 25; 
