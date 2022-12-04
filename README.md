# Predicción mediana del precio de NFT's usando LSTM

El surgimiento de la tecnología blockchain, los contratos inteligentes y en general el mundo de las criptomonedas ha generado un nuevo mercado de distintos objetos como imagenes o terrenos virtuales. Estos objetos llamados  tokens suelen estar caracterizados por ser unicos, es decir, que solo tienen un propietario y por pertenecer a un contratointeligente.

En este proyecto se propone generar un modelo que permita calcular la mediana de los tokens de un contrato con el fin de obtener informacion sobre la variabilidad de los precios de estos tokens. El objetivo consiste en entrenar una red neuronal con informacion de todas las transacciones del contrato hasta el día anterior, para predecir la mediana de las transacciones del día actual. Esto se hace, ya que si se sabe que mediana tendrán las transacciones del día de hoy, los potenciales compradores tendran cierta información del precio general de los tokens.

El proyecto cuenta con los siguientes recursos:
- link del doumento : [documento](https://github.com/dnunezq/IA_Proyet_dp/blob/main/Proyecto_final_Intro_IA.pdf)
- link del video: [video](https://vimeo.com/777748127)
- link notebook interactivo : [notebook](http://34.125.227.157:8080/notebooks/work/Predicci%C3%B3n%20del%20precio%20de%20NFT's%20.ipynb/?token=ecd742482430bd26924140ed338f1e1164a01e2414968da54bdf7fb76c63a74e)

## Getting Started 

These instructions will give you a copy of the project up and running on
your local machine for development and testing purposes. See deployment
for notes on deploying the project on a live system.

### Prerequisites

Requirements for the software and other tools to build, test and push 
- [install npm](https://www.example.com](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)

### Installing


Install the dependencies

    npm i 

And run with 

    mpn run start
    
## Getting Started  (Notebook)


### Prerequisites

Requirements for the software and other tools to build, test and push 
- [install juyter](https://jupyter.org/install)
- install requirements

### Installing


Install the requirements

    cd /notebook
    pip install -r requirements.txt

And run 
    
    jupyter notebook 

    
## Authors

  - **David Núñez** 
  - **Fabian Andrés Ruiz**
  - **María Sol Botello**
  - **Sofia Salinas Rico**

## License

This project is licensed under the [CC0 1.0 Universal](LICENSE.md)
Creative Commons License - see the [LICENSE.md](LICENSE.md) file for
details


