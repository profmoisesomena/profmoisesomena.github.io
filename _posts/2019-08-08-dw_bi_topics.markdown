---
layout: post
title: Projetos de Data Warehouse e Business Intelligence consistentes
date: 2019-08-08 00:00:00 +0900
description: Neste post iremos listar 10 pontos de grande relavância para um projeto de DW/BI sadio. (optional)
img: dw_bi.png # Add image post (optional)
tags: [DW, BI] # add tag
---

Neste post vamos apresentar algums importantes pontos relacionados a um projeto sadio de BI/DW.Sem mais delongas vamos aos 10 pontos mais importantes relacionados a um projeto de BI/DW.
<br>
<br> **Resistindo o impulso de iniciar a codificação.**<br>
<br>
Ralph Kimball, define que que padoxalmente um dos mais importantes passos na concepção do BI é parar.
Voltar uma semana e certificarse de que se tem uma perspectiva ampla o suficinente de todos os requerimentos que envolvem seu projeto é muito importante.<br>
Projetar um DW/BI é uma tarefa que envolve um grande desafio que pode levar a descoberta de problemas durante o andamento caso não haja um planejamento sólido. Por isso, é importante antes de iniciar qualquer código, projetar as tabelas, ou especificações de hardware e software, parar e refletir sobre as seguintes questões apontadas por Ralph Kinball.<br>
<br>
1 - Business requirements (requerimentos de negócio):<br>
<br>
Você esta a par dos principais indicadores chave de desempenho (KPIS - Key performance Indicatores) que seus clientes/usuários realmente necessitam para tomar decissões que são realmente importantes para a empresa? Tendo uma resposta positiva para esta questão voce poderá identificar os ativos de dados necessários para apoiar as tomadas as decisões e será capaz de decidir que medidas e processos abordará primeiro.
<br>
2 - Strategic data profiling (perfil de dados estratégicos):<br>
<br>
Você verificou se os ativos de dados disponíves são necessários para responder as principais perguntas? O objetivo é tomar decisões sobre se devemos ou não proseguir em uma área ou assunto no início do projeto de DW/BI.<br>
<br>
3 - Tactical data profiling (perfil de dados táticos):<br>
<br>
Existe um órdem/diretiva executiva clara para apoiar o necessário processo de reengenharia requerido por uma cultura efetiva de qualidae de dados eficaz, talvez, ate mesmo direcionada para os Seis Sigmas da Qualidade de Dados? O único caminho real para umentar a qualidade dos dados é voltar para a fonte e descobrir porque melhores dados não estão sendo inseridos. Normalmente isto envolve um compromisso dos níveis mais altos para mudar o funcionamento dos processos de negócio de ponta a ponta, ao invés de direcionar a culpa simplesmente para os funcionários que inserem dados nos sistemas.<br>
<br>
4 - Integration (Integração):<br>
<br>
Existe um órdem executiva clara na organização para definir descritores1 comuns e medidas atraves de todos nossos processos voltados para o clientes? Todas as organizações da empresa que participam da integração de dados devem chegar a um acordo sobre os principais descritores e medidas. Os Executivos deixaram claro que isto deverá acontecer?<br>
<br>
5 - Latency (Latência).<br>
<br>
Voce tem uma definição realistica dos requesitos de negócios do usuários sobre a rapidez com que os dados devem ser publicados data warehouse, inclusive: on line, muitas vezes por dia ou de modo instantâneo?<br>
<br>
6 - Compliance (Conformidade):<br>
<br>
Voce rebebeu diretrizes claras da gerencia sênior quanto a conformidade e sensibilidade dos dados?<br>
<br>
7 - Security (Segurança)<br>
<br>
Voce sabe como voce irá proteger dados proprietários e confidenciais no processo de ETL , nos Desktops dos usuários na Web e em todas as medias permanentes?<br>
<br>
8 - Archiving (Arquivamento):<br>
<br>
Voce tem um plano realista para arquivamento de longo prazo de dados importantes e sabe quais dados devem ser arquivados?<br>
<br>
9 - Supporting business users (Suporte para usuários de negócios):<br>
<br>
Voce definiu os pefís de toda comunidade de usuários envolvidos para determinar suas habilidades para usar planilhas, construir consultas ad hoc em ferramentas de bancos de dados, ou somente visualizar relatórios em suas telas? Os usuários esperam anexar feramentas de análises preditivas e mineção de dados para entender os dados subjacentes?<br>
<br>
10 - IT licenses and skill sets (Licenças de TI e conjuntos de habilidades):<br>
<br>
Você está preparado para confiar nas principais licenças dos sites de tecnologia que a sua organização já contratou e você possui funcionários suficientes com habilidades avançadas para explorar as escolhas técnicas que feitas? Você sabe quais partes da sua organização esperam acessar Big Data ou a Internet das Coisas (IoT), e vocês possuem as habilidades para apoiar essas atividades que muitas vezes resultam em serviços externos de TI?<br>
<br>
Concluindo<br>
O tempo gasto respondento estas questãoes clássicas do DW é enormentente valioso. Cada uma das respostas irá afetar a arquitetura, escolha de abordaregns e até mesmo a viabilidade de seu projeto de DW/BI. É extremamente importante não começar a codificar antes que todos os membros da equipe entendam o que estas perguntas significam!
<br>
Referências:<br>
Ralph Kimball, DM Review, Nov 2007
> 1. Descritores:elemento que tem a função de descobrir, identificar ou indexar algo.
