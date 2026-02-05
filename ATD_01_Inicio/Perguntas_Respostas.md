
# 🧠 Estudos Iniciais: Machine Learning

## 📋 Perguntas e Respostas

### 1. Explique, com suas palavras, o que é machine learning?

Para mim, **Machine Learning** é uma forma de ensinar o computador a aprender padrões através de dados. Em vez de escrever mil linhas de `if/else`, podemos "treina" um algoritmo com exemplos, e ele mesmo descobre como tomar decisões ou fazer previsões para novos dados que ele nunca viu antes. Entretanto, nem sempre o algoritmo entende os dados ou se sai bem, assim, é necessário entender sobre pré-processamaento e outras técnicas para aumetar a precisão e limpeza dos dados.

### 2. Explique o conceito de conjunto de treinamento, conjunto de validação e conjunto de teste.

Em analogia a um estudo para uma importante prova.

* **Conjunto de Treinamento:** São os exercícios que fazemos para aprender a matéria. O modelo usa esses dados para entender os padrões.
* **Conjunto de Validação:** É como um "simulado". Usamos ele durante o treino para ajustar as configurações do modelo e ver se ele está indo pelo caminho certo.
* **Conjunto de Teste:** É a prova final. São dados que o modelo nunca viu durante o treino. Serve para dar o veredito real de quão bom o modelo é na prática.

### 3. Explique como você lidaria com dados ausentes em um conjunto de dados de treinamento.

Dados ausentes são normais em Datasets reias, portanto, algumas técnicas podem ser usadas:

* **Exclusão:** Se forem poucas linhas com dados faltando, eu simplesmente as removeria.
* **Imputação Simples:** Preencheria os espaços vazios com a **média**, **mediana** ou a **moda** daquela coluna.
* **Preenchimento Constante:** Em alguns casos, faz sentido colocar um valor padrão como "Desconhecido" ou "0".

### 4. O que é uma matriz de confusão e como ela é usada para avaliar o desempenho?

A **Matriz de Confusão** é uma tabela que mostra onde o modelo acertou e onde ele se "confundiu". Ela cruza os valores reais com as previsões do modelo.
Com ela, conseguimos ver quatro métricas principais:

Considerando contexto de detecção de Câncer.

1. **Verdadeiros Positivos:** Acertou quem realmente possuia Câncer.
2. **Verdadeiros Negativos:** Acertou quem não tinha a doença.
3. **Falsos Positivos:** Disse que tinha, mas não era o Câncer.
4. **Falsos Negativos:** Disse que não era Câncer, mas era.

### 5. Em quais áreas você acha mais interessante aplicar algoritmos de machine learning?

Como estudante, vejo potencial em tudo, mas duas áreas me chamam muito a atenção:

* **Saúde:** Para ajudar médicos a detectarem doenças em exames de imagem com mais precisão e rapidez.
* **Manufatura:** Manutenção preditiva, que é basicamente o modelo avisar que uma máquina vai quebrar antes mesmo dela parar, evitando prejuízos na fábrica.
