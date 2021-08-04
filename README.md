# LDES_Translator [WORK IN PROGRESS]

This package read data from LDES and generates translations for object discriptions based on available data via linked authorities such as Getty AAT, ULAN and TGN. 

## USE 

### dependencies
before running this program make sure to install the following packages:

```
pip3 install skosprovider_getty
pip3 install pandas
pip3 install regex
```

to use the program enter the following commands in the CLI. 

```
python3 ldes_translator.py --path --list
```
for example: 
```
python3 ldes_translator.py --path User/path/output.csv --list User/path/input.csv

```


| Parameter | Description | Possible values |
|---------|-----------|----------|
|path|define the path where the .csv containing the translations will be stored|filepath|
|list|define the path where the .csv containing the the object numbers of the objects for which to generate translations|filepath|



## License
This project is released as an open-source project under the MIT License