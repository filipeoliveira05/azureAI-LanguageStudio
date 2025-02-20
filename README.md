# Análise de Sentimentos no Language Studio do Azure AI

## 📌 Descrição  
Este repositório contém um projeto de **Análise de Sentimentos** utilizando o **Language Studio do Azure AI**. O objetivo é analisar emoções em textos, identificando se são positivos, negativos ou neutros, de modo a demonstrar a capacidade dos serviços cognitivos do Azure.

## 📂 Estrutura do Repositório  
```
📁 inputs/   -> Contém as frases utilizadas para a análise de sentimentos
📄 readme.md -> Documentação do processo e insights
```

## 🚀 Passo a Passo do Processo  

### 1️⃣ Configuração do Ambiente  
1. Criar um recurso **Cognitive Services** no **Azure Portal**.  
2. Ativar o serviço de **Language Service**.  
3. Obter as **chaves de acesso** e o **endpoint** para uso nas requisições.  

### 2️⃣ Análise de Sentimentos  
- Utilizamos o **Language Studio** do Azure para analisar o sentimento das frases.  
- O modelo identifica o tom do texto, classificando-o como:
  - **Positivo** → Ex.: "Este produto é incrível!"  
  - **Negativo** → Ex.: "O atendimento foi péssimo."  
  - **Neutro** → Ex.: "O evento ocorrerá amanhã."  

### 3️⃣ Salvando os Resultados  
- As frases analisadas são armazenadas na pasta `inputs/`.  
- Os resultados da análise de sentimentos podem ser documentados diretamente no `README.md` ou em futuros arquivos de output.

## 📊 Insights e Possibilidades  
✅ **Análise de Feedbacks** → Compreensão de opiniões em avaliações de produtos.  
✅ **Monitoramento de Redes Sociais** → Identificação de crises e oportunidades a partir de comentários.  
✅ **Atendimento ao Cliente** → Análise de sentimentos em interações para melhoria do serviço.  

## 🔗 Links Úteis  
- [Lab: Análise de Texto com Language Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)  
- [Explorar Speech Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)  
