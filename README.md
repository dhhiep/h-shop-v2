# HSHOP v2

### The purpose to built this project
HShop is a little e-commerce project, so it's like a simple shopping cart project. I want to make for my friends, who need a online store to sell anything they want, clothes, shoes, tools or even service provider.
Other way, I want to practise my skills, techniques and technology, I was learning and apply in this project.

### Trello Board
https://trello.com/b/MTL5UZrv/hshop

### Development setup

  1. Clone project and install gem
  ```bash
  git clone git@github.com:dhhiep/h-shop-v2.git
  cd h-shop-v2
  bundle install
  ```

  2. Update environment variables
  ```
  Rename .env.example to .env
  Update missing value
  ```

  3. Setup database
  ```
  bundle exec rake db:create
  bundle exec rake db:migrate
  bundle exec rake db:seed
  ```
