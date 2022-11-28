# cargo-inventory-system

# Motivation

Hoje em dia sistemas de e-commerce necessitam de estoques de carga cada vez mais dinamicos e rapidos em suas respostas, exemplos de empresas que normalmente precisam dessa dinamicidade sao: Amazon, Kaboom, Magazine Luiza, etc (normalmente varejo e e-commerc).

Com isso em mente, pretendemos desenvolver um sistema de estoque que resolva uma das principais dificuldades que existem em empresas desse tipo:

 A dificuldade de apenas ser possivel realizar uma compra, com itens que existam no estoque.

Evitando, assim, a complicacao de uma compra ser realizada sem que o estoque, do determinado item, esteja disponivel. Oque poderia resultar em estorno do valor e provavel perda do cliente.

De forma geral, todos os estoques visam esse objetivo, mas com a dinamicidade da internet e redes de distribuicao (logistica), tem-se questoes de fluxo de itens, pagamentos (estorno, confirmacao), disponibilidade, falta de produto (reposicao, fluxo imperfeito).

Vamos abordar cada um desses itens individualmente e propor resolucoes viaveis e que incorporem nossos ideais de dinamicidade e entrega.

# Objectives

Armazenar quantidade de mercadoria para determinado fim (venda).

# Activities

| Identificador | Nome | Descricao |
|---------------|------|-----------|
| ATCV001 | Quantifica | Gerencia (controle sobre) da quantidade de itens no estoque. |
| ATCV002 | Repoe | Reposicao de determinado item. |

![Diagrama de Atividades](#activities)