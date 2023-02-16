# Account 2 - Setup Authentication

## Setup git access
```
https://github.com/nhson2022/Account2.git
git remote add origin git@github.com:nhson2022/Account2.git
git status
git add -A
git commit -m "Create account with devise"
git push -u origin main
```
---
## Setup project
```
./bin/importmap pin jquery bootstrap
bundle add bootstrap
```
---
**Setup devise**
Go to page and follow https://github.com/heartcombo/devise
```
bundle add devise
rails generate devise:install
rails g devise:views

rails generate devise User
rails db:migrate
```