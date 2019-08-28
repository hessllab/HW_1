```
mkdir sites   #creates the parent directory for the files
cd sites      #changes the directory to the parent directory

mkdir site{_A,_B,_C} #creates subdirectories (site_A, site_B, site_C) in the parent directory
mkdir -p ./site_A/Data ./site_A/Metadata ./site_A/GIS #creates the file (Data, Metadata, GIS) in the site_A directory

cp -r ./site_A/* ./site_B #copy the content of site_A to site_B
cp -r ./site_A/* ./site_C #copy the content of site_A to site_C

cd site_A/Data && touch Plot_1.txt Plot_2.txt Plot_3.txt #change directory to the Data subdirectory in site_A and write the txt files
cd ../Metadata && touch Plot_1_meta.txt Plot_2_meta.txt Plot_3_meta.txt #change directory to the Metadata subdirectory in site_A and write the txt files

cp -r ../* ../../site_B #copy the contents of site_A into site_B
```
```
cd ../../..
rm -r -i sites #removes the files from the tail asking every step up if you want to delete a file
```
