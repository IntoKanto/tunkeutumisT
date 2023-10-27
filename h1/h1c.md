## SQL injection vulnerability in WHERE clause allowing retrieval of hidden data

Tehtävänä on suorittaa SQL ingektio kuvitteelliseen verkkokauppaan saadakseen julkaisemattomien tuotteiden tietoja esiin. 

Tehtäväannossa on annettu SQL käsky joka hakee tietyn kategorian julkaistut tuotteet

    SELECT * FROM products WHERE category = 'Gifts' AND released = 1

Kyseinen käsky hakee 'products' taulusta kaikki tiedot kunhan 'category' on Gifts ja 'released' on 1 (tuote on julkaistu, released=0 tarkoittaa ettei tuotetta ole julkaistu).

