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
<img width="1083" height="376" alt="Captura de tela 2025-09-05 140501" src="https://github.com/user-attachments/assets/ac244b07-c6bd-4b19-be41-a672f9ce29d4" />
---
## Exercício 5

### Implementação em Java

---
## Exercício 6

### Teste Automatizado em Java

---
