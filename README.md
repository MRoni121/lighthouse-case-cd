# 📌 Previsão de Preços de Apartamentos

Este projeto utiliza um modelo de **Machine Learning** para prever o preço de apartamentos em NYC com base em diversas variáveis. O modelo foi treinado usando um **Random Forest Regressor (RFR)** e avaliado com a métrica **R²**.

---

## 📂 Estrutura do Projeto

```
/
├── notebooks/
│   ├── LH_CD_MATEUS_RONI.ipynb  # Notebook principal com o treinamento e previsão
├── model/
│   ├── model.pkl  # Modelo treinado salvo
├── data/
│   ├── dataset.csv  # Conjunto de dados original
│   ├── incremented_dataset.csv  # Conjunto de dados incrementado
│   ├── Points_of_Interest.csv  # Pontos de interesse de NYC
├── requirements.txt  # Dependências do projeto
└── README.md  # Documentação
```

---

## 🚀 Instalação

1. **Clone este repositório**

```bash
git clone https://github.com/MRoni121/lighthouse-case-cd.git
cd lighthouse-case-cd
```

2. **Crie e ative um ambiente virtual (opcional, mas recomendado)**

```bash
# No Windows
python -m venv venv
venv\Scripts\activate

# No Linux/Mac
python3 -m venv venv
source venv/bin/activate
```

3. **Instale as dependências**

```bash
pip install -r requirements.txt
```

---

## 📊 Execução do Projeto

Para rodar o projeto, basta abrir o notebook no ambiente desejado e executar os códigos na ordem:

### ✅ **Opção 1: Rodando no VS Code ou Localmente**

1. **Abra o projeto no VS Code ou outro editor compatível**

2. **Abra o arquivo `notebooks/LH_CD_MATEUS_RONI.ipynb`**

3. **Execute todas as células do notebook** na ordem

### ✅ **Opção 2: Rodando no Google Colab**

1. **Faça upload do projeto para o Google Drive**
2. **Abra o Google Colab e carregue o arquivo `notebooks/LH_CD_MATEUS_RONI.ipynb`**
3. **Execute todas as células do notebook** na ordem

O modelo será treinado e salvo automaticamente.

---

## 🔍 Testando Novos Dados

Para prever o preço de um novo apartamento, faça o tratamento de dados mostrado na seção **"Prevendo o preço do apartamento do case"** no notebook.

- Substitua os dados na variável **`apartamento_do_case`** pelos valores do novo apartamento.
- Execute as células correspondentes para gerar a previsão.

---

# 📹 Vídeo de Entrega

O vídeo com a explicação do desenvolvimento das entregas pode ser encontrado em https://drive.google.com/file/d/1J12QZ_eS-FPvv4MSH-NcsoY1VYPFWqV1/view?usp=sharing
