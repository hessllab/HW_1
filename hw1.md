I will make a directory!

```bash
mkdir -p Sites/Site_A/Data Sites/Site_A/Metadata Sites/Site_A/GIS #This creates the directory Sites and the directory Site_A, which contains Data, Metadata, and GIS   
cd Sites/Site_A #change our directory to Site A so the next line can be more concise  
touch Data/Plot_1.txt Data/Plot_2.txt Data/Plot_3.txt Metadata/Plot_1_meta.txt Metadata/Plot_2_meta.txt Metadata/Plot_3_meta.txt #creating the text files under Data and Metadata  
cp -r . ../Site_B #copying Site A to create Site B  
cp -r . ../Site_C #Copying Site A to create Site C  
rm -r -i ../Site_C/*ata/* #removing all files in Site C without removing the directory structure. Using a wildcard for *ata/*, I'm able to remove files from both Data and Metadata  
```
  
Wow, glad that's over. Let's delete it.
  
```bash
cd ../.. #moving out of the Sites directory so it can be removed  
rm -r -i Sites #remove the entire directory
```
