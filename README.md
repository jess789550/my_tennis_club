# my_tennis_club app
W3 Schools Tutorial
https://www.w3schools.com/django/index.php

This app features a home page and a members page with a list of tennis club members and their contact details.

## How to use
```
# Clone repository
git clone https://github.com/jessicakan789/my_tennis_club

# Enter repository
cd my_tennis_club

# Create virtual environment
python -m venv myworld

# Install requirements
pip install -r requirements.txt

# Run server
python manage.py runserver
```

Navigate to http://127.0.0.1:8000/

## Useful database commands
```
# Generate models
python manage.py inspectdb

# View database tables
python manage.py dbshell
.tables
```

## Tree
```
.
├── db.sqlite3
├── manage.py
├── members
│   ├── admin.py
│   ├── apps.py
│   ├── __init__.py
│   ├── migrations
│   │   ├── 0001_initial.py
│   │   ├── 0002_member_joined_date_member_phone.py
│   │   ├── __init__.py
│   │   └── __pycache__
│   │       ├── 0001_initial.cpython-310.pyc
│   │       ├── 0002_member_joined_date_member_phone.cpython-310.pyc
│   │       └── __init__.cpython-310.pyc
│   ├── models.py
│   ├── __pycache__
│   │   ├── admin.cpython-310.pyc
│   │   ├── apps.cpython-310.pyc
│   │   ├── __init__.cpython-310.pyc
│   │   ├── models.cpython-310.pyc
│   │   ├── urls.cpython-310.pyc
│   │   └── views.cpython-310.pyc
│   ├── static
│   │   └── myfirst.css
│   ├── templates
│   │   ├── 404.html
│   │   ├── all_members.html
│   │   ├── details.html
│   │   ├── main.html
│   │   ├── master.html
│   │   ├── myfirst.html
│   │   └── template.html
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── mystaticfiles
│   ├── myglobal.css
│   └── mystyles.css
├── my_tennis_club
│   ├── asgi.py
│   ├── __init__.py
│   ├── __pycache__
│   │   ├── __init__.cpython-310.pyc
│   │   ├── settings.cpython-310.pyc
│   │   ├── urls.cpython-310.pyc
│   │   └── wsgi.cpython-310.pyc
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── productionfiles
│   ├── admin
│   │   ├── css
│   │   │   ├── autocomplete.css
│   │   │   ├── base.css
│   │   │   ├── changelists.css
│   │   │   ├── dark_mode.css
│   │   │   ├── dashboard.css
│   │   │   ├── forms.css
│   │   │   ├── login.css
│   │   │   ├── nav_sidebar.css
│   │   │   ├── responsive.css
│   │   │   ├── responsive_rtl.css
│   │   │   ├── rtl.css
│   │   │   ├── vendor
│   │   │   │   └── select2
│   │   │   │       ├── LICENSE-SELECT2.md
│   │   │   │       ├── select2.css
│   │   │   │       └── select2.min.css
│   │   │   └── widgets.css
│   │   ├── img
│   │   │   ├── calendar-icons.svg
│   │   │   ├── gis
│   │   │   │   ├── move_vertex_off.svg
│   │   │   │   └── move_vertex_on.svg
│   │   │   ├── icon-addlink.svg
│   │   │   ├── icon-alert.svg
│   │   │   ├── icon-calendar.svg
│   │   │   ├── icon-changelink.svg
│   │   │   ├── icon-clock.svg
│   │   │   ├── icon-deletelink.svg
│   │   │   ├── icon-hidelink.svg
│   │   │   ├── icon-no.svg
│   │   │   ├── icon-unknown-alt.svg
│   │   │   ├── icon-unknown.svg
│   │   │   ├── icon-viewlink.svg
│   │   │   ├── icon-yes.svg
│   │   │   ├── inline-delete.svg
│   │   │   ├── LICENSE
│   │   │   ├── README.txt
│   │   │   ├── search.svg
│   │   │   ├── selector-icons.svg
│   │   │   ├── sorting-icons.svg
│   │   │   ├── tooltag-add.svg
│   │   │   └── tooltag-arrowright.svg
│   │   └── js
│   │       ├── actions.js
│   │       ├── admin
│   │       │   ├── DateTimeShortcuts.js
│   │       │   └── RelatedObjectLookups.js
│   │       ├── autocomplete.js
│   │       ├── calendar.js
│   │       ├── cancel.js
│   │       ├── change_form.js
│   │       ├── collapse.js
│   │       ├── core.js
│   │       ├── filters.js
│   │       ├── inlines.js
│   │       ├── jquery.init.js
│   │       ├── nav_sidebar.js
│   │       ├── popup_response.js
│   │       ├── prepopulate_init.js
│   │       ├── prepopulate.js
│   │       ├── SelectBox.js
│   │       ├── SelectFilter2.js
│   │       ├── theme.js
│   │       ├── urlify.js
│   │       └── vendor
│   │           ├── jquery
│   │           │   ├── jquery.js
│   │           │   ├── jquery.min.js
│   │           │   └── LICENSE.txt
│   │           ├── select2
│   │           │   ├── i18n
│   │           │   │   ├── af.js
│   │           │   │   ├── ar.js
│   │           │   │   ├── az.js
│   │           │   │   ├── bg.js
│   │           │   │   ├── bn.js
│   │           │   │   ├── bs.js
│   │           │   │   ├── ca.js
│   │           │   │   ├── cs.js
│   │           │   │   ├── da.js
│   │           │   │   ├── de.js
│   │           │   │   ├── dsb.js
│   │           │   │   ├── el.js
│   │           │   │   ├── en.js
│   │           │   │   ├── es.js
│   │           │   │   ├── et.js
│   │           │   │   ├── eu.js
│   │           │   │   ├── fa.js
│   │           │   │   ├── fi.js
│   │           │   │   ├── fr.js
│   │           │   │   ├── gl.js
│   │           │   │   ├── he.js
│   │           │   │   ├── hi.js
│   │           │   │   ├── hr.js
│   │           │   │   ├── hsb.js
│   │           │   │   ├── hu.js
│   │           │   │   ├── hy.js
│   │           │   │   ├── id.js
│   │           │   │   ├── is.js
│   │           │   │   ├── it.js
│   │           │   │   ├── ja.js
│   │           │   │   ├── ka.js
│   │           │   │   ├── km.js
│   │           │   │   ├── ko.js
│   │           │   │   ├── lt.js
│   │           │   │   ├── lv.js
│   │           │   │   ├── mk.js
│   │           │   │   ├── ms.js
│   │           │   │   ├── nb.js
│   │           │   │   ├── ne.js
│   │           │   │   ├── nl.js
│   │           │   │   ├── pl.js
│   │           │   │   ├── ps.js
│   │           │   │   ├── pt-BR.js
│   │           │   │   ├── pt.js
│   │           │   │   ├── ro.js
│   │           │   │   ├── ru.js
│   │           │   │   ├── sk.js
│   │           │   │   ├── sl.js
│   │           │   │   ├── sq.js
│   │           │   │   ├── sr-Cyrl.js
│   │           │   │   ├── sr.js
│   │           │   │   ├── sv.js
│   │           │   │   ├── th.js
│   │           │   │   ├── tk.js
│   │           │   │   ├── tr.js
│   │           │   │   ├── uk.js
│   │           │   │   ├── vi.js
│   │           │   │   ├── zh-CN.js
│   │           │   │   └── zh-TW.js
│   │           │   ├── LICENSE.md
│   │           │   ├── select2.full.js
│   │           │   └── select2.full.min.js
│   │           └── xregexp
│   │               ├── LICENSE.txt
│   │               ├── xregexp.js
│   │               └── xregexp.min.js
│   ├── myfirst.css
│   ├── myglobal.css
│   └── mystyles.css
├── README.md
└── requirements.txt

23 directories, 171 files

```


## Notes

* my_tennis_club is the project
* members is the app
* models.py contains information about each table in the database
* views.py consists of functions that get the information
* templates displays the information from views.py
* urls.py defines the endpoint where the template is displayed



