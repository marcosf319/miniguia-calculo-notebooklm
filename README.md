# Miniguia de Estudos: Fundamentos de Derivadas e Integrais com NotebookLM

## 🎯 Contexto e Objetivos

Este repositório foi desenvolvido como parte de um desafio de projeto na plataforma **DIO (Digital Innovation One)**. O objetivo é utilizar o **Google NotebookLM** como uma ferramenta de aprendizagem ativa, aplicando Inteligência Artificial para organizar, sintetizar e fixar conceitos complexos de disciplinas universitárias de exatas.

### Tema Escolhido: Cálculo Diferencial e Integral (Derivadas e Integrais)
A escolha do tema se justifica pela sua importância central em cursos de tecnologia, computação e engenharia. O objetivo deste caderno temático é consolidar a interpretação geométrica e matemática de derivadas (taxas de variação) e integrais (acúmulo e área sob a curva), além de mapear suas aplicações práticas em algoritmos e otimização de sistemas.

---

## 📚 Curadoria de Fontes

Para alimentar o NotebookLM com base acadêmica sólida, foram selecionadas as seguintes fontes abertas e materiais didáticos:

1. **Notas de Aula de Cálculo I - Limites e Derivadas** (PDF Acadêmico) - Foco na definição formal de limite e na introdução geométrica da derivada como a reta tangente.
2. **O Teorema Fundamental do Cálculo e Integração** (Artigo/Capítulo de Livro Aberto) - Exploração da relação inversa entre a diferenciação e a integração.
3. **Aplicações de Cálculo na Computação** (Whitepaper/Artigo) - Exemplos práticos de como derivadas são usadas em Machine Learning (Gradient Descent) e integrais no processamento de sinais digitais.

---

## 🛠️ Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Esta seção documenta o processo de refinamento das perguntas feitas ao NotebookLM para extrair explicações didáticas e evitar respostas puramente mecânicas ou abstratas demais.

### Prompt Teste 1 (Abordagem Direta/Superficial)
* **Prompt:** *"Como faz uma integral?"*
* **Resultado:** A IA trouxe apenas regras de integração isoladas (como a regra da potência) sem explicar o conceito visual ou o motivo matemático por trás da constante de integração ($C$).
* **Cicatrização/Refinamento:** O prompt foi reestruturado para exigir uma explicação conceitual antes da aplicação de fórmulas.

### Prompt Teste 2 (Abordagem Pedagógica e Contextualizada - Sucesso)
* **Prompt:** *"Com base nos materiais de Cálculo fornecidos, explique a interpretação geométrica de uma integral definida como a soma de Riemann. Use uma analogia simples e descreva passo a passo por que dividimos a área sob a curva em retângulos infinitamente pequenos."*
* **Resultado:** A resposta foi excelente. A IA utilizou a analogia de fatiar um pão para medir seu volume total e explicou o conceito de limite quando a base do retângulo tende a zero ($dx$).

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado do Assunto

* **O que é a Derivada?** Graficamente, a derivada de uma função em um ponto é a inclinação da reta tangente a esse ponto. Fisicamente, ela representa uma **taxa de variação instantânea** (como a velocidade instantânea de um objeto em um determinado segundo).
* **O que é a Integral?** Geometricamente, a integral definida representa a **área sob a curva** de uma função em um gráfico. Ela funciona como um operador de acúmulo (a partir da velocidade, podemos integrar para descobrir a distância total percorrida).
* **O Teorema Fundamental do Cálculo:** É a ponte que une os dois mundos. Ele prova que a diferenciação e a integração são operações inversas. Se você integrar uma função e depois derivar o resultado, você volta para a função original.

### 2. Glossário de Conceitos-Chave

* **Taxa de Variação:** A velocidade com que uma variável muda em relação a outra.
* **Reta Tangente:** Uma reta que toca uma curva em apenas um ponto local, representando a direção da curva naquele instante.
* **Soma de Riemann:** Um método para aproximar a área sob uma curva somando as áreas de múltiplos retângulos sob o gráfico.
* **Integral Indefinida (Antiderivada):** O processo de encontrar a função original que gerou a derivada, incluindo sempre a constante de integração $+ C$.
* **Diferencial ($dx$):** Representa uma mudança infinitamente pequena na variável independente $x$.

### 3. Prompts Reutilizáveis para Revisões Futuras

Use estes prompts no seu NotebookLM para estudar antes das provas da faculdade:

* 🧠 **Prompt para Simplificar Teoremas:**
  > *"Explicite o Teorema Fundamental do Cálculo de uma forma que um estudante do ensino médio consiga entender, utilizando uma analogia com o velocímetro e o hodômetro de um carro."*
* ✍️ **Prompt para Passo a Passo de Exercícios:**
  > *"Identifique no texto fornecido quais são os passos recomendados para resolver uma integral por substituição (U-substitution) e monte um checklist mental para eu usar durante a resolução de problemas."*

---
✨ *Projeto desenvolvido com fins educacionais para o portfólio do GitHub e plataforma DIO.*
