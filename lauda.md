# Trabalho Prático 2 — Mapas Auto-Organizáveis (SOM)

## 📌 Objetivos

Neste segundo trabalho prático, você poderá dar continuidade ao trabalho anterior, preferencialmente utilizando o mesmo dataset escolhido para o treinamento com MLP. O objetivo é explorar agrupamentos e padrões utilizando a técnica de Mapas Auto-Organizáveis (SOM).

---

## 📌 Equipes

Preferencialmente, as mesmas equipes do primeiro trabalho.

---

## 📌 Etapas

### 1️⃣ Reaproveitamento e Justificativa do Dataset

Reutilize o mesmo dataset do primeiro trabalho. Caso realize modificações no pré-processamento (remoção de atributos, nova normalização, etc.), explique e justifique.

### 2️⃣ Treinamento e Configuração do SOM

Configure os hiperparâmetros do SOM para melhor desempenho: tamanho da malha, número de épocas, sigma e learning rate para obtenção de boas métricas.

Opcionalmente, pode-se usar o Gridsearch para explorar configurações distintas.

### 3️⃣ Avaliação e Visualização

Calcule métricas como **Quantization Error** e **Topographic Error**. Explique o que essas métricas indicam sobre o seu treinamento.

Produza visualizações como:

- U-Matrix
- Component Planes
- Scatterplots por pares de atributos (se forem muitos, pode ser uma seleção dos mais relevantes)
- Hit Maps (mapa de ativação dos neurônios)

Opcionalmente, a animação mostrando a evolução dos neurônios durante o treinamento.

### 4️⃣ Análise e Interpretação dos Resultados

- Analise os agrupamentos encontrados. O que as visualizações indicam sobre o dataset?
- Comente a coerência dos agrupamentos identificados pelo SOM com o problema original do dataset (classificação).
- Compare brevemente os resultados obtidos com aqueles do primeiro trabalho (MLP).

---

## 📌 Entrega da Atividade

Entregar e explicar o notebook contendo:

- ✅ Dataset reutilizado e explicação sobre qualquer modificação feita no pré-processamento.
- ✅ Código do treinamento do SOM com hiperparâmetros.
- ✅ Todas as visualizações claramente identificadas e analisadas.
- ✅ Uma discussão dos resultados encontrados.
- ✅ Comparação resumida com a etapa anterior (MLP).

---

> ⚠️ **IMPORTANTE:** Seguindo os princípios institucionais quanto à transparência no uso da IA Generativa e respeitando o regulamento para uso acadêmico de IA disponibilizado, o notebook deverá conter, de forma clara e explícita, uma seção inicial com:
>
> - Os nomes dos integrantes da equipe
> - A declaração de uso de IA Generativa no trabalho (caso tenha sido utilizada), contendo no mínimo:
>   - A ferramenta utilizada
>   - A finalidade do uso
>   - A extensão aproximada da contribuição da IA Generativa
>   - As medidas adotadas para validação do conteúdo
