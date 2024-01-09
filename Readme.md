### Clone the repo, extract ant.zip and set environemntal variables
```
## JAVA Path
export JAVA_HOME="/usr/lib/jvm/java-11-openjdk-amd64"

## ANT Installation
export ANT_HOME="/home/sakib/Documents/Software/apache-ant-1.10.13"
export PATH="${PATH}:${ANT_HOME}/bin"
```
### Replace above variables with your path where you have extracted/installed them

### Run the command below in terminal to check if ant is installed
```
ant -version
```
### Download your version of jasperreport library from [JasperReport Library](https://sourceforge.net/projects/jasperreports/files/jasperreports/)

### Extract, open terminal in the parent folder and run the command below to check if the build file of your library source files is properly detected
```
ant -p
```
### Run the two commands below in the terminal to compile the source files and build the library
```
ant alljars

ant retrievelibs
```
### Lastly move the lib folder inside dist to your parent folder

### Done, Now your library is ready to be deployed.
