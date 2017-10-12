# Localizable
Localization of iOS and Android projects


## Configuration
create yaml file 

ex : 
```
datasource : "izy-strings.xlsx"
ios : {"root" : "../izy-ios","path" : "izy/Application"}
android : {"root" : "../izy-android"}
```

datasource : path to excel file contains localizable strings
ios : root of project and path for Base.lproj if needed
android : root of project

## Run
```
need pip 9.0.1 and Python 2.7
sudo pip install -r requirements.txt
python localize.py <file.yaml>
```
