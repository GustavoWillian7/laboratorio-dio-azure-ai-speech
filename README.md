# 🧪 Laboratório DIO: Análise de Fala e Linguagem utilizando Azure AI

## 📝 Descrição

Este repositório documenta minha experiência utilizando as ferramentas de IA Microsoft Azure: o **Speech Studio** e o **Language Studio**. A proposta consistiu em colocar em prática os fundamentos de análise da fala e de processamento de linguagem natural (NLP), ampliando a compreensão sobre os recursos da nuvem Azure na construção de soluções inteligentes.

---

## 🗣️ Análise de Fala com Azure Speech Studio

O Speech Studio é uma ferramenta robusta que possibilita experimentar e aplicar recursos baseados em voz. Neste laboratório, foquei especialmente na funcionalidade de transcrição de fala para texto (Speech-to-Text).

### ⏱️ 1. Transcrição em Tempo Real

Logo de cara fiquei impressionado com a velocidade da transição em tempo real, ao concluir de falar uma palavras, ela já estava transcrita, com uma latência baixíssima.

### 🎧 2. Transcrição de Arquivo de Áudio

Realizei também o upload de um arquivo para transição, e assim como na etapa anterior, o resultado foi muito preciso e muito veloz, com certeza irei utilizar essa ferramenta para apoiar meus estudos em Línguas.

---

## 💬 Análise de Linguagem com Language Studio

O Language Studio disponibiliza um conjunto avançado de ferramentas voltadas para a compreensão e interpretação automática de textos. Durante este experimento, explorei três funcionalidades distintas que demonstram o potencial da plataforma.

### ❤️‍🔥 1. Análise de Sentimento

Avaliei a capacidade do serviço em identificar emoções expressas em avaliações de produtos.

* **Texto analisado:** "O atendimento foi excelente, porém o processo de entrega demorou mais do que o esperado."
* **Resultado:** A ferramenta reconheceu corretamente o tom como "misto", atribuindo alta confiança à parte positiva relacionada ao atendimento e menor à entrega, que foi apontada como negativa.
* **Observação:** Ideal para análise automatizada de avaliações de clientes, permitindo às empresas entender pontos fortes e áreas que exigem melhorias.

### 🧠 2. Identificação de Entidades e Tópicos em Notícias

Apliquei o modelo a um trecho retirado de uma notícia sobre tecnologia, com o objetivo de mapear entidades relevantes e temas centrais.

* **Texto analisado:** "A Microsoft anunciou uma nova parceria com a OpenAI para expandir os serviços de inteligência artificial no Azure."
* **Resultado:** O sistema reconheceu corretamente entidades como "Microsoft" (Organização), "OpenAI" (Organização) e "Azure" (Produto), além de destacar frases-chave como "parceria", "inteligência artificial" e "serviços".
* **Observação:** Excelente recurso para aplicações em curadoria de conteúdo, mecanismos de busca e geração de resumos inteligentes.

### 🗂️ 3. Classificação de Texto por Categoria

Testei a capacidade do modelo em categorizar automaticamente trechos de texto em tópicos gerais, como tecnologia, saúde, educação, etc.

* **Texto analisado:** "Pesquisadores desenvolvem um novo algoritmo capaz de detectar doenças respiratórias com base em padrões de voz."
* **Resultado:** O modelo classificou o texto na categoria "Saúde/Tecnologia" com alta precisão.
* **Observação:** Ferramenta útil para triagem de grandes volumes de conteúdo textual, como artigos, e-mails ou relatórios, facilitando a organização por temas.

---

## ✅ Conclusão

Esta atividade prática ajudou a entender melhor os serviços disponibilizados na Azure AI. As ferramentas são fáceis de usar, bem explicadas e muito eficientes, permitindo que desenvolvedores de todos os níveis criem soluções avançadas. Poder testar e ver os resultados direto no Studio torna o desenvolvimento e a validação de ideias muito mais rápidos.

## 🔗 Recursos Úteis

- **Documentações Oficiais:**
  - [Explore Speech Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)
  - [Analyze text with Language Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)
