# Streaming

Começando projeto para estudo de como criar uma plataforma de streaming de cursos em vídeo.

Considerando possíveis stacks.

Pedi ao chat quais são stacks utilizadas por streamings educacionais famosos:

| Plataforma   | Back-end                       | Front-end                  | Infraestrutura          | Por que funciona                              |
| ------------ | ------------------------------ | -------------------------- | ----------------------- | --------------------------------------------- |
| Coursera     | Scala/Play, Cassandra, MySQL   | React, Bootstrap, GraphQL  | NGINX, AWS (S3, RDS)    | Escalabilidade, modularidade e deploy ágil    |
| Udemy        | Python (MVC custom), MySQL     | AngularJS, React ocasional | AWS, Cloudflare, Fastly | Agilidade, experimentação e CDN global        |
| edX          | Python/Django, MySQL, MongoDB  | Backbone.js, Sass          | S3, YouTube             | Framework maduro e custo otimizado            |
| Skillshare   | PHP, Node.js, React            | React, Backbone.js         | AWS, NGINX, Cloudflare  | Evolução tecnológica com base em performance  |
| Udacity      | Python, GraphQL, React/Angular | Modern front libs          | AWS                     | Foco em experiência rica e estrutura flexível |
| Khan Academy | — (YouTube-hosted)             | Web tracking + UI          | YouTube + web app       | Disseminação gratuita e eficiente             |

Também lembrei que a DSA utiliza uma espécie de CMS específico para aprendizado, chama [LearnWorlds](https://www.learnworlds.com).

| Critério                | Pontos Fortes                                   | Desafios / Limitações                               |
| ----------------------- | ----------------------------------------------- | --------------------------------------------------- |
| Interatividade          | Vídeos interativos, quizzes, SCORM, app builder | Recurso avançado requer plano alto                  |
| Marketing & Vendas      | Funnels, checkout custom, afiliados, pop-ups    | Integrações limitadas, e-mail marketing básico      |
| Branding e Customização | White-label completo, templates, blog integrado | UI carregada, curva de aprendizado lenta            |
| Suporte e Reputação     | Altas notas, atendimento personalizado          | Algumas queixas sobre bugs e relatórios             |
| Custo e Acesso          | Ferramentas poderosas abaixo do mesmo teto      | Taxas adicionais, funcionalidade bloqueada em tiers |

Considerando outros LMS Open Source:

| Plataforma     | Força principal                          | Pontos fortes                                                                                                        | Pontos fracos                                                                         |
| -------------- | ---------------------------------------- | -------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| **Moodle**     | Comunidade e maturidade                  | Muito flexível, enorme ecossistema de plugins, suporte a SCORM, multi-idioma, robusto para grandes volumes de alunos | Interface default pouco moderna (melhora com temas), curva de aprendizado para admins |
| **Open edX**   | Escalabilidade e cursos massivos (MOOCs) | Usado por Harvard e MIT, forte em vídeos interativos, fóruns e certificação                                          | Infra complexa, consumo alto de recursos, manutenção pesada                           |
| **Canvas LMS** | UX moderna e acessibilidade              | Open source, intuitivo, mobile-friendly, bom suporte a LTI                                                           | Instalação e atualização mais complexas, sem tantas ferramentas nativas de marketing  |
| **Chamilo**    | Simplicidade e leveza                    | Instalação rápida, consumo baixo de recursos, fácil para iniciantes                                                  | Menos flexível que Moodle e Canvas, design mais simples                               |
| **Forma LMS**  | Treinamento corporativo                  | Pensado para empresas, bom para e-learning interno, suporte a multi-empresa                                          | Comunidade menor, menos recursos para marketing/monetização                           |
