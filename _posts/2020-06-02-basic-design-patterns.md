---
layout:     post
title:      Um pouco sobre design patterns
date:       2020-06-02 11:21:29
summary:    Um pouco sobre design patterns para ter em mente em seus projetos
categories: design-patterns
---

Quando vamos desenvolver o código de um software é comum encontrarmos problemas que são recorrentes, mesmo que em projetos distintos e com o passar do tempo criamos soluções padronizadas para os problemas.

Com isso pode ocorrer padronizações boas ou ruins, e não foram poucas as vezes que vi soluções ruins serem replicadas de um projeto para outro, porque é comum buscarmos reaproveitar soluções, mas o problema é quando os engenheiros não questionam as soluções.

Embora as padronizações ruins possam "resolver o problema", elas podem vir com vários outros problemas que  impactará performance, segurança, integridade e até mesmo semântica ruim que irá trazer vários problemas na manutenção do projeto, que obviamente será queimar dinheiro de diversas formas, onerando profissionais, processos e outros recursos... E no final a empresa perde dinheiro.

Alguns engenheiros perceberam que existem problemas que são recorrentes, e então desenvolveram algumas soluções padrões para esses problemas e com isso foram criado os famosos "design patterns" ou "padrões de projeto" para resolvê-los da melhor forma possível.

Existem design patterns em vários cenários, que vai desde a solução de códigos(O nosso caso de estudo desse artigo), planejamento ágil, infraestrutura de redes, microsserviços...

Neste pequeno artigo vamos tentar falar um pouco mais sobre os padrões GoF("Gang of Four" ou "A gangue dos quatro"), que faz referência aos quatros profissionais Erich Gamma, Richard Helm, Ralph Johnson, e John Vlissides, que escreveram o livro "Design Patterns".

No GoF os padrões são classificados basicamente em 3 famílias:
- **Padrões de criação ou Creational Patterns**  está relacionado as criações de classes e objetos fornecendo flexibilidade e reutilização de código de forma mais eficiente.  
    
- **Padrões estruturais ou Structural Patterns** é a forma que classes e objetos podem ser compostos para formar estruturas maiores.
    
- **Padrões comportamentais ou Behavior Patterns** se preocupa com a interação e a responsabilidade de cada objeto.

## Os benefícios da utilização dos padrões

Devido os padrões terem sido testados e validados para as soluções dos problemas nas quais eles propõem resolver, faz com que a velocidade do desenvolvimento do software aumente e também a qualidade.

Os padrões também ajudam no entendimento de código e na discussão técnica sobre a arquitetura do sistema, pois são padrões amplamente utilizados. São de baixo acoplamento, a organização e manutenção do software se torna mais elegante e não confusa.

## Os tipos de padrões de projetos

Abaixo estão os padrões de acordo com as familias do GoF:

- **Padrões criacionais(Creational Patterns)**

     1. [Abstract Factory](http://xxpauloxx.com.br/design-patterns-factory)

     2. Builder

     3. [Factory Method](http://xxpauloxx.com.br/design-patterns-factory)

     4. Prototype

     5. Singleton.

        

- **Padrões estruturais(Structural Patterns)**  

    1. Adapter

    2. Bridge

    3. Composite

    4. Decorator

    5. Façade

    6. Flyweight

    7. Proxy.

       

- **Padrões comportamentais(Behavior Patterns)**  

     1. Chain of Responsibility

     2. Command

     3. Interpreter

     4. Iterator

     5. Mediator

     6. Memento

     7. Observer

     8. State

     9. Strategy

     10. Template Method

     11. Visitor.

         

A idéia é para cada artigo escrito sobre os temas, ser colocado um link nos padrões da lista.
