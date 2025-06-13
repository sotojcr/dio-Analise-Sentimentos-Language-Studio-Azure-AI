# Desafio Analise de Sentimentos com Language Studio no Azure AI

O objetivo deste desafio é realizar uma análise de sentimento  de um texto utilizando o `Azure AI`.



## Pré-requisitos:

- Ter um cadastro na [Azure](https://azure.microsoft.com) 

# Análise de Sentimentos com Azure Language Studio – Passo a Passo

## ✅ Passo 1: Acesse o Azure Language Studio
- Acesse: [https://language.azure.com](https://language.azure.com)
- Faça login com sua conta da Azure.
- Caso não tenha nenhum recurso disponível, crie um novo recurso.

## ✅ Passo 2: Selecione “Análise de sentimentos”
- No menu lateral, clique em **"Análise de texto"**.
- Depois selecione **"Análise de sentimentos"**.

## ✅ Passo 3: Configure o recurso do Azure
- Clique em **“Configurar recurso do Azure”**.
- Selecione um recurso do tipo **Azure AI Language** já criado em sua conta.
- Clique em **“Aplicar”**.

## ✅ Passo 4: Insira os textos a serem analisados
- No campo **“Text input”**, insira o(s) comentário(s) ou texto(s) desejado(s).

Exemplo:

````
O produto chegou rápido, mas veio com defeito.
Excelente atendimento e entrega no prazo.
````

## ✅ Passo 5: Defina o idioma
- Defina o idioma como **“pt”** (Português) no campo de idioma.

> A detecção automática pode funcionar, mas é mais confiável definir o idioma explicitamente.

---

## ✅ Passo 6: Execute a análise
- Clique em **“Executar”** (Run).
- Aguarde o processamento.

---

## ✅ Passo 7: Veja e interprete os resultados
- A plataforma exibirá:
  - **Sentimento geral** de cada texto (positivo / negativo / neutro)
  - **Pontuação de confiança** para cada classe
  - **Sentimentos por frase**, quando aplicável
 
Exemplo de saída:

````
Texto: Excelente atendimento e entrega no prazo.
Sentimento: positive
Positivo: 98%
Negativo: 1%
Neutro: 1%

````
