CREATE TABLE "employees" (
  "emp_no" int,
  "emp_title_id" varchar,
  "birth_date" date,
  "first_name" varchar,
  "last_name" varchar,
  "sex" varchar,
  "hire_date" date
);

CREATE TABLE "titles" (
  "title_id" varchar,
  "title" varchar
);

CREATE TABLE "departments" (
  "dept_no" varchar,
  "dept_name" varchar
);

CREATE TABLE "salaries" (
  "emp_no" int,
  "salary" int
);

CREATE TABLE "dept_manager" (
  "dept_no" varchar,
  "emp_no" int
);

CREATE TABLE "dept_emp" (
  "emp_no" int,
  "dept_no" varchar
);

