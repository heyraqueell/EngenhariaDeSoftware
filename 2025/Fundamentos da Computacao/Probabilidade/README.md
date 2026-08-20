## **Conceitos Fundamentais**



- **Experimento Aleatório:** Experimento que, mesmo repetido sob as mesmas condições, pode apresentar resultados diferentes.
    - **Exemplo**: Lançamento de um dado.
- **Espaço Amostral (Ω):** Conjunto de todos os resultados possíveis de um experimento aleatório.
    - **Exemplo**:  para o lançamento de um dado.
        
        Ω=1,2,3,4,5,6
        
- **Evento (E):** Subconjunto do espaço amostral.
    - **Exemplo**:  para o evento "sair número par" no lançamento de um dado.
        
        E=2,4,6
        
- **Probabilidade (P):** Medida da chance de um evento ocorrer.
    - **Fórmula**: , onde  é o número de resultados favoráveis e  é o número total de resultados possíveis.
        
        P(E)=n(E)/n(Ω)
        
        n(E)
        
        n(Ω)
        

## **Regras:**



- **Probabilidade de um Evento**: .
    
    0≤P(E)≤1
    
- **Probabilidade do Espaço Amostral**: .
    
    P(Ω)=1
    
- **Probabilidade de um Evento Impossível**: .
    
    P(∅)=0
    
- **Regra da Adição**:
    - **Eventos mutuamente exclusivos**: .
        
        P(A∪B)=P(A)+P(B)
        
    - **Eventos não mutuamente exclusivos**: .
        
        P(A∪B)=P(A)+P(B)−P(A∩B)
        
- **Regra da Multiplicação**:
    - **Eventos independentes**: .
        
        P(A∩B)=P(A)∗P(B)
        
    - **Eventos compostos**: .
        
        P(A∩B)=P(A)∗P(B|A)
        
- **Probabilidade Condicional**: .
    
    P(A|B)=P(A∩B)/P(B)
    

## **Distribuições:**



- **Distribuição Binomial:**
    - Usada para eventos com dois resultados possíveis (sucesso/fracasso).
    - **Fórmula**:
        
        P(X=k)=(n!/(k!∗(n−k)!))∗pk∗(1−p)n−k
        
        - n: número de tentativas.
        - k: número de sucessos.
        - p: probabilidade de sucesso.
- **Distribuição de Poisson:**
    - Usada para eventos raros que ocorrem em um intervalo de tempo ou espaço.
    - **Fórmula**: .
        
        P(X=k)=(e−λ∗λk)/k!
        
        - λ: taxa média de ocorrência.
        - k: número de ocorrências.
        - e: constante ()
            
            2.7182818…
            
- **Distribuição Normal:**
    - Distribuição contínua simétrica em forma de sino.
    - Caracterizada pela média () e desvio padrão ().
        
        μ
        
        σ
        
    - Usada para modelar muitos fenômenos naturais e sociais.
    - Probabilidades calculadas usando a tabela Z ou software estatístico.

## **Exemplos**



- **Probabilidade de tirar um número par em um dado**: .
    
    P(E)=3/6=1/2
    
- **Probabilidade de tirar duas caras em dois lançamentos de moeda**: .
    
    P(A∩B)=(1/2)∗(1/2)=1/4
    
- **Probabilidade de um evento binomial**:  em 5 tentativas com probabilidade de sucesso 0.3.
    
    P(X=2)
    
- **Probabilidade de um evento de Poisson**:  com taxa média de ocorrência 2.
    
    P(X=3)
    
- **Probabilidade de um valor em uma distribuição normal**:  usando a tabela Z.
    
    P(X<x)
