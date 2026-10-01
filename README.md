# Filipe Jones

Em transição para Produto. Chego com três bagagens que raramente aparecem juntas: formação em Direito (Unicap), dois anos como fundador de uma produtora audiovisual e treze meses de formação Full Stack. Desde setembro de 2026 curso a formação de Product Manager da PM3.

O que me interessa: entender como a operação de alguém funciona de verdade, transformar isso em escopo com critério de sucesso e conversar com engenharia sem intermediário. Aprendi a programar para entender o custo do que peço.

## Projeto em destaque

**[Indústrias Wayne](https://github.com/BlackJoness/wayne-industries)** · [app no ar](https://wayne-industries-web.vercel.app)

Controle de acesso por perfil, gestão de recursos e dashboard. O briefing tinha três páginas e nenhuma especificação técnica; o primeiro trabalho foi transformá-lo em escopo com critério de aceite. O README conta o que cada frase do enunciado virou, o que foi cortado e por quê, e onde cada decisão está registrada (5 ADRs).

| Problema | Decisão | Resultado |
|---|---|---|
| Três perfis com permissões diferentes | Autorização validada no servidor, nunca só na tela | Chamar a rota com token de nível inferior devolve 403 |
| "Controle de acesso" sem definição | Entidade Área com nível mínimo e registro de cada tentativa com o motivo | Trilha auditável de quem tentou entrar onde |
| Prazo de uma semana | Refresh token, E2E e upload cortados, com motivo registrado | Entrega no prazo, 52 testes em CI |

Node.js · Express · PostgreSQL · Prisma · React · TypeScript · Docker

## Contato

[LinkedIn](https://www.linkedin.com/in/filipe-jones/) · Recife, Brasil
