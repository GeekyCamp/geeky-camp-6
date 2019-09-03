# Databases

Домашно (понеже го има в презентацията, тук само го копирам, не трябва да се различава от slide-овете):

**Краен срок:** 07.09.2019, 09:00.

Домашни, предадени (submit-нати) до 11.09, 09:00 ще бъдат преглеждани, но ще се отнемат 4 точки.
Домашни предадени след това няма да бъдат преглеждани.

GitHub user for review: _petar-iv_

Необходимо е да submit-нете всички SQL заявки, които правите.
Това включва `create database`, `use <database>` (или името на database-а да участва във всички queries), `create table`, `insert into`, `select`.

## 1. T-shirts

### Условие

Every GeekyCamp participant, lecturer, mentor gets a t-shirt (different sizes and colors).
- Create a table that contains the t-shirt choices (create table + inserts). Note: the table must not contain any names! Just type of the t-shirt (enum - male or female), color, size (enum).
- Create a query that aggregates the data in the table: retrieves type, color, size and count of t-shirts that are of the same (type, color, size). Order the results by type, color and size. Include the result set (as you see it in the MySQL CLI).

### Оценяване
Максимален брой точки: 5

## 2. IT Competitions

### Условие

Create a database for high school students IT competitions. Each student has first name, last name, city. At least 6 students should be entered into the database. A student may be assigned to a single project, but a project can have multiple students assigned to it. A project has a name and a description. At least 4 projects should be available in the database. A competition has a name and a city in which is being held. At least 3 competitions should be entered in the database. The database should be able to store a relation between a competition, project and the award that has received (‘gold’, ‘silver’, ‘bronze’ or null if a project has not been awarded in the competition). Every project has been part of each competition. Create the following queries:

- Retrieve students from a particular city
- Retrieve students whose last name end with letter 'a'
- Retrieve all students (first name and last name) and the names of their projects
- Retrieve the first and last names of all students who work on a project with a given name
- Retrieve competition name, project name and the award that has been given (a project that has not been awarded should not be present in the result)

Отново трябва да submit-нете всички SQL заявки, които правите.

### Оценяване
Максимален брой точки: 15
