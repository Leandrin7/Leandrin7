Tecnologias com que trabalho
<p> <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"> <img alt="React" src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"> <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"> <img alt="Anthropic" src="https://img.shields.io/badge/Anthropic_API-191919?style=for-the-badge&logo=anthropic&logoColor=white"> <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"> <img alt="Supabase" src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white"> <img alt="Mercado Pago" src="https://img.shields.io/badge/Mercado_Pago-00B1EA?style=for-the-badge&logo=mercadopago&logoColor=white"> <img alt="Vercel" src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white"> <img alt="Railway" src="https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white"> <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> <img alt="pnpm" src="https://img.shields.io/badge/pnpm-F69220?style=for-the-badge&logo=pnpm&logoColor=white"> <img alt="Turborepo" src="https://img.shields.io/badge/Turborepo-EF4444?style=for-the-badge&logo=turborepo&logoColor=white"> <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"> <img alt="pandas" src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"> <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"> </p>
O que eu sei fazer com cada uma
Tecnologia	Experiência prática
TypeScript	Escrevo toda a base do Papo Redação em TypeScript: front, API, worker e pacotes compartilhados
React · Next.js	Construí a interface web completa, com áreas separadas para alunos, professores e coordenação e painéis de acompanhamento
Node.js	Desenvolvi um worker assíncrono que processa as correções em segundo plano sem travar a aplicação
Anthropic API	Integrei LLMs ao produto para avaliar redações nas 5 competências do ENEM, com engenharia de prompts própria e avaliação de outros provedores de modelo
PostgreSQL · Supabase	Modelo e mantenho o banco de dados, a autenticação e o armazenamento de arquivos
Mercado Pago	Integrei cobrança e assinaturas para clientes B2B
Vercel	Faço o deploy e a configuração de produção do front-end
Railway · Docker	Coloco o worker em produção com build por Dockerfile, healthcheck ajustado e estratégia de réplicas
pnpm · Turborepo	Estruturei o projeto em monorepo (apps/web, apps/api, packages/shared) com builds em cache
Python · pandas	Faço análise de dados direto sobre o banco do produto, como o funil de cadastro
Git · GitHub	Versionamento e fluxo de trabalho do projeto
Arquitetura
Arquitetura hexagonal: isolei a lógica de correção atrás de uma porta (CorretorPort), o que permite trocar ou combinar provedores de LLM sem mexer no resto do sistema.
Processamento assíncrono: o front só registra o envio; o worker faz o trabalho pesado e devolve o resultado.
Topologia Vercel + Railway + Supabase: cada peça roda onde faz mais sentido, com o Supabase como fonte única de dados e autenticação.
Em foco agora
Evoluir o motor de correção do Papo Redação
Avaliar um segundo provedor de LLM através da CorretorPort
Preparação para o Desafio de Informática da PUC-Rio (algoritmos e estruturas de dados)
Contato
Site: SEU-SITE-AQUI
LinkedIn: SEU-LINKEDIN-AQUI
E-mail: SEU-EMAIL-AQUI
