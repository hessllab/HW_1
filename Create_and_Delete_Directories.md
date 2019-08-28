Code for creating directories and files
```bash
mkdir -p ./Sites/Site_A/Data ./Sites/Site_A/Metadata ./Sites/Site_A/GIS # Create Sites hierarchy with Site A file structure. Location of files is below working directory
cp -r ./Sites/Site_A/ ./Sites/Site_C # Copy Site A structure to Site C
touch ./Sites/Site_A/Data/Plot_1.txt ./Sites/Site_A/Data/Plot_2.txt ./Sites/Site_A/Data/Plot_3.txt ./Sites/Site_A/Metadata/Plot_1_meta.txt ./Sites/Site_A/Metadata/Plot_2_meta.txt ./Sites/Site_A/Metadata/Plot_3_meta.txt # Add files to Data and Metadata in Site A
cp -r ./Sites/Site_A/ ./Sites/Site_B # Copy Site A structure with files to Site B
```

Code for deleting directories and files
```bash 
rm -r ./Sites # Remove all directories and files
```
