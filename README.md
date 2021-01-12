# GIS Final Assessment of YUE LI

Here is used to publish all work of Yue Li's coursework of CASA0005 GIS module.

**If want to reproduce my work, please use the files in data and final version**

## File published

### In 'data' folder
- [x] Raw datasets
- [x] produced work of plots
- [x] produced work of datasets (not fully included in RPub)
- [x] graph of workflow (not included in RPub)

### In 'final version' folder

- [x] Appendix written in R Markdown
- [x] Essay exported as pdf

## R pub link
You could also go to the [link](https://rpubs.com/amberyli/GISappendix) to see my code with outputs.

As some outputs of my work are tables, which are partly shown in RPub, they are included fully here.

## Note of workflow graph

It was made through the [nomnoml](https://www.nomnoml.com/) website. The best way to reproduce it is to copy the raw code file and paste them in the website. The [shareble link](https://www.nomnoml.com/#view/%23background%3A%20transparent%0A%23.purple%3A%20bold%20fill%3D%23D3C1DD%20visual%3Droundrect%0A%23.green%3A%20fill%3D%2366cdaa%20visual%3Dinput%0A%23.orange%3A%20fill%3D%23ffa07a%20%0A%23.pink%3A%20fill%3Dpink%20visual%3Drhomb%0A%5B%3Cpurple%3E%20START%5D%20-%3E%20%5B%3Cgreen%3EDownload%20Subindexes%20Data%5D%0A%5B%3Cpurple%3E%20START%5D%20-%3E%20%5B%3Cgreen%3EDownload%20Basemap%20Data%5D%0A%0A%5BDownload%20Basemap%20Data%5D%20-%3E%20%5B%3Corange%3EStudy%20Area%20.shp%20file%5D%0A%5BStudy%20Area%20.shp%20file%5D%20-%3E%20%5B%3Cgreen%3EImport%20into%20R%5D%0A%5BImport%20into%20R%5D%20-%3E%20%5B%3Corange%3E%20London%20Borough%20Layer%5D%0A%0A%5BDownload%20Subindexes%20Data%5D%20-%3E%20%5B%3Corange%3EEarning%20.xls%20file%5D%0A%5BEarning%20.xls%20file%5D%20-%3E%20%5B%3Cgreen%3EImport%20into%20R%20to%20calculate%20GPG%5D%0A%5BImport%20into%20R%20to%20calculate%20GPG%5D%20-%3E%20%5B%3Cpink%3EAny%20missing%20value%5D%0A%0A%5BDownload%20Subindexes%20Data%5D%20-%3E%20%5B%3Corange%3EEmployment%20rate%20.xls%20file%5D%0A%5BEmployment%20rate%20.xls%20file%5D-%3E%20%5B%3Cgreen%3EImport%20into%20R%20to%20calculate%20EG%5D%0A%5BImport%20into%20R%20to%20calculate%20EG%5D%20-%3E%20%5B%3Cpink%3EAny%20missing%20value%5D%0A%0A%5BDownload%20Subindexes%20Data%5D%20-%3E%20%5B%3Corange%3EEmployment%20by%20occupation%20.xls%20file%5D%0A%5BEmployment%20by%20occupation%20.xls%20file%5D-%3E%20%5B%3Cgreen%3EImport%20into%20R%20to%20calculate%20AG%5D%0A%5BImport%20into%20R%20to%20calculate%20AG%5D%20-%3E%20%5B%3Cpink%3EAny%20missing%20value%5D%0A%0A%5BAny%20missing%20value%5D%20-%3E%20%5BYES%5D%0A%5BAny%20missing%20value%5D%20-%3E%20%5BNO%5D%0A%5BYES%5D%20-%3E%20%5B%3Cgreen%3EChange%20NA%20to%200%5D%0A%5BChange%20NA%20to%200%5D%20-%3E%20%5B%3Corange%3ECalculate%20INDEX%5D%0A%5BNO%5D%20-%3E%20%5B%3Cgreen%3EUpdate%20GPG%2C%20EG%2C%20AG%5D%0A%5BUpdate%20GPG%2C%20EG%2C%20AG%5D%20-%3E%20%5BCalculate%20INDEX%5D%0A%0A%5BCalculate%20INDEX%5D%20-%3E%20%5B%3Cgreen%3EComprehensive%20Visualization%5D%0A%5B%3Corange%3E%20London%20Borough%20Layer%5D%20-%3E%20%5B%3Cgreen%3EComprehensive%20Visualization%5D%0A%0A%5BCalculate%20INDEX%5D%20-%3E%20%5B%3Cgreen%3ESpatial%20Pattern%20Analysis%5D%0A%5B%3Corange%3E%20London%20Borough%20Layer%5D%20-%3E%20%5B%3Cgreen%3ESpatial%20Pattern%20Analysis%5D%0A%0A%5BSpatial%20Pattern%20Analysis%5D%20-%3E%20%5B%3Cpurple%3E%20END%5D%0A%5BComprehensive%20Visualization%5D%20-%3E%20%5B%3Cpurple%3E%20END%5D%0A%0A%0A%0A) exported through the webpage sometimes fails to open due to different web browser.

