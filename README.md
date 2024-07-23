# RN-Airline-Passenger-Satisfaction

### Instruções para rodar o KAN
Dentro do diretório base do projeto, siga os seguintes passos:

1. Crie e ative um ambiente virtual

    ```sh
    python3 -m venv pykan-env
    source pykan-env/bin/activate  # No Windows use `pykan-env\Scripts\activate`
    ```

2. Instale o Pykan do GitHub

    ```sh
    pip install git+https://github.com/KindXiaoming/pykan.git
    ```

3. Instale os requirements

    ```sh
    pip install -r kan_requirements.txt
    ```

### AVISO
Após fazer o procedimento acima, verifique se existem os seguintes arquivos:
 - `./pykan-env/lib/python3.10/site-packages/kan/assets/img/mult_symbol.png`
 - `./pykan-env/lib/python3.10/site-packages/kan/assets/img/sum_symbol.png`

Em caso negativo, siga os seguintes passos:

1. Crie o diretório para armazenar os arquivos

    ```sh
    mkdir pykan-env/lib/python3.10/site-packages/kan/assets/img
    ```

2. Baixe os arquivos `mult_symbol.png` e `sum_symbol.png` do [repositório do Pykan](https://github.com/KindXiaoming/pykan/tree/master/kan/assets/img)

3. Copie os arquivos para o diretório criado `pykan-env/lib/python3.10/site-packages/kan/assets/img`