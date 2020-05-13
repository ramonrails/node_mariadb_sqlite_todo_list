# react sample app + jest TDD + docker dev environment

Used to learn & refersh react, node, jest and docker knowledge.

- react app
- babel transpiler
- mariadb / sqlite3
- docker based local environment
- yarn packaging
- TDD with jest
- few modifications to make the test cases pass without docker setup too

```bash
➜ SQLITE_DB_LOCATION=~/tmp/todo.db yarn test
yarn run v1.21.1
$ jest
 PASS  spec/routes/updateItem.spec.js
 PASS  spec/routes/addItem.spec.js
 PASS  spec/routes/getItems.spec.js
 PASS  spec/persistence/sqlite.spec.js
 PASS  spec/routes/deleteItem.spec.js

Test Suites: 5 passed, 5 total
Tests:       9 passed, 9 total
Snapshots:   0 total
Time:        2.742s
Ran all test suites.
✨  Done in 4.18s.
```

2020-05 update: adding all my earlier experimental and learning repos to online git account in public domain
