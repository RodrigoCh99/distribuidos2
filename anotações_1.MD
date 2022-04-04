## **DEFINIÇÕES DE SISTEMAS DISTRIBUIDOS:**

> *"Sistemas em que componentes de hardware e software localizados em diferentes computadores 
interconectados se comunicam e coordenam suas ações trocando mensagens." 
 (George Coulouris)*

> *"Conjunto de computadores independentes que se apresenta a seus usuários 
como um sistema unico e coerente." (Andrew Tanenbaum)*

> *"Sistema onde você não consegue trabalhar por causa de uma falha em um computador 
que você nunca viu" (Leslie Lamport)*

vídeo introdutório:
https://www.youtube.com/watch?v=hE9ksH4kOlQ

## **Consequências da distribuição de um sistema:**

### **Concorrência:** 

Em uma rede de computadores, a execução concorrente de programas é a norma. Posso fazer meu trabalho em meu computador, enquanto você faz
o seu em sua máquina, compartilhando recursos como páginas Web ou arquivos,
quando necessário.

### **Inexistência de relógio global:**

Quando os programas precisam cooperar, eles coordenam suas ações trocando mensagens. A coordenação frequentemente depende
de uma noção compartilhada do tempo em que as ações dos programas ocorrem. Entretanto, verifica-se que existem limites 
para a precisão com a qual os computadores podem sincronizar seus relógios em uma rede – não existe uma noção global
única do tempo correto.

### **Falhas independentes:**

Todos os sistemas de computador podem falhar, e é responsabilidade dos projetistas de sistema pensar nas consequências 
das possíveis falhas. Nos sistemas distribuídos, as falhas são diferentes. Falhas na rede resultam no isolamento dos 
computadores que estão conectados a ela, mas isso não significa que eles param de funcionar. Na verdade, os programas 
neles existentes talvez não consigam detectar se a rede falhou ou se ficou demasiadamente lenta. Analogamente, a falha 
de um computador ou o término inesperado de um programa em algum lugar no sistema (um colapso no sistema) não é 
imediatamente percebida pelos outros componentes com os quais ele se comunica. Cada componente do sistema pode falhar 
independentemente, deixando os outros ainda em funcionamento.

## **Exemplos de sistemas distribuídos:**

- Finanças e comércio: Amazon e eBay, e PayPal.
- A sociedade da informação: Google, Yahoo e wikipedia.
- Setores de criação e entretenimento: Netflix, Disney+ e YouTube.

## Interligação em rede pervasiva e a Internet moderna



