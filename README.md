# Desafio: Azure Speech Studio & Language Studio

## 🎯 Objetivo

Este projeto tem como objetivo praticar e aprofundar o uso das ferramentas **Azure Speech Studio** e **Language Studio**, com foco na análise de **fala** e **linguagem natural**. A proposta é documentar os testes e experiências realizados com as ferramentas, destacando aprendizados, dificuldades e aplicações práticas.

---

## 📌 Conteúdo

- [x] Introdução às ferramentas Azure
- [x] Transcrição de fala com Speech Studio
- [x] Análise de sentimentos com Language Studio
- [x] Testes e observações práticas
- [x] Capturas de tela (/images)
- [x] Documentação técnica da experiência

---

## 🧪 Experimentos Realizados

### 🔊 Azure Speech Studio

- **Objetivo:** Testar transcrição de áudio para texto.
- **Ferramentas utilizadas:** Speech-to-Text
- **Resultado:** A ferramenta conseguiu transcrever falas com alta precisão, mesmo em português brasileiro.
- **Observações:**
  - A pontuação nem sempre foi bem colocada.
  - Vozes com ruído de fundo diminuem a qualidade da transcrição.

### 💬 Azure Language Studio

- **Objetivo:** Analisar o sentimento de diferentes textos.
- **Ferramentas utilizadas:** Sentiment Analysis, Key Phrase Extraction.
- **Resultado:** Identificou corretamente sentimentos positivos e negativos.
- **Observações:**
  - Quando há ambiguidade, o resultado tende a ser "neutro".

---

## 📝 Anotações Técnicas

- Os testes foram feitos com textos e áudios curtos.
- O Speech Studio possui interface intuitiva, mas exige boa conexão com a internet.
- A API do Language Studio pode ser integrada via REST ou SDK (Python/C#/Java).

---


