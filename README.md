# DynamicJasperExample
[![Build Status](https://travis-ci.org/davidkey/DynamicJasperExample.svg?branch=master)](https://travis-ci.org/davidkey/DynamicJasperExample)

Short example of a dynamic JasperReport rendered as pdf / xlsx by a Spring Boot application. Uses [Jasper 6.5](https://en.wikipedia.org/wiki/JasperReports) and [DynamicJasper](http://dynamicjasper.com/) to generate reports.

## How to run
```bash
git clone https://github.com/davidkey/DynamicJasperExample.git
mvn spring-boot:run
```
Once the application has started, you can go to one of the following urls to see the reports:
* http://localhost:8080/employeeReport.pdf
* http://localhost:8080/employeeReport.xlsx 

![pdf report screenshot](https://raw.githubusercontent.com/davidkey/DynamicJasperExample/master/screenshots/reportPdf.png "pdf report screenshot")
