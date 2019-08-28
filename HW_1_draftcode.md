```bash  
mkdir -p ~/Sites/Site_A/Data ~/Sites/Site_A/Metadata ~/Sites/Site_A/GIS  
# make new directories for Site_A with hirarchy.  
touch ~/Sites/Site_A/Data/Plot_1.txt ~/Sites/Site_A/Data/Plot_2.txt ~/Sites/Site_A/Data/Plot_3.txt  
# create text files under Data folder.
touch ~/Sites/Site_A/Metadata/Plot_1_meta.txt ~/Sites/Site_A/Metadata/Plot_2_meta.txt ~/Sites/Site_A/Metadata/Plot_3_meta.txt 
# create tect files under Metadata folder.
cp -r ~/Sites/Site_A ~/Sites/Site_B  
# make a new folder of Site_B with the same folder structure and files of the Site_A. 
cp -r ~/Sites/Site_A ~/Sites/Site_C  
# make a new folder of Site_C with the same folder structure and files of the Site_A.
rm ~/Sites/Site_C/Data/* ~/Sites/Site_C/Metadata/*  
# remove all the text files in Site_C folder.
```  

```bash  
rm -r ~/Sites  
# remove all the folders and files under the Sites folder, and remove the Sites folder itself.
```  