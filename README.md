# Documenting VBI View

Requires python 3.5.x

## To install dependencies

    virtualenv docstuff

    docstuff\Scripts\activate

    pip install -r requirements.txt --upgrade

## To start documenting a project

    docstuff\Scripts\activate

    sphinx-quickstart

## To generate html

    docstuff\Scripts\activate

    make html

## To change theme

Open source\conf.py and in the line

    html_theme = '<Your theme name>'

For example: html_theme = 'sphinx-rtd-theme'

## Reference

https://github.com/ralsina/rst-cheatsheet/blob/master/rst-cheatsheet.rst



Links:
code .

Set the link code above the figure, heading,..... items as .. _forgot-password:

If you forgot password, see :ref:`forgot-password`

