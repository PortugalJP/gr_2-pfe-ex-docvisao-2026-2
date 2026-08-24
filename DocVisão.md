# *Documento de Visão*

## *Aplicativo de Entregas Comunitárias para Áreas Insulares*


## *1. Introdução*

### 1.1 *Objetivo do documento*

Este documento tem como finalidade apresentar a visão geral de um aplicativo de entregas voltado para comunidades localizadas em áreas pequenas e geograficamente isoladas, como ilhas. A intenção é alinhar o entendimento entre todos os envolvidos — equipe de desenvolvimento, patrocinadores e futuros usuários — sobre o propósito e a direção do produto antes de qualquer definição técnica mais aprofundada.

---

### 1.2 *Público-alvo*

O público-alvo deste sistema é formado por moradores de comunidades insulares ou de pequenas áreas de difícil acesso, que hoje dependem de deslocamentos físicos ou de arranjos informais para obter produtos e serviços. Também fazem parte do público-alvo os pequenos comerciantes locais, como mercearias, restaurantes, farmácias e produtores artesanais, que poderão usar o aplicativo como canal de venda adicional. Por fim, o sistema se destina a entregadores locais, moradores da própria comunidade que poderão atuar como agentes de entrega, gerando renda complementar dentro do próprio território em que vivem.

---

### 1.3 *Escopo do sistema*

O sistema abrangerá o cadastro de estabelecimentos locais e de seus produtos ou serviços, a criação de pedidos por parte dos moradores, a atribuição desses pedidos a entregadores disponíveis na comunidade e o acompanhamento do status da entrega até sua conclusão. Está incluído também um mecanismo simples de pagamento e um canal de comunicação entre cliente, comerciante e entregador.

---

## *2. Posicionamento*

### 2.1 *Oportunidade de mercado*

Comunidades pequenas e isoladas, como ilhas, costumam ficar à margem das plataformas de entrega tradicionais, já que os grandes aplicativos concentram sua operação em centros urbanos densos, onde o volume de pedidos compensa os custos logísticos. Essa lacuna cria uma oportunidade clara para uma solução dimensionada especificamente para a realidade dessas comunidades: baixo volume populacional, distâncias curtas, forte conhecimento mútuo entre moradores e comércio local ainda pouco digitalizado. Um aplicativo pensado para esse contexto pode se tornar a principal ferramenta de comércio digital da região, sem concorrência direta de grandes players.

---

### 2.2 *Problema a ser resolvido*

Atualmente, os moradores dessas comunidades enfrentam dificuldades para adquirir produtos e serviços sem se deslocar fisicamente, o que é especialmente problemático para idosos, pessoas com mobilidade reduzida ou em dias de condições climáticas adversas, comuns em regiões insulares. Os pequenos comerciantes locais, por sua vez, não têm acesso a canais digitais de venda compatíveis com sua realidade, ficando limitados ao público que passa fisicamente por seus estabelecimentos. Não existe, hoje, um meio estruturado e confiável de conectar a demanda dos moradores à oferta dos comerciantes locais por meio de um serviço de entrega organizado.

---

### 2.3 *Proposta de solução*

A solução proposta é um aplicativo de entregas leve e simples de usar, adaptado às particularidades de uma comunidade pequena: poucos quilômetros de distância entre pontos, entregadores que já conhecem o território e uma base de comerciantes limitada, porém bem mapeada. O aplicativo permitirá que moradores façam pedidos a partir de estabelecimentos locais cadastrados, que esses pedidos sejam roteados a entregadores da própria comunidade e que todo o processo seja acompanhado de forma transparente, do pedido até a entrega. Dessa forma, fortalece-se a economia local, reduz-se a dependência de deslocamentos físicos e cria-se uma fonte adicional de renda para moradores que atuarem como entregadores.

---

## 3. *Descrição de Stakeholders e Usuários*

### 3.1 *Resumo dos Stakeholders*

- **Morador da comunidade (cliente)** — Residente da área insular que utiliza o aplicativo para solicitar produtos e serviços sem precisar se deslocar fisicamente. Responsável por realizar pedidos, efetuar pagamentos e avaliar o serviço recebido.
- **Comerciante local** — Proprietário de mercearia, restaurante, farmácia ou negócio artesanal que passa a vender também pelo canal digital. Responsável por cadastrar produtos/serviços, gerenciar disponibilidade e preparar/confirmar pedidos.
- **Entregador local** — Morador da comunidade que atua como agente de entrega, gerando renda complementar. Responsável por aceitar entregas, transportar pedidos e atualizar o status da entrega.
- **Patrocinador do projeto** — Responsável por viabilizar e financiar o desenvolvimento do aplicativo. Define prioridades estratégicas e aprova escopo e investimentos.
- **Equipe de desenvolvimento** — Responsável pela construção, manutenção e evolução técnica do sistema. Desenvolve, testa e mantém as funcionalidades do aplicativo.

---

### 3.2 **Resumo dos usuários**

- **Cliente (morador)** — Usuário final que realiza pedidos pelo aplicativo. Representante a definir junto ao patrocinador.
- **Comerciante** — Usuário que gerencia seu catálogo de produtos/serviços e recebe pedidos. Representante a definir junto ao patrocinador.
- **Entregador** — Usuário que executa as entregas na comunidade. Representante a definir junto ao patrocinador.

---

## 3.3 *Ambiente do usuário*
O uso do aplicativo ocorrerá em um contexto de conectividade limitada e instável, comum em áreas insulares, o que exige uma interface leve, de baixo consumo de dados e com boa tolerância a conexões intermitentes. Os usuários possuem perfis variados de familiaridade com tecnologia — desde moradores mais jovens, habituados a aplicativos móveis, até idosos ou comerciantes com pouca experiência digital —, o que reforça a necessidade de uma navegação simples e intuitiva. As distâncias percorridas são curtas, e os entregadores normalmente já conhecem o território, o que reduz a complexidade logística em comparação a aplicativos urbanos tradicionais.

---

## *5. Requisios de Alto Nível*

### *Requisitos Funcionais*

- O sistema deverá permitir o cadastro e a autenticação de moradores, comerciantes e entregadores.
- O sistema deverá permitir que comerciantes cadastrem e atualizem seus estabelecimentos, produtos e serviços.
- O sistema deverá permitir que moradores consultem os estabelecimentos locais, vizualizem os itens disponíveis e realizem pedidos.
- O sistema deverá encaminhar os pedidos aos entregadores disponíveis na comunidade.
- O sistema deverá permitir o acompanhamento do status do pedido, desde a confirmação até a conclusão da entrega.
- O sistema deverá disponibilizar um meio de pagamento e um canal de comunicação entre morador, comerciante e entregador.

---

### *Requisitos Não Funcionais*

- O aplicativo deverá possuir uma interface simples, intuitiva e de fácil utilização.
- O aplicativo deverá ser compatível com dispositivos móveis e adaptar-se a diferentes tamanhos de tela.
- O aplicativo deverá apresentar bom desempenho mesmo em conexões de interenet  de baixa velocidade.
- O sistema deverá proteger os dados pessoais dos usuários e as informações  relacionadas aos pagamentos.
- O sistema deverá manter as informações dos pedidos e de seus status atualizadas de forma confiável.

---

## *6. Restrições e Premissas*

### *Restrições*

- Dependência de conexão com a internet
- Dependência da disponibilidade de entregadores locais
- Necessidade de compatibilidade com dispositivos móveis
- Infraestrutura limitada

--- 

### *Premissas*

- Existência de comerciantes locais dispostos a utilizar a plataforma
- Existência de moradores interessados a realizar entregas
- Disponibilidade de acesso à internet 
- Haverá demanda suficiente pelo serviço de entregas na comunidade


