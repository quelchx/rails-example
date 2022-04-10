# Ruby Notes

## Create A Fresh Project

- run `rails` to view every rails cli command available.

- run `rails new foodlog`, make sure sqlite3 and libsqlite3 is installed or during configuration some errors will occur.
  
- run `rails server` to start the server.

### To generate models

- run `rails g model Entry`

- can also run `rails g scaffold Entry` but this is different (faster + also generates more files)

- example using scaffold `rails g scaffold Entry meal_type:string calories:integer proteins:integer carbohydrates:integer fats:integer`. This will generate a lot of files.

- after creating this scaffold we could visit `http://localhost:3000/rails/info/routes` and this will show info in regards to everything that was basically generated.

