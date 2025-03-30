# 🚀 Análise de Sentimento Econômico com Machine Learning

Este repositório apresenta um projeto de Business Analytics e Machine Learning focado na análise de sentimento econômico no Brasil. Foi utilizado um conjunto de dados fictício contendo frases rotuladas sobre a economia brasileira. Utiliza técnicas avançadas de aprendizado de máquina para classificar textos sobre economia em categorias de sentimento positivo, neutro ou negativo, proporcionando insights valiosos para decisões econômicas e financeiras.

---

## 📊 Visão Geral do Projeto

O projeto é desenvolvido com as seguintes etapas principais:

1. **Ajuste fino de modelos de Machine Learning**
2. **Tokenização dos textos**
3. **Avaliação de desempenho dos modelos**
4. **Deploy em aplicação web com visualizações interativas e histórico de consultas**

---

## 📁 Estrutura do Projeto

```
.
├── pipeline_ml_sentimento.ipynb    # Notebook com ajuste fino, tokenização e avaliação
├── app_web_sentimento.py           # Aplicação web para deploy com Streamlit
├── requirements.txt                # Dependências do projeto
├── dataset.csv                     # Dataset fictício utilizado
├── modelo_final/                   # Pasta com modelo treinado (BERT)
└── README.md
```

---

## ⚙️ Tecnologias Utilizadas

- Python **3.11** (recomendado)
- Streamlit
- PyTorch
- Transformers (BERT)
- Pandas
- NumPy
- Matplotlib
- Plotly
- WordCloud
- Scikit-Learn

Consulte `requirements.txt` para todas as versões específicas utilizadas.

---

## 💻 Como Executar o Projeto Localmente

### 🔁 1. Clone o repositório

```bash
git clone https://github.com/ede1000son/sentimento-economico-brasil-ml
cd sentimento-economico-brasil-ml
```

### 📦 2. Crie e ative um ambiente virtual

```bash
python3.11 -m venv .venv
source .venv/bin/activate  # Linux/macOS
.venv\Scripts\activate     # Windows
```

### 📥 3. Instale as dependências

```bash
pip install -r requirements.txt
```

### ▶️ 4. Execute o notebook (pipeline de ML)

```bash
jupyter notebook pipeline_ml_sentimento.ipynb
```

### 🚀 5. Deploy da aplicação web com Streamlit

```bash
streamlit run app_web_sentimento.py
```

Abra a aplicação web no endereço exibido pelo Streamlit (geralmente `http://localhost:8501`).

---

## 🧪 Avaliação dos Modelos

O notebook realiza a avaliação detalhada do desempenho dos modelos ajustados. Os resultados incluem métricas relevantes para análise de sentimento, como precisão, recall e F1-score.

---

## 🔮 Funcionalidades da Aplicação Web

- **Análise em tempo real:** Classifica o sentimento do texto inserido pelo usuário.
- **Gráficos Interativos:** Gauge de confiança e barras de probabilidades para cada sentimento.
- **Histórico de Consultas:** Registro das últimas análises realizadas.
- **Visualização:** Nuvem de palavras baseada nos textos analisados.

---

## 📈 Possíveis Pontos de Melhorias

- Aumentar o dataset: Coletar mais exemplos para treinamento
- Balanceamento de classes: Usar técnicas como oversampling/undersampling
- Ajuste de hiperparâmetros: Testar diferentes learning rates, batch sizes
- Regularização: Adicionar dropout ou weight decay mais forte
- Fine-tuning mais longo: Aumentar número de épocas (com early stopping)
- Experimentar outros modelos: Testar BERT em português (ex: 'neuralmind/bert-base-portuguese-cased')

---

## 👩‍💻 Autor

**Edemilson Fernandes Vieira**\
Analista de Dados especialista em Business Analytics e Machine Learning.

---

## 📄 Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

