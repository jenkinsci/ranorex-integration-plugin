# Changelog
## 0.3.0
### 2019-08-30
* Fix compatibility with Snippet Generator
* Add Pipeline support

## 0.2.0
### 2018-04-05
* Add Unit Tests
* Changed "Workspace" to "Ranorex Working Directory" in the Console Summary
* Clean up code
* Fix report path and compressed report path (add support for white spaces)
* Fix absolute path for test suite file on windows master node
* Fix global parameters
* Fix command line arguments 

## 0.1.4
### 2018-03-19
* Add support for Unix Master installation
* Fix issue with default reportname if no reportname is specified
* Add plugin version in log summary

## 0.1.3
### 2018-03-15
* add Missing commit

## 0.1.2
### 2018-03-13
* Skipped 0.1.1 due to internal changes
* Change the working directory to the outputpath where the *.rxtst file is located
* Fix issue with report directory path separator (use File.separator), to prevent issues if master node is installed on a unix machine
* Code cleanup (Remove unused codes to prevent against site effects

## 0.1.0
### 2017-06-15
* Add dropdown to select report extension. Currently RXLOG and HTML are possible.

## 0.0.2
### 2017-06-12
* Reportdirectories will now be automatically created if they do not exist. Please be careful when using variables in the directory name

## 0.0.1
### 2017-04-25
* Release version 0.0.1 