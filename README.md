# ForcePlan-PostgreSQL
Implementation of ForcePlan feature for PostgreSQL 9.3
A plug-in for PostgreSQL database engine, which can force the query optimizer into choosing a user specified execution plan for a query.

- Along with an SQL query, we can supply an execution plan as well in XML format.
- Optimizer skips optimization phase and uses the plan passed as argument along with the query.

How to use:

<Query> fpc <path_of_xml_file>
