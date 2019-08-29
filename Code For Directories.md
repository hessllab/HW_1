# NEW CODE for HW_1
Here is the code to set up the new working directory.
```
mkdir -p Sites/Site_A/Data Sites/Site_A/Metadata Sites/Site_A/GIS
# First line made a directory including a folder with Site A and 3 other folders inside Site A called Data,Metadata and GIS

touch Sites/Site_A/Data/Plot_1.txt Sites/Site_A/Data/Plot_2.txt Sites/Site_A/Data/Plot_3.txt Sites/Site_A/Metadata/Plot_1_meta.txt Sites/Site_A/Metadata/Plot_2_meta.txt Sites/Site_A/Metadata/Plot_3_meta.txt
#This inserted respective text files into their proper folders in Site_A. Text files went into the Data folder and Metadata folder. Three
files into each folder.


cp -r Sites/Site_A Sites/Site_B
#This copied everything from Site_A directory into a new directory name Site_B

#Must do same thing and create Site_C directory
cp -r Sites/Site_A Sites/Site_C
#This again copied everything in directory Site_A into a new directory Site_C

#Must remove text files in Directory Site_C from Data and Metadata folders
rm Sites/Site_C/Data/*.txt*
rm Sites/Site_C/Metadata/*.txt*
#This removed all text files from Site_C in folders Data and Metadata by using the wildcard to identify all text files
```

Here is the code to delete the entire directory created.
```
rm -r Sites
#This will remove/delete the directory just created
```
