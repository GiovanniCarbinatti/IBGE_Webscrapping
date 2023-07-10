# IBGE_Webscrapping
Webscrapping of the data available at https://cidades.ibge.gov.br
Once IBGE (Brazillian Institute of Geography and Statistics) does not provide an API to have access to this data, a scrapping was necessary

The code requires some hours to run, causing timeouts in Colab. The IBGE site is also unstable, which can cause some errors during execution.
The *start* variable is used to mitigate this error - using it in the main *for loop* enables re-running the cell without modifications.

## Please note:
This code as it is now doesn't work anymore due to recent changes (July 2023) in the site, which now presents the data of the Census 2022
It should work properly with some small changes.
