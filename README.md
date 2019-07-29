# myscrummy
A simple website written in django
=============
leendahscrumy
=============

leendahscrumy is a simple django app to show goals on the web.
It includes has a Super user who sets daily goals, weekly goals
and checks goals status.

Quick start
--------------

1. Add "leendahscrumy" to your INSTALLED_APPS setting like this:
       INSTALLED_APPS = [
           ...
           'leendahscrumy',
       ]

2. Include the leendahscrumy URLconf in your project urls.py like this:
      
      path('leendahscrumy/', include('leendahscrumy.urls')),
3. Run 'python manage.py migrate' to create the leendahscrumy models.

4. Start the development server and visit http://127.0.0.1:8000/admin/
   to creat a poll(you'll need the Amin app enabled).

5. Visit http://127.0.0.1:8000/leendahscrumy/ to participate in the poll.
