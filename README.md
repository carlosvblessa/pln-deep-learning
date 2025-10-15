# Deep Learning com PyTorch (Alura)

Este repositório reúne os notebooks utilizados na formação **Deep learning com Pytorch** da Alura. O curso é voltado a pessoas que já possuem base em data science e machine learning e desejam mergulhar em redes neurais profundas, passando por construção, treinamento e aplicações em visão e processamento de texto.

## Estrutura dos notebooks

- `02-TensoresSintaxeDoPytorch.ipynb`: explora a sintaxe fundamental do PyTorch, criação de tensores, conversões com NumPy, indexação, operações básicas e uso de GPU.
- `03-Perceptron-Camada-Linear.ipynb`: apresenta a camada `nn.Linear`, fluxo de forward, manipulação de pesos/bias e visualização em 3D do hiperplano aprendido.
- `03-Perceptron-Classificacao-Linear.ipynb`: revisita a classificação linear, estuda a equação da reta, gera dados sintéticos com `sklearn` e analisa o comportamento do perceptron.
- `04-FuncoesDeAtivacao.ipynb`: discute o papel das funções de ativação, mostra exemplos práticos e avalia como alteram a fronteira de decisão do modelo.
- `05-RedesNeurais-Arquitetura.ipynb`: constrói arquiteturas com `nn.Sequential` e classes que herdam de `nn.Module`, realiza o forward completo, move modelos para GPU e usa `torchsummary`.

## Como executar

1. Crie e ative um ambiente virtual (opcional, mas recomendado).
2. Instale as dependências com `pip install -r requirements.txt`.
3. Inicie o Jupyter (`jupyter notebook` ou `jupyter lab`) e abra os notebooks na ordem sugerida.

## Requisitos

As dependências principais estão listadas em `requirements.txt`:

- `torch`
- `torchsummary`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `jupyter`

Com tudo instalado você poderá reproduzir os exemplos, ajustar hiperparâmetros e experimentar suas próprias arquiteturas em PyTorch.
