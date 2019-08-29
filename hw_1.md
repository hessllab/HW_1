mkdir -p Sites/{Site_A,Site_B,Site_C} 
##This command creates the main "Site" folder as well as Site A,B,C subfolders.
mkdir Sites/Site_A/Data Sites/Site_A/Metadata Sites/Site_A/GIS Sites/Site_B/Data Sites/Site_B/Metadata Sites/Site_B/GIS Sites/Site_C/Data Sites/Site_C/Metadata Sites/Site_C/GIS 
##This command creates the Data, Metadata, and GIS subfolders within Site A,B,C.
touch Sites/Site_A/Data/Plot_1.txt Sites/Site_A/Metadata/Plot_1_meta.txt Sites/Site_A/Data/Plot_2.txt Sites/Site_A/Metadata/Plot_2_meta.txt Sites/Site_A/Data/Plot_3.txt Sites/Site_A/Metadata/Plot_3_meta.txt Sites/Site_B/Data/Plot_1.txt Sites/Site_B/Metadata/Plot_1_meta.txt Sites/Site_B/Data/Plot_2.txt Sites/Site_B/Metadata/Plot_2_meta.txt Sites/Site_B/Data/Plot_3.txt Sites/Site_B/Metadata/Plot_3_meta.txt 
##This command creates all of the text files for the Data and Metadata subfolders in Site A and B.
-----------------------------------------------------------------


rm -r Sites 
##This command deletes the "Sites" folder and everything contained within.