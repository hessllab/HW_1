The following code makes a directories Data, Metadata, GIS within directory Site_A, which is in directory Site. Moving down the directory into Sites, so that Site_A/ can be replicated to Site_C/. From there, Site_A/Data/ and Site_A/Metadata/ are popoulated with the necessary text files. Once these are populated, they are copied to Site_B.
```bash
mkdir -p Sites/Site_A/{Data,Metadata,GIS}
cd Sites
cp -r Site_A/ Site_C/
touch Site_A/Data/Plot_1.txt Site_A/Data/Plot_2.txt Site_A/Data/Plot_3.txt Site_A/Metadata/Plot_1_meta.txt Site_A/Metadata/Plot_2_meta.txt Site_A/Metadata/Plot_3_meta.txt
cp -r Site_A/ Site_B/
```

The following code moves up one directory so that Sites can be correctly located and recursively deleted.
```bash
cd ..
rm -r Sites
```
