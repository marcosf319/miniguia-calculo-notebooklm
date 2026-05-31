# Miniguia de Estudos: Cálculo Diferencial e Integral Aplicado à Computação com NotebookLM

## 🎯 Contexto e Objetivos

Este repositório foi desenvolvido como parte de um desafio de projeto na plataforma **IE / DIO (Digital Innovation One)**. O objetivo é explorar o uso do **Google NotebookLM** como uma ferramenta de aprendizagem ativa, utilizando Inteligência Artificial para organizar, sintetizar e fixar conceitos complexos que unem a matemática pura à ciência da computação.

### Tema Escolhido: Cálculo Diferencial e Integral e suas Aplicações Tecnológicas
A escolha do tema baseia-se na necessidade de compreender a base matemática abstrata por trás de algoritmos modernos. O objetivo deste caderno temático é consolidar os conceitos de limites, derivadas (taxas de variação) e integrais (acúmulo), mapeando como essas ferramentas gerenciam o aprendizado de redes neurais (*backpropagation*), a detecção de bordas em visão computacional, simulações científicas e a análise de complexidade de algoritmos.

---

## 📚 Curadoria de Fontes

Para alimentar o NotebookLM com rigor acadêmico e técnico, foram selecionadas e carregadas as seguintes 13 fontes (manuais, páginas da web, apostilas e teses):

1. **Análise de Complexidade de Algoritmos 1.1** (PDF - CIn UFPE)
2. **A Máquina Analítica e a pré-história dos computadores** (Página da Web - Mentalidades Matemáticas)
3. **A base matemática da Engenharia de Software** (Página da Web - Blog Universo Ateneu)
4. **A essência do cálculo diferencial e integral da Engenharia da Computação** (Página da Web)
5. **Aplicações científicas e tecnológicas da derivada e integral usando simulação computacional** (PDF - Research, Society and Development)
6. **Apostila de Cálculo I** (PDF - IME/Unicamp)
7. **Aula 11 Expositiva: Integrais para TI - Da Derivada ao Acúmulo** (PDF de Aula)
8. **Capítulo 14: Algoritmo Backpropagation Parte 1 - Grafos Computacionais e Chain Rule** (Página da Web - Deep Learning Book)
9. **Engenharia de Computação - Disciplina: Cálculo Diferencial e Integral I** (PDF - Faculdade Engenheiro Salvador Arena)
10. **Guia de Estudos em Limites, Derivadas e Integrais** (PDF de Apoio)
11. **Matemática Discreta para Computação e Informática** (Livro/PDF - Paulo Blauth Menezes)
12. **Números Fuzzy em Processamento de Imagens Digitais e Suas Aplicações na Detecção de Bordas** (Tese/PDF - USP)
13. **Tabela de Derivadas e Integrais** (PDF de Consulta Rápida)

---

## 🛠️ Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Esta seção documenta as iterações e o refinamento lógico utilizados no NotebookLM para traduzir a matemática pura em conceitos computacionais legíveis.

### Prompt Teste 1 (Abordagem Direta/Fórmula Isolada)
* **Prompt:** *"O que é a regra da cadeia?"*
* **Resultado:** A IA explicou a fórmula matemática puramente teórica ($f(g(x))'$), o que ajuda na álgebra, mas não contextualiza sua importância para quem estuda tecnologia.
* **Cicatrização/Refinamento:** O prompt foi modificado para cruzar a teoria matemática com a aplicação de Inteligência Artificial presente nas fontes.

### Prompt Teste 2 (Abordagem Interdisciplinar Avançada - Sucesso)
* **Prompt:** *"Com base nos materiais fornecidos sobre Deep Learning e Cálculo, explique como a Regra da Cadeia (Chain Rule) é aplicada em grafos computacionais durante a execução do algoritmo Backpropagation. Como o cálculo de derivadas parciais ajuda a rede a aprender?"*
* **Resultado:** Resposta fantástica. O NotebookLM utilizou o material do *Deep Learning Book* para demonstrar como o erro da rede retropropaga pelas camadas, calculando o gradiente de variação dos pesos usando a regra da cadeia de forma encadeada.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado do Assunto

* **A Derivada como Taxa de Variação e Aprendizado de IA:** No cálculo tradicional, a derivada mede a inclinação de uma curva. Na Computação Gráfica e em Inteligência Artificial, essa "inclinação" se transforma no conceito de *Gradiente*. O algoritmo *Backpropagation* utiliza derivadas sucessivas para entender como uma pequena mudança nos pesos neurais afeta o erro total do sistema, permitindo que a IA se ajuste e "aprenda".
* **A Integral como Acúmulo e Processamento Digital:** Do ponto de vista conceitual (como visto em *Integrais para TI: Da Derivada ao Acúmulo*), a integral calcula o total acumulado de um fluxo contínuo. Isso é essencial em simulações computacionais e no processamento de sinais, onde você precisa somar infinitas variações discretas para analisar dados contínuos.
* **Processamento de Imagens e Detecção de Bordas:** A variação de intensidade dos pixels de uma imagem digital pode ser mapeada por funções matemáticas. Aplicando conceitos de derivadas (junto à lógica de *Números Fuzzy*), algoritmos conseguem detectar variações bruscas de cor e luz, localizando com precisão as "bordas" de objetos em visão computacional.

### 2. Glossário de Conceitos-Chave

* **Regra da Cadeia (Chain Rule):** Técnica matemática para calcular a derivada de funções compostas. Fundamental para o cálculo de gradientes em redes neurais multicamadas.
* **Backpropagation:** Algoritmo de retropropagação de erros usado para treinar redes neurais artificiais, fortemente baseado em cálculo diferencial.
* **Complexidade de Algoritmos:** Análise do crescimento do tempo de execução ou uso de memória de um programa (geralmente descrita pela notação Big O), que se apoia em conceitos de limites matemáticos quando a entrada ($n$) tende ao infinito.
* **Lógica Fuzzy (Névoa/Difusa):** Abordagem lógica que lida com verdades parciais (valores entre 0 e 1), aplicada junto ao cálculo para tratar incertezas em processamento de imagens digitais.
* **Teorema Fundamental do Cálculo:** Princípio que garante que a integração e a diferenciação (derivação) são operações inversas, permitindo transitar livremente entre taxas de variação e acúmulos de dados.

### 3. Prompts Reutilizáveis para Revisões Futuras

Guarde estes prompts no seu NotebookLM para estudar antes das avaliações:

* 👁️ **Prompt para Visão Computacional:**
  > *"Utilizando como referência a tese da USP sobre Números Fuzzy e Processamento de Imagens, resuma em formato de tópicos como o conceito de derivada é traduzido computacionalmente para realizar a detecção de bordas em uma matriz de pixels."*
* 💻 **Prompt para Análise de Algoritmos:**
  > *"Explique a relação entre o conceito matemático de Limites (visto nas apostilas de Cálculo) e o cálculo de limites assintóticos na Análise de Complexidade de Algoritmos (Notação Big O) fornecida pelo material do CIn UFPE."*
  >
  > ## 🔗 Link do Caderno Temático
Você pode acessar o caderno de estudos interativo criado diretamente no NotebookLM através do link abaixo:
👉 [Acesse aqui o meu Notebook de Cálculo Aplicado à Computação](https://notebooklm.google.com/notebook/b0d9b189-943b-41b5-a6f4-2e99b1a91e12)

---
✨ *Projeto desenvolvido com fins educacionais para o portfólio do GitHub e plataforma DIO.*
