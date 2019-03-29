# Plan for chitter challenge
## Handling peeps
  [x] Domain model
  [x] Set up the project
  [] Set up databases
    [x] migrations folder
    [x] "chitter" (id, name, handle, time, content [max length=140])
      [x] 01 migration file
    [] "chitter_test" (id, name, handle, time, content [max length=140])
      [] 02 migration route
    [] database_helper
  [] implementing CRUD
    [] C [x] R [] U [] D
    [x] Read (Chitter.all)
      [x] feature tests
      [x] insert few peeps
      [x] pass feature test
      [x] refactor
      [x] TDD to implement PG and retrieve peeps from database - unit test for chitter.rb
    [] Create
      [] feature test
      [] pass the feature test
      [] refactor dummy data insertion
    [] Delete
      [] feature test
      [] pass the feature test
      [] refactor
  [] README
    [] full instructions
    [] Screenshots
## Handling userbase
[] Set up databases
  [] "userbase" (id, name, handle, email, password)
    [] 01 migration route
  [] "userbase_test" (id, name, handle, email, password)
    [] 02 migration route
  [] database_helper
[] implementing CRUD
  [] C [] R [] U [] D
  [] Read (Chitter.all)
    [] feature tests
    [] insert few peeps
    [] TDD to implement PG and retrieve peeps from database - unit test for chitter.rb
  [] Create
    [] feature test
    [] pass the feature test
    [] refactor dummy data insertion
  [] Delete
    [] feature test
    [] pass the feature test
    [] refactor
[] README
  [] full instructions
  [] Screenshots
[] Style
  [] HTML labels for everything
  [] CSS classes added to elements
  [] CSS style