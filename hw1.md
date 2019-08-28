This first script creates the Sites folder and its contents in the current working directory.

```
# Create the Sites directory
mkdir Sites
# Move to that directory
cd Sites
# Create Site_A and its directories
mkdir -p Site_A/Data Site_A/Metadata Site_A/GIS
# Create the Plot files within Site_A's Data
touch Site_A/Data/Plot_1.txt Site_A/Data/Plot_2.txt Site_A/Data/Plot_3.txt
# Create the Plot Metadata files within Site_A's Metadata
touch Site_A/Metadata/Plot_1_Meta.txt Site_A/Metadata/Plot_2_Meta.txt Site_A/Metadata/Plot_3_Meta.txt 
# Copy the contents of Site_A to new directories Site_B and Site_C
cp -r Site_A Site_B
cp -r Site_A Site_C
# Remove all text files from Site_C
rm Site_C/Data/*.txt Site_C/Metadata/*.txt
# Back out of the Sites directory
cd ..
```
---

This second script deletes the Sites folder from the current directory.
```
# Delete Sites and all of its contents
rm -r Sites
```

