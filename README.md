# :birthday: **Birthday Registration**
- - -

## :book: **Introduction**:
Web application developed in ***python*** with ***flask*** that allows you to save and remove birthdays.
- - -

## :floppy_disk: **Database**:

#### **Create Database**:
```
sqlite3 birthdays.db
```

#### **Create Birthday Table**:
```SQL
CREATE TABLE birthdays (
    id INTEGER,
    name TEXT,
    month INTEGER,
    day INTEGER,
    PRIMARY KEY(id)
);
```
- - -

## :arrow_forward: **Run**

#### **Flask**: 
```Linux
flask run
```
- - -

## :eight_spoked_asterisk: **References**
[CS50 Harvard - Week 7](https://cs50.harvard.edu/x/2020/psets/7/)

