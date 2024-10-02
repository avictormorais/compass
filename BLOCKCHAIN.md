# Blockchain
Pode ser entendida basicamente como uma **corrente de blocos** (tradução literal). Cada bloco armazena informações, e essas informações estão conectadas umas às outras, criando uma sequência.

É uma estrutura descentralizada, tornando-a independente de qualquer autoridade central para manter seu funcionamento pleno.

## Funcionamento básico

### 1. Blocos
Cada bloco possui três partes principais:
- **Dados**: As informações que estão sendo armazenadas como transações, contratos, etc.
- **Hash**: Uma "assinatura" digital única do bloco.
- **Hash do bloco anterior**: O hash do bloco que veio antes, criando uma cadeia entre os blocos, onde cada um se conecta ao anterior, até chegar no bloco gênesis (O primeiro bloco minerado).

### 2. Mineração
Para adicionar um novo bloco à cadeia, é realizada a chamada **mineração**. Os mineradores precisam resolver problemas matemáticos, e quem conseguir resolver primeiro, consegue adicionar o bloco que criou à blockchain.

### 3. Consenso
A blockchain usa protocolos de **consenso** para assegurar que todos na rede concordam com o estado atual da blockchain. Isso evita fraudes ou alterações indevidas.
Os principais meios de consenso são **Proof of Work**, usado na mineração de bitcoin, e **Proof of Stake**, usado na rede Ethereum.

## Tipos de Blockchain
### 1. Blockchain Pública
Qualquer pessoa pode fazer parte da rede, verificar e adicionar blocos.

### 2. Blockchain Privada
Apenas usuários autorizados podem participar, sendo mais usado em empresas.

### 3. Blockchain Híbrida
Combina características públicas e privadas, controlando quem pode participar da validação ou transação. Podendo permitir transações apenas autorizadas, mas validações públicas.

## Por que usar blockchain
- **Segurança**: Como cada bloco depende do anterior, alterar um bloco altera toda a cadeia, o que torna a blockchain segura.
  
- **Transparência**: Todos os participantes da rede podem verificar as transações e auditá-las.
  
- **Descentralização**: Não há um ponto único de falha, porque os dados são distribuídos entre todos os computadores conectados na rede.

---

## Aplicações
- **Criptomoedas**: O maior e mais famoso uso da blockchain, como o Bitcoin.
  
- **Contratos inteligentes**: Automatizam acordos entre partes sem precisar de intermediários (Geralmente usa-se a rede Ethereum).
  
- **Rastreabilidade**: Por conta da conexão ao bloco anterior, toda a rede de blocos pode ser rastreada facilmente.

---

## Desafios
- **Escalabilidade**: À medida que a blockchain cresce, o processamento pode ficar mais lento e a armazenagem da corrente torna-se mais difícil.
  
- **Consumo de energia**: Especialmente em blockchains que usam Proof of Work, a mineração pode consumir muita energia, podendo tornar-se um problema global, haja vista a grande quantidade de mineradores na rede.

---

## Meios de consenso

- **Proof of Work**: Nesse método, para se adicionar um novo bloco, ele tem que atender a especificidade da rede, onde o hash do bloco deve ter um certo número de zeros á esqueda para ser adicionado. Então, ao gerar um bloco novo, caso ele não tenha `0's` suficientes, ele não pode ser adicionado. Então, o minerador deve tentar gerar outro bloco que cumpra a quantiade de `0's` para adicionar o bloco à rede.
  
- **Proof of Stake**: Nesse método, o staker (validador) que possui maior stake (quantidade de criptomoeda) tem certa vantagem em relação aos demais. Portanto, quem tem maior quantidade de criptomoedas, tende a criar mais blocos e adicioná-los à rede.

### Problemas dos meios de consenso
- **Proof of Work**: Por conta da alta "geração" de blocos com finalidade de criar um bloco válido, o gasto energético e computacional é alto. E no geral, é um gasto desnecessário, já que esse `loop` serve exclusivamente para provar que o minerador tem alto poder computacional, não sendo uma tarefa primordial para manutenção da rede.
  
- **Proof of Stake**: Por priorizar staker que tenham mais criptomoedas, primordialmente o PoS acaba criando um monopólio, pois, na teoria quem tem mais criptomoedas consegue criar mais blocos, e ao criar blocos, consegue mais criptomoedas. Porém, já existem alguns algoritmos para randomizar um pouco a escolha do minerador para que não crie esse monopólio, e possibilitando stakers com menos valores também adicionar blocos à rede.