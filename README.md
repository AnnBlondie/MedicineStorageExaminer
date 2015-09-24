# MedicineStorageExaminer

SUMMARY
Service to collect information about the volumes of medicine items left on storages. It analyses given web-source for links on latest information presented as PDF report. Reads all available reports once a day and save information into database.

Consists of two parts - logical module data-crawler and rest-web-app that supports REST API and web interface

LIBRARIES
In service Java HTML Parser jsoup is used. To extract information from PDF PDFBox library and Tika toolkit are used. Data is stored using MongoDB

TOOLS
Git, Maven, Tomcat

REST API
GET /[location]   returns list of drugs


Task bord of project: https://trello.com/b/OE3OIbmC/fabrika-final-project
