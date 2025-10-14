# PD-algoritmos-clusterizacao

#### Procedimentos utilizados para preparar o ambiente
Para criar o ambiente virtual:
```
conda create --name PD_algoritmos_clusterizacao python=3.12 --no-default-packages -y
```
Para ativar o ambiente virtual:
```
conda activate PD_algoritmos_clusterizacao
```
Com o requirements.in, posso gerar o requirements.txt com as dependências pinadas. Para isso, vou instalar o pip-tools e realizar o pip-compile:
```
python -m pip install pip-tool
pip-compile
```
Por fim, para instalar as dependências do requirements.txt:
```
pip install -r requirements.txt
```

