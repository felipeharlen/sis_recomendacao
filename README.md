# Desafio de Projeto: Sistema de Recomendação por Imagens Digitais

Projeto desenvolvido como parte do Desafio de Projeto da Formação Machine Learning Specialist da Digital Innovation One.

## Tecnologias Utilizadas

- TensorFlow
- TensorFlow Hub
- Annoy Index
- Pandas
- NumPy
- PIL (Pillow)
- Matplotlib
- tqdm
- requests

## Etapas do Projeto

### Etapa 1: Configuração do Ambiente (Windows)

1. Instale o pacote Kaggle: `pip install -q -U kaggle`
2. Crie a pasta .kaggle no diretório do usuário: `mkdir "{user_dir}/.kaggle"`
3. Copie o arquivo kaggle.json para .kaggle: `copy kaggle.json "{user_dir}/.kaggle/"`
4. Baixe o conjunto de dados: `kaggle datasets download -d paramaggarwal/fashion-product-images-small`
5. Descompacte o arquivo: `tar -xf fashion-product-images-small.zip`

### Etapa 2: Organização dos Dados

- Organiza as imagens por categoria e salva em 'fashion_data/categories'.

### Etapa 3: Transfer Learning com Bit

- Utiliza um modelo pré-treinado Bit para extrair features das imagens.

### Etapa 4: Annoy Index

- Cria um índice eficiente para busca aproximada usando Annoy Index.

### Etapa 5: Recomendação

- Realiza recomendação de produtos com base nas imagens fornecidas.

## Passo a Passo do Projeto

1. Configurar ambiente e organizar dados.
2. Treinar modelo de transfer learning e extrair features das imagens.
3. Criar índice Annoy para busca aproximada.
4. Realizar recomendação de produtos com base nas imagens fornecidas.

---

**Importante:** Este projeto faz parte do Desafio de Projeto da Formação Machine Learning Specialist da Digital Innovation One.
