Django cheet sheet:

for all below task: create a virutal env

## Task-1 : CREATE PROJECT , APP & RUN SERVER.

1. project setup, check Django installed, run app form venv.

## Task-2: CREATE ROUTES,DYNAMIC ROUTES,MULTIPLE DYNAMIC ROUTES.

1. creating basic get server routes. send response with httpsResponse
2. creating basic dynamic routes with path, re_path, kwargs

## Task-3: TEMPLATES.

3. creating template both project level and app level

templates task:

for template task use include for adding path.

template task1: - class:12
create template in 2 apps and project level.
register app and templates
create view with render and connect with urls at app level
register app urls in project urls file.
create own template tag in base html file and pass data from app template html file to base html
make sure both view render data in between template tags in browser.

template task2:- class:13
create template in app level
register app and templates
pass content from view and display in template folders .html page.
pass content like nested object, object ,list etc.. use render method with view
display html page with data passed from view.

template task3:- class:14
create a template in app and register both app and template.
pass content from view
use template filter like text filter, list filter, yes/no & plural , pluralize, urlencode.
displayed data passed from view with filters.

template task4:- class:15
templates tags
create a template in app and register both app and template

1. make sure to pass html string code like something........ and display content with both html tag and with out html tag use safe, but html result should return bold content because we have passed html content with <b></b> content
2. pass content make sure content have both array data and object data from view and display in templates .html page with as variables and templates tags

- display object with index
- `{% if %}...{% else %}`
- `{% for %}...{% empty %}`
- `{% with %}` - create a variable
- `{% verbatim %}` (ignore template parsing)
- safe.

template task5:- class:16
create a template in app and register both app and template
crate a static folder and add css,image,js
register static
pass dummy content from apps template html page with customly created template tags
create a template in outerproject and include navbar.html page in base html
in navbar navigation both view name and anchor tag href name should be same.
connect both templates base.html page and app level template html page with extends
display static css color differently for both app level html page and templates folder base html page.

## task4 - ORM task.... :

class-21,22,23,24

1. create a model in app.
2. register app
3. migrate a model
4. add data manually in SQLite db
5. use commands to reterive data with commands like
   get()
   all()
   filter()
   ordering and chaining
   exclude - opposite of filter
   values - returns data as dictionaries
   first / last - get first or last record
   count() - total number of records
6. display model data in templates html page with passing data
   from views to apps template .html page.

class 25 & 26

1. creating a model and migration
2. adding data in model with create method from shelll
3. using model data to display in view which is in html page.

4. create superuser
   login to super admin panel and create/add user from webinterface.
   exploring of ready made django admin webpage through web.

class 27 & 28
creating multiple models
registering models in django-admin panel
adding user from django-admin panel

creating customisation in admin list view
registering model in new way
add new filters method with tuple.

## task5 - form submission with models

class 29
creation of form submission
create form and save form data in model

## task6 - todo form curd operations

class-30
todo app
with bootstarp

## task7 - django forms with cur operations

class-31,32,33
create a froms with django froms
perform curd operatoin with django form

class -36 
only django user creation in admin panel
allow access to users,group from django admin panel
allowing user to login to admin panel

##  task8 - djang forms, django auth
class-37
1. creation of register,login & logout with django auth.
2. using django predefined user model
3. used django forms to validate and save data in django model

class-38
what i have learned
1. how to add files or images
2. install pillow library for adding files
3. save images or files and view them which are saved.