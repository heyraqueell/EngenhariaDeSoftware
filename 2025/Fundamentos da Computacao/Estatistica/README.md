## **Conceitos Fundamentais**



- **Estatística:** Ramo da matemática que coleta, analisa, interpreta e apresenta dados numéricos.
- **Métodos Estatísticos:** Formas organizadas de tratamento de dados.
- **População:** Conjunto total de elementos a serem observados.
- **Amostra:** Subconjunto da população.
- **Medidas de Posição (Tendência Central):** Valores que descrevem o centro dos dados (média, moda, mediana).
- **Medidas de Dispersão:** Valores que indicam a variabilidade dos dados (variância, desvio padrão).

## **Média**



- **Definição:** Valor que representa a tendência central de um conjunto de dados.
- **Dados não agrupados:**
    - Fórmula:
        
        X―=(Σxi)/n
        
    - Exemplo: Preço médio de discos rígidos externos.
- **Dados agrupados (Distribuição de Frequência):**
    - Fórmula:
        
        X―=(Σxi∗fi)/n
        
    - Conhecida como média ponderada.
    - Exemplo: Valor médio do frete de mercadorias.
- **Dados agrupados por classe:**
    - Usa o ponto médio de cada intervalo .
        
        pmi
        
    - Fórmula:
        
        X―=(Σpmi∗fi)/n
        
    - Exemplo: Tempo médio de uso de um aplicativo.

## **Moda**



- **Definição:** Valor que aparece com maior frequência em um conjunto de dados.
- Pode haver uma ou mais modas, ou nenhuma (amodal).
- **Exemplo:** Moda dos preços de discos rígidos.
- **Dados agrupados:**
    - Identificar o valor com a maior frequência.
    - Exemplo: Moda dos valores de frete.
- **Dados agrupados por classe:**
    - Fórmula:
        
        Mo=Li+((fpost∗A)/(fant+fpost))
        
    - Li: Limite inferior da classe modal.
    - fpost: Frequência da classe posterior à modal.
    - fant: Frequência da classe anterior à modal.
    - A: Amplitude da classe modal.
    - Exemplo: Moda do tempo de permanência em um aplicativo.

## **Mediana**



- **Definição:** Valor que ocupa a posição central em um conjunto de dados ordenados (rol).
- Se o número de dados for ímpar, é o valor central.
- Se o número de dados for par, é a média dos dois valores centrais.
- **Exemplo:** Mediana dos preços de discos rígidos.
- **Dados agrupados:**
    - Calcular a frequência acumulada ().
        
        fa
        
    - Identificar a posição central ().
        
        n/2
        
    - Exemplo: Mediana dos valores de frete.
- **Dados agrupados por classe:**
    - Fórmula:
        
        Md=Li+(((n/2−Σfant)∗A)/fMd)
        
    - Li: Limite inferior da classe mediana.
    - n: Número total de elementos.
    - Σfant: Frequência acumulada da classe anterior à mediana.
    - fMd: Frequência da classe mediana.
    - A: Amplitude da classe mediana.
    - Exemplo: Mediana do tempo de permanência em um aplicativo.

## **Variância**



- **Definição:** Média dos quadrados dos desvios em relação à média.
- **Dados não agrupados:**
    - População:
        
        σ2=Σ(xi−X―)2/n
        
    - Amostra:
        
        σ2=Σ(xi−X―)2/(n−1)
        
    - Exemplo: Variância dos preços de discos rígidos.
- **Dados agrupados:**
    - População:
        
        σ2=(Σ(xi−X―)2∗fi)/n
        
    - Amostra:
        
        σ2=(Σ(xi−X―)2∗fi)/(n−1)
        
    - Exemplo: Variância dos valores de frete.
- **Dados agrupados por classe:**
    - População:
        
        σ2=(Σ(pmi−X―)2∗fi)/n
        
    - Amostra:
        
        σ2=(Σ(pmi−X―)2∗fi)/(n−1)
        
    - Exemplo: Variância do tempo de permanência em um aplicativo.

## **Desvio Padrão**



- **Definição:** Raiz quadrada da variância.
- Indica a dispersão dos dados em relação à média.
- **Dados não agrupados:**
    - População:
        
        σ=(Σ(xi−X―)2/n)
        
    - Amostra:
        
        σ=(Σ(xi−X―)2/(n−1))
        
    - Exemplo: Desvio padrão dos preços de discos rígidos.
- **Dados agrupados:**
    - População:
        
        σ=((Σ(xi−X―)2∗fi)/n)
        
    - Amostra:
        
        σ=((Σ(xi−X―)2∗fi)/(n−1))
        
    - Exemplo: Desvio padrão dos valores de frete.
- **Dados agrupados por classe:**
    - População:
        
        σ=((Σ(pmi−X―)2∗fi)/n)
        
    - Amostra:
        
        σ=((Σ(pmi−X―)2∗fi)/(n−1))
        
    - Exemplo: Desvio padrão do tempo de permanência em um aplicativo.
