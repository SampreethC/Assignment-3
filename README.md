GitHub tree :
1) check the handler is valid or not (do it last)
2) if valid handler then see if you have any repos under that - if exist list the repo name
3) if has repo, list branches under that repo
4) if repo not present, then create it (input will your repo name)
5) if branch is not present under any repo (input will your repo name)  - Crete it (input will be branch name)
6) store this tree info in DB
7) you need to read data from DB and list it
---------
REST API's
1) API to create a new repo (write in db as well)
2) API to create a new branch (write in db as well)
3) API to show the tree
4) API to show all the repo's (only)
5) API to show all the branches (only)
6) API to list data from DB

Reasons for this Assignment:

1) Able to understand Re-usability of code
2) How to create the REST API's
3) How to connect and use the third party API
4) if we can able to write the first part in all 3 fashion (callback/promises/async-await), then try to understand the advantage and disadvantage of each in terms of readability, code formatting, functionality extensibility and bug fixing.
