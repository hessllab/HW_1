# Caleb Malay
## HW_1

```bash
#Makes the directory Sites
mkdir ./Sites
#Makes subdirectories
mkdir -p Sites/Site_A/Data Sites/Site_A/Metadata Sites/Site_A/GIS
#Creates .txt files within specific subdirectories 
touch Sites/Site_A/Data/Plot_1.txt Sites/Site_A/Data/Plot_2.txt Sites/Site_A/Data/Plot_3.txt Sites/Site_A/Metadata/Plot_1.txt Sites/Site_A/Metadata/Plot_2.txt Sites/Site_A/Metadata/Plot_3.txt
#Creates further subdirectories Sites B and C and copies the contents of Site_A into them
cp -r Sites/Site_A/ Sites/Site_B/ 
cp -r Sites/Site_A/ Sites/Site_C/
#Removes the contents of specific subdirectories from Site_C
rm Sites/Site_C/metadata/*
rm Sites/Site_C/data/*
```
```bash
#Removes the directory Sites and all of its contents
rm -r Sites
```
