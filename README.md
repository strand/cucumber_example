## These commands were run to get this Cucumber example rolling

```
10227  cd cucumber
10228  cucumber features
10229  subl .
10230  cd ..
10231  rails new cucumber
10232  cd cucumber
10233  bundle install
10234  cucumber features
10235* cd cucumber
10236* ls
10237  rails generate rspec:install
10238  rails generate cucumber:install --capybara
10239  cucumber features
10240  cucumber features/manage_assignments.feature:5
10241  subl .
10242  cucumber features/manage_assignments.feature:5
10243  rails generate scaffold assignments
10244  cucumber features/manage_assignments.feature:5
10245  RAILS_ENV='test' rake db:create db:migrate
10246  cucumber features/manage_assignments.feature:5
10247  cucumber features/manage_assignments.feature
10248  git add .
10249  git commit -m "Created application and got the first feature passing."
10250  git remote add origin git@github.com:strand/cucumber_example.git
10251  subl .git
10252  ls -a
10253  git init
10254  git add .
10255  git commit -m "Created application and got the first feature passing."
10256  git remote add origin git@github.com:strand/cucumber_example.git
10257  git push origin master
10258  cucumber features
10259  cucumber features/manage_assignments.feature:9
10260  rails destroy scaffold assignments
10261  rake db:rollback
10262  rails generate scaffold assignments title details:text
10263  rake db:migrate
10264  cucumber features
10265  cucumber features/manage_assignments.feature:9
10266  rake db:drop
10267  RAILS_ENV='test' rake db:migrate
10268  cucumber features/manage_assignments.feature:9
```
