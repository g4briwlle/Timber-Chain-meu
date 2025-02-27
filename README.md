This repository contains timber transportation data for the IPE wood species from 2010 to 2020. 

The `transports.csv` columns account for:

- 'id_wood': id of the IPE species. It matches the column 'id_wood' in the file `species.csv`.
- 'node_src' and 'node_dest': id of the enterprise of origin and destination of the wood. They match the column "id_emp" in the file `nodes.csv`. 
- 'vol': volume of timber transported in cubic meters.
- 'id_product': id of the product type. It matches the column "id_product" in the file `products.csv`.
- 'date': the transportation date.

The Jupyter Notebook contains a code to build the _Timber Trade Network_ and to compute the _k most likely supply chains_ of a given enterprise.

The demo has been tested with Python 3.10.9 and the following package versions:
- pandas 1.5.3
- networkx 2.8.4
- matplotlib 3.7.0
- tqdm 4.64.1
- plotly 5.9.0

To run the demo, simply open the file `Timber Chain Demo Notebook.ipynb` in a Jupyter Notebook and run the cells. 

A complete description of what a _Timber Trade Network_ and the _k most likely supply chains_ are can be found in the paper:

_L.G. Nonato, V. Russo, B. Costa, F. Moreno-Vera, G. Toledo, O. de Jesus, R. Vieira, M. Lentini, J. Poco, and L.G. Nonato.
[Analyzing Timber Trade in Brazil: assessing timber networks and supply chains](https://www.researchsquare.com/article/rs-4580916/v1), Researchsquare, 2024._

Please, acknowledge the paper when using the data or code.
