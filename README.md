# mining-classifiers

## Steps to reproduce this environment

0. Python v3.10.6
1. Clone o repositório:
```
git clone this-proj
```
2. Crie uma virtualenv e ative o ambiente para instalar pacotes locais:
```
python3 -m venv /PATH-TO-pyjail/
source ./pyjail/bin/activate
```

3. Atualize o pip e instale os pacotes necessários: pandas (carregará o dataset), numpy (para manipular matrizes), matplotlib e seaborn (visualização de dados) e sklearn (construção de classificadores).
> PS: O jupyter pode precisar de algumas dependências de sistema para executar, como por exemplo o caso do __libzmq__.

```
pip3 install --upgrade pip
pip3 install numpy pandas matplotlib seaborn sklearn jupyter
```

 4. Na raíz do projeto, execute o notebook e acesse a URL com o token de endereço no browser ().:
```
jupyter notebook
```





















