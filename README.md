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

[YA.XML]: http://xml.yandex.com/
