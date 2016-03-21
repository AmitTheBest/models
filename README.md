
# Agile ORM

Agile ORM is a Functional Object-Relational-Mapper. It's fast, simple and query-efficient.

Some developres claim that ORM is an anti-pattern that might be simple, but for any decent
project it will become inefficient, non-scalable and inflexible limitation that you will have
to hack around constantly to get any resemblence of performance.

Agile ORM strives to fundamentally redesign the patterns that we use to access SQL
and give you in exchange a data access library, that is:

 - Humble. Never uses more than one SQL query.
 - Structured. Design your models and their fields in a flexible way.
 - Expressive. Add fields to your model that are calculated in SQL.
 - Functional. Convert models into expressions and actions.
 - Simple. Clear syntax and great flexibility.
 - PHP-style. Follows PHP-way and not copying other languages.

## Origins

This project is based around Model implementation in Agile Toolkit. The first version of
Model layer was debuted in 4.0 version of Agile Toolkit that was published in 2011. 
(https://github.com/atk4/atk4/commit/976ccce73c5c7bf5afbedc70aa3f72158dbf534b)
Since then it was significantly improved and became very stable.
http://book.agiletoolkit.org/model/sql.html.

We are the same team that made Agile Toolkit framework and we're committed to bringing
Agile ORM to the new level of standard and re-integrate it in Agile Toolkit version 4.4.

