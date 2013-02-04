django-foundation-forms
=======================

Rendering django forms with the use of zurb-foundation framework.

###Usage

First, clone the project:<br>
`git clone git://github.com/paprykut/django-foundation-forms.git`

Move **forms.html** to your project template directory. In my case, this would be:<br>
`/home/paprykut/myproject/myproject/templates/`

In order to use the form generation in your templates, include the following 
code within the respective html files:<br>
`{% include "forms.py" with form=form %}`

The "form" variable is passed from **views.py**.
