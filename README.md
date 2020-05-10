# MSCI3300
Basic on the flask-rbac

---

Create the database table(include books)
---
```
CREATE TABLE IF NOT EXISTS `book_tbl`(
   `student_id` INT UNSIGNED,
   `student_name` VARCHAR(40) NOT NULL,
   `runoob_author` VARCHAR(40) NOT NULL,
   `borrow_date` DATE NOT NULL,
   `submission_date` DATE NOT NULL,
   `book_name` VARCHAR(40) NOT NULL,
   `book_id` INT UNSIGNED,
   `info` VARCHAR(100),
   `book_place` VARCHAR(100),
   PRIMARY KEY ( `student_id` )
)ENGINE=InnoDB DEFAULT CHARSET=utf8;


```


# session 
## An established session is the basic requirement to perform a connection-oriented communication. A session also is the basic step to transmit in connectionless communication modes. However any unidirectional transmission does not define a session.

# MySQL datebase

## if you want run in local env

[watch the video](https://www.youtube.com/watch?v=DPBspKl2epk&list=PLdS4Kd4flpQxY-xE-wAcwkZ6KFQ0WgC3O&index=5&t=837s)


