This is a list of things that should be done.
Help is welcome!

Document
========
- Revise README.md more naturally


Code
====
- Refactor the code
  Initial commit is Proof Of Concept version therefore We need to clean-up the code.

- Remove limitations
  See README.md to know more details. 

- Fix Makefile to make pg_plan_advsr more easily
  pg_plan_advsr needs some files from pg_hint_plan and pg_store_plans.
  It would be better to copy them to its directory automaticaly.
  
- ~~Implement CREATE STATISTICS suggestion as a new feature~~

- Improve Extended Statistics Suggestion feature
	- Increase the number of supported column types: grouping columns and  expression columns
	- Check existing Extended stats to prevent duplicate Extended stats suggestions
	- Suggest only Extended stats that are effective
