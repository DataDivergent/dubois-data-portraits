# Recreations of W.E.B Dubois's Data Portraits

decksh recreations of visualizations in "W.E.B Dubois's Data Portraits, Visualizing Black America" 
edited by Whitney Battle-Baptiste and Britt Rusert (ISBN 978-1-61689-706-2).

The original plates (also included in this repo), may be accessed at the [Library of Congress].(https://www.loc.gov/collections/african-american-photographs-1900-paris-exposition/?st=grid&sb=shelf-id_desc)

## List of Plates

* Plate  1: The Georgia Negro
* Plate  2: Relative Negro Population of the States of the United States
* Plate  3: States of the United States According to Their Negro Population
* Plate  4: Negro Population of Georgia
* Plate  5: Negro Population of Georgia by Counties, 1890
* Plate  6: Negro Population of Georgia by Counties, 1870, 1880
* Plate  7: Comparative Increase of White and Colored Population of Georgia
* Plate  8: Migration of Negroes 1890
* Plate  9: Age Distribution of Georgia Negroes Compared with France
* Plate 10: Conjugal Condition
* Plate 11: City and Rural Population 1890
* Plate 12: Slave and Free Negroes
* Plate 13: Race Amalgamation in Georgia
* Plate 14: Illiteracy
* Plate 15: Children in the Public Schools
* Plate 16: Teachers in Georgia Public Schools
* Plate 17: Number Of Negro Students Taking The Various Courses Of Study Offered In Georgia Schools
* Plate 18: Value of Land Owned by Georgia Negroes
* Plate 19: Acres of Land Owned by Negroes in Georgia
* Plate 20: Land Owned by Negroes in Georgia, USA, 1870-1900
* Plate 21: Valuation of Town and City Property Owned by Georgia Negroes
* Plate 22: Assessed Valuation of all Taxable Property Owned by Georgia Negroes
* Plate 23: Negro population in two cities of Georgia
* Plate 24: Value of Farming Tools
* Plate 25: Assessed Value of Household and Kitchen Furniture Owned by Georgia Negroes
* Plate 26: Occupations Of Georgia Negroes
* Plate 27: Occupations Of Negroes And Whites In Georgia
* Plate 30: Condition of 300 Negro Farm Tenants After 1 Year's Toil, 1898
* Plate 31: Income and Expenditure
* Plate 37: A Series Of Statistical Charts Illustrating The Conditions Of Descendants Of Formal African Slaves Now Resident In The Unites States
* Plate 38: Distribution of Negroes in the United States
* Plate 39: Increase in the Negro Population in the United States
* Plate 40: Comparative rate of increase of the White and Negro elements population of the United States
* Plate 41: Population Comparison
* Plate 42: Population Proportions
* Plate 43: Occupations in which American Negroes are engaged
* Plate 44: Proportion of Whites and Negroes in the different classes
* Plate 45: Occupations in which 10,000 or more American Negroes are engaged
* Plate 46: Number of Negro teachers in the Public Schools of the United States
* Plate 47: Illiteracy of the American Negro compared with other nations
* Plate 48: Enrollment in the Negro common school of the former slave States
* Plate 49: Proportion Of Total Negro Children Of School Age Who Are Enrolled In The Public Schools
* Plate 50: The Rise of Negroes from Slavery to Freedom in One Generation
* Plate 51: Proportion of Freemen and Slaves
* Plate 52: City and Rural Population
* Plate 53: Conjugal condition of American Negroes according to age periods
* Plate 54: Amalgamation of the White and Black elements of the population in the United States
* Plate 55: Proprietes contribuables des Nègres dans trois Etats des Etats Unis
* Plate 56: Negro landowners
* Plate 57: Negro business men in the United States
* Plate 58: Pauperism among American Negroes
* Plate 59: Mortality of American Negroes
* Plate 60: Crime among American Negroes
* Plate 61: American Negro newspapers and periodicals
* Plate 62: Religion of American Negroes
* Plate 63: Statistics of Negro Church Organizations
* Plate XX: Decrease of Illiteracy Among Black Freedmen of the United States (not in the book discovered by Jason Forrest)

## Making the recreations

You can use git to download the repo to your computer.

```
git clone https://github.com/ajstarks/dubois-data-portraits
```

Each plate has its own directory, for example ```plate27```, and in the the directory is the bash
script ```mkdeck``` which will create both a PDF (```f.pdf```) and PNG ```(f1.png)``` version of the
plate. 

```
cd plate27
./mkdeck
```

Also, each directory contains the original image of the plate, for example ```original-plate-27.jpg```

Note that the repo assumes these environment variables are set:

```
duboisans=PublicSans-Regular
duboiserif=PublicSans-Bold
duboismono=Inconsolata-Medium
portrait=1584,2016
landscape=2016,1584
```
