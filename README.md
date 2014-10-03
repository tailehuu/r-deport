# Welcome to Rails - Deport Project

Web-based shopping cart application

### Create rails app
    rails new -r-deport
    cd r-deport
    
### Push to GitHub
    git init
    git add .
    git commit -m "init"
    git remote add origin https://github.com/tailehuu/r-deport.git
    git push -u origin master

### Generate scaffolding
    # product
    rails generate scaffold product title:string description:text image_url:string price:decimal
    # apply product's migration
    rake db:migrate
    # test
    rake test
    # unit test
    rake test:units
    # create seed data, db/seed.rb
    rake db:seed
    # db rollback
    rake db:rollback