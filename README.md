#  Projeto de Precificação de Imóveis
Este projeto foi desenvolvido como parte do processo seletivo do programa Lighthouse, da empresa Indicium. O objetivo é explorar dados de imóveis e aplicar técnicas de ciência de dados para criar modelos de machine learning capazes de prever preços de aluguel.

## 🛠️ Requisitos
Antes de executar o projeto, certifique-se de que você tenha o Python 3.8 ou superior instalado.

## Instalação dos Pacotes
Para instalar todas as bibliotecas necessárias com suas respectivas versões, siga os passos abaixo:

Clone este repositório:

git clone https://github.com/seu_usuario/LH_CD_LuccaPinilla_v2.git
cd seu_repositorio

Crie um ambiente virtual (opcional, mas recomendado):
python -m venv venv
source venv/bin/activate  # Para Linux/Mac
.\venv\Scripts\activate  # Para Windows

Instale os pacotes listados no arquivo requisitos.txt:
pip install -r requisitos.txt

## 🚀 Como Executar o Projeto
Verifique se está no diretório do projeto (onde há o dataset usado) e com o ambiente virtual ativado (caso tenha criado um).

Execute o arquivo principal do projeto (LH_CD_LuccaPinilla.ipynb) em um ambiente compatível, como o Google Colab ou o Jupyter Notebook:
jupyter notebook LH_CD_LuccaPinilla.ipynb

Siga os passos descritos no notebook para carregar os dados, treinar os modelos e avaliar a performance dos algoritmos.

## 🧩 Estrutura do Projeto
LH_CD_LuccaPinilla.ipynb: Notebook principal com o código de todas as etapas do projeto.

requisitos.txt: Lista de pacotes necessários para a execução do projeto e suas versões.

teste_indicium_precificacao.csv: Dataset contendo os dados dos apartamentos.

LH_CD_LuccaPinilla-EDA.pdf: Arquivo em pdf mostrando a análise exploratória dos dados.

lgbm_model.pkl: Modelo desenvolvido em LightGBM com o melhor desempenho.

## 📚 Observações
Este projeto foi elaborado exclusivamente para fins de avaliação técnica.
