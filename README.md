create table Students(name varchar(20), Lastname varchar(20), rolenumber integer, History integer, Math integer, Science integer);
insert into Students VALUES("Arjun","Totre", 10,85,86,90,100);
insert into Students VALUES("Desmond","Wong", 76,89,86,10,5);
insert into Students VALUES("Devin","Yip", 98,60,86,70,100);
insert into Students VALUES("Rhys","Thomas", 1,96,89,90,100);
select*from Students;
select * from Students where History = 80 and Math = 86;
select min(Math) AS worstMath
FROM Students;
select max(Math) AS bestMath
FROM Students;
select min(History) AS worstHistory
FROM Students;
select max(History) AS bestHistory
FROM STudents;
select min(English) AS worstEnglish
FROM Students;
select max(English) AS bestEnglish
FROM Students;
select min(Science) AS worstScience
FROM Students;
select max(Science) AS bestScience
FROM Students;
