# Guia inicial de estudos

## Fichamento
É um registro organizado de uma leitura para recuperar ideias e fontes. Leia o texto inteiro; identifique autor, título, data e endereço; resuma com suas palavras; anote conceitos e dúvidas; relacione ao projeto. Diferencie citação literal, resumo e comentário próprio.
Use [o modelo](../templates/fichamento.md). Quando um blog não apresenta experimento, registre “não descrito” em metodologia e resultados, sem inventar.

## Google Acadêmico
Buscador de literatura acadêmica: artigos, teses e outros materiais. Pesquise “detecção de equipamentos de proteção individual” e “personal protective equipment detection”. Registre consulta, data e critérios; leia o original; verifique autores, veículo, método, dados e limitações.
Filtros por ano, “Citado por”, “Artigos relacionados” e “Todas as versões” ajudam a explorar a literatura. “Citar” oferece exportação bibliográfica; confira os metadados.
Fonte consultada: [ajuda oficial](https://scholar.google.com/intl/pt-BR/scholar/help.html), acesso em 10/10/2026.
Atividade: selecionar três trabalhos pertinentes e preencher o [registro de buscas](../../references/registro-de-buscas.md).

## Inteligência Artificial
Área que estuda sistemas capazes de realizar tarefas como reconhecer padrões, prever e tomar decisões segundo objetivos. Exemplos: reconhecimento de fala, recomendação, análise de imagens e detecção de objetos.
No projeto, a aplicação proposta é localizar EPIs em imagens.

## Algoritmo
Sequência definida de passos para resolver um problema. Exemplo conceitual: receber imagem → preparar entrada → executar modelo → filtrar previsões → apresentar caixas e classes. Nem todo algoritmo usa IA.

## Dados e informação
Dados são registros: pixels, rótulos, medidas. Informação resulta de interpretar esses dados em um contexto. Uma previsão “capacete, confiança 0,82” é uma saída do modelo; não comprova ausência de risco.

## Machine Learning
Aprendizado de máquina é uma área de IA em que modelos ajustam parâmetros a partir de dados. Generalizar significa produzir respostas úteis para novos exemplos, além dos usados no treino.

## Aprendizado supervisionado
Treino com exemplos e respostas conhecidas. Em detecção, as anotações podem indicar classes e caixas dos objetos.
Classificação atribui uma classe a uma entrada; detecção também localiza objetos. Classificar uma imagem como “com capacete” não identifica automaticamente quem o utiliza.

## Treino e inferência
Treino ajusta parâmetros com dados. Inferência usa os parâmetros já aprendidos para gerar previsões em novas entradas.
Validação orienta escolhas de modelo; teste separado avalia o resultado final. Evite imagens quase iguais ou quadros do mesmo vídeo em divisões diferentes.

## Resumo de IA
IA inclui métodos para tarefas de reconhecimento, previsão e decisão. ML aprende padrões a partir de dados. Visão computacional analisa imagens e vídeos e pode usar ML. Um detector de EPIs deve ser avaliado com exemplos representativos, métricas e análise dos erros.
Este é um exemplo de resumo; escreva sua própria compreensão e cite fontes estudadas.

## Exercícios
1. Escreva um algoritmo de cinco passos para a análise de uma imagem.
2. Dê dois exemplos de dados e da informação que pode ser obtida.
3. Compare classificação de imagens e detecção de objetos.
4. Explique por que o conjunto de teste precisa ser separado.
5. Cite duas situações em que um detector pode falhar.

## Fontes a estudar
Selecionar artigos primários e documentação técnica; registrar referências em references antes de usar afirmações no relatório.
