# Notas de Leitura — *Software Engineering at Google* (O’Reilly)

Este documento reúne comentários e reflexões sobre os primeiros trechos do livro *Software Engineering at Google*, destacando as diferenças entre **programar** e **fazer engenharia de software**, além de exemplos práticos de **trade-offs**.

---
## Exercício 1

### Trecho 1 — Programar x Engenharia de Software

O texto aborda a diferença entre **programar** e **fazer engenharia de software**, conceitos que muitas vezes são confundidos e usados como sinônimos.  

- **Programar**: habilidade de escrever código que funciona.  
- **Engenharia de Software**: envolve aplicar métodos, teorias, processos e garantir que o software seja **correto, confiável e sustentável ao longo do tempo**.  

O autor compara com outras engenharias (civil, mecânica, aeronáutica), ressaltando que engenheiros seguem **processos rigorosos e normas claras**.

---
## Exercício 2

### Trecho 2 — Programming Integrated Over Time

O autor reforça que engenharia de software não é apenas escrever código, mas sim **cuidar do software ao longo do tempo**. O valor do código não está apenas em sua criação, mas em sua **manutenção e utilidade contínua**.  

### Pontos principais:
- **Tempo e mudança**: o código vai precisar se adaptar; a engenharia deve facilitar essa adaptação.  
- **Escala e crescimento**: não é só o código que cresce, mas também as organizações.  
- **Trade-offs e custos**: decisões técnicas têm preço (tempo, manutenção, complexidade); é necessário equilibrar **qualidade, velocidade e custo**.  

O autor ressalta que não existem respostas absolutas: a engenharia de software é um campo em **constante evolução**.

---

## Características do Software

- **Intangibilidade**: software é **invisível** e não físico, o que dificulta a visualização de progresso e a detecção de falhas (diferente de um prédio ou avião).  
- **Programação em tempo/escala**: o esforço não é apenas criar o código inicial, mas garantir sua **manutenção ao longo do tempo** e **capacidade de escalar** conforme cresce o número de usuários e a complexidade do sistema.  
- **Exemplo Windows vs Linux**:  
  - Windows cresceu priorizando **compatibilidade e suporte a usuários leigos**, mas carrega complexidade e alto custo de manutenção.  
  - Linux, em contrapartida, nasceu voltado à comunidade técnica, priorizando **robustez e adaptabilidade**, ainda que com curva de aprendizado maior.  
  → Ambos refletem **trade-offs** feitos em suas origens que impactam sua evolução até hoje.  

---
## Exercício 3

### Trade-offs

**Definição**: trade-off é quando você abre mão de algo para ganhar outra coisa.  
Não dá pra ter tudo ao mesmo tempo, então é preciso escolher o que é mais importante.  

### Exemplos gerais:
1. **Tempo x Dinheiro** → Trabalhar mais horas aumenta o dinheiro, mas reduz o tempo livre.  
2. **Qualidade x Velocidade** → Fazer algo rápido pode diminuir a qualidade.  
3. **Preço x Conforto** → Comprar passagem de ônibus mais barata significa menos conforto na viagem.  

### Exemplos em software:
- **Velocidade de entrega x Manutenibilidade**: lançar rápido pode gerar dívida técnica.  
- **Complexidade x Flexibilidade**: arquiteturas muito robustas dão poder, mas aumentam custo de manutenção.  
- **Usuários leigos x Usuários avançados**: interfaces simples vs. sistemas altamente configuráveis (Windows x Linux).  

---
## Exercício 4

### Diagrama de Classes UML
<img width="464" height="302" alt="diagramaloja" src="https://github.com/user-attachments/assets/87739321-c526-48b3-b20a-e24d755a1fde" />

---
## Exercício 5

### Implementação em Java

**Classe Loja:**
<img width="1118" height="632" alt="loja" src="https://github.com/user-attachments/assets/74f16705-5dc8-423c-8452-df5faebf706b" />

**Classe Produto:**
<img width="1119" height="304" alt="produto" src="https://github.com/user-attachments/assets/4e74317b-1ae7-4570-8d88-5c79e301d42c" />

**Classe Cliente:**
<img width="1116" height="294" alt="cliente" src="https://github.com/user-attachments/assets/05a31962-1a62-4647-92f5-7d8423e2dd5b" />

---
## Exercício 6

### Teste Automatizado em Java
<img width="738" height="372" alt="testeloja" src="https://github.com/user-attachments/assets/a0f0007a-b6e0-4f17-9fdd-9153ffc7d319" />

---
## Exercício 7

### Diagrama de Classes UML
<img width="410" height="381" alt="diagramapet" src="https://github.com/user-attachments/assets/60acb440-fefb-46a8-b3c2-7f39222b8c8b" />

---
## Exercício 8

### Implementação em Java

**Classe PetShop:**
<img width="1117" height="363" alt="petshop" src="https://github.com/user-attachments/assets/47a35f5e-1cc3-45aa-954d-a133c2173324" />

**Classe Animal:**
<img width="1116" height="392" alt="animal" src="https://github.com/user-attachments/assets/d3eac8bc-e264-4673-bec3-9e6fa77f7a37" />

**Classe Dono:**
<img width="1116" height="300" alt="dono" src="https://github.com/user-attachments/assets/2d3ead71-b2e8-4b21-adcc-14793af95839" />

---
## Exercício 9

### Teste Automatizado em Java
<img width="767" height="382" alt="testepet" src="https://github.com/user-attachments/assets/6976408e-5831-4420-8101-99ed4b7ba42e" />
