---
layout: page
title: Sobre
permalink: /sobre/
---

A Maratona de Programação da Semana de Informática (MPSI) foi criada em 2019 nos moldes da [Maratona SBC de Programação](https://maratona.sbc.org.br/sobre/index.html), da [Sociedade Brasileira de Computação]()(SBC). 

# Objetivo e Regras

Os competidores participam em times de até 3 estudantes, com objetivo de resolver a maior quantidade de questões da prova no menor tempo. 

As regras da competição são as seguintes:

- No início da prova, cada time recebe um caderno de questões impresso, o qual foi escrito por professores do Departamento de Informática da UFV e possui diferentes níveis de dificuldade;
- As soluções são julgadas por um juiz automatizado, que compara as saídas geradas pelos programas desenvolvidos pelos alunos com as saídas esperadas;
- Cada questão é associada a um balão de uma determinada cor. Sempre que um time resolve uma questão, ele recebe um balão (virtual, no sistema de submissão, e real, que é pendurado ao lado do computador do time) daquela cor;
- Cada time tem acesso a apenas um computador e não pode usar a Internet de forma alguma, a não ser para acessar o sistema de submissão de soluções (única e exclusivamente pelo login do time);
- Como cada time tem acesso a apenas um computador, será disponibilizada uma impressora para que os times imprimam códigos parciais;
- É permitido levar qualquer material impresso e também digital (em um pendrive, que deve ser copiado para o computador do time antes do início da maratona);
- Os times terão acesso ao placar durante a competição, mas ele deixará de ser atualizado faltando 30 minutos para o final (período frozen) e não receberão respostas do julgamento das submissões faltando 15 minutos para o final (período blind).

# Sistema de Submissão e Avaliação 

Tradicionalmente, a Maratona da SI, assim como na Maratona da SBC, utiliza o sistema de controle de competição [BOCA Online Contest Administrator]() (BOCA). A figure a seguir ilustra a interface desse sistema:

<img src="{{'/assets/images/boca.png' | relative_url}}">

 Nesse sistema, os participantes podem submeter suas soluções em diferentes linguagens de programação, como: C, C++, Java e Python. Assim que uma submissão é feita, ela é adiciona a uma fila de execução e, assim que possível, é executada com um conjunto de casos de testes. Quando todos os casos são verificados, o BOCA retorna uma notificação para os participantes com o resultado da execução:

- YES: o programa passou em todos os casos de teste, ou seja, a questão foi resolvida com sucesso. Nesse caso, o time que submeteu esse programa recebe um balão da cor associada à esta questão.
- NO: Wrong Answer - o programa respondeu incorretamente a algum(ns) dos testes dos juízes.
- NO: Time-limit Exceeded - a execução do programa excedeu o tempo permitido pelos juízes. 
- NO: Compilation Error	- o programa tem erros de sintaxe.
- NO: Runtime error - o programa não segue a especificação exigida na folha de questões.
