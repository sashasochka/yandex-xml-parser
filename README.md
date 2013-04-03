Yandex.XML parser
=================

This tools provides a way to get basic yandex websearch info parsed and saved on the local computer.

## You need:
 - Java 7
 - Yandex.XML login ([register here][YA.XML])
 - Yandex.XML password
 - Not to use it overmuch - a number of queries is limited

## Features:
 - get basic info by query like url, title, annotations and yandex "green line"
 - save all web-pages returned by the query locally

## Usage:
 - To save web-pages in DIRECTORY:
       java yandex.Parser "Your query here" yourlogin yourpassword directory
 - To save web-pages in default directory:
       java yandex.Parser "Your query here" yourlogin yourpassword
 - Disable saving web-pages locally:
       java yandex.Parser "Your query here" yourlogin yourpassword --nosave

## Example:
    java yandex.Parser "python docs" uid-fhsghafr 03.206015392:53811c98048d4bb4a046d45678239987 --nosave
### Typical output:
    Overview — Python v3.3.0 documentation
    http://docs.python.org/
    Python Setup and Usage how to use Python on different platforms. Python HOWTOs in-depth documents on specific topics.Docs for other versions. Python 2.7 (stable).
    docs.python.org

    GIMP Python Documentation
    http://www.gimp.org/docs/python/
    This document outlines the interfaces to GIMP-Python, which is a set of Python modules that act as a wrapper to libgimp allowing the writing of plug-ins for GIMP.
    gimp.org

    Overview — Python v2.7 documentation
    http://docspython.org/
    Distributing Python Modules sharing modules with others. Documenting Python guide for documentation authors.Docs for other versions. Python 2.6 (stable).
    docspython.org

    Welcome to python-docs.net!
    http://python-docs.net/
    python-docs.net. Save on: Domain names, Web hosting, email accounts, SSL certificates, ecommerce products AND MORE!
    python-docs.net

    Python Client Library - Braintree
    https://www.braintreepayments.com/docs/python
    wget http://pypi.python.org/packages/source/b/braintree/braintree-2.20.0.tar.gz tar zxf braintree-2.20.0.tar.gz cd braintree-2.20.0 python setup.py install.
    braintreepayments.com

    ADOdb for Python
    http://phplens.com/lens/adodb/adodb-py-docs.htm
    ADOdb was originally developed for PHP, and ported to Python. The Python version implements a subset of the PHP version.From the Python DB API docs
    phplens.com

    Blender 
    http://www.blender.org/documentation/249PythonDoc/
    The game engine API is separate from the Blender Python API this document references and you can find its own ref doc in the doc section of the main sites below.
    blender.org

    PythonDocs - NetBeans Wiki 
    http://wiki.netbeans.org/PythonDocs
    The purpose of the wiki page is to provide a central planning location for Python documentation for NetBeans IDE.Web Docs.
    wiki.netbeans.org

    Python: module xbmc and xbmcgui
    http://xbmc.sourceforge.net/python-docs/

    xbmc.sourceforge.net

    The Hitchhiker’s Guide to Python! — The Hitchhiker's Guide to Python
    http://docs.python-guide.org/
    Welcome to The Hitchhiker’s Guide to Python. This guide is currently under heavy active development.Read the Docs.
    docs.python-guide.org


[YA.XML]: http://xml.yandex.com/
