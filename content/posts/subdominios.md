---
title: "Subdomínios gratuitos!"
date: "2025-04-09T14:00:00-03:00"
tags: ['supabase', 'selfhosting', 'web', 'cloudflare', "domínios", "flutter"]
summary: "Construi uma plataforma para obter subdomínios gratuitos."
---

### Por quê?
Vi um [projeto gringo](https://is-a.dev/) e achei que seria interessante ter uma versão brasileira do mesmo. Também queria testar as functions do Supabase, portanto esse projeto tinha potencial para tomar várias horas do meu tempo livre (o que é muito bom).


### Como funciona?
O front-end em flutter faz chamadas para o supabase, que através das actions, gerencia os domínios que pertencem ao usuário.

Por sua vez, as actions gerenciam segredos e chamam os end-points do cloudflare para adicionar ou remover domínios.

### Como obter um domínio grátis?
É simples:

1. Acesse o [website](https://e-um.dev.br/);
2. Registre-se com o método que preferir (por enquanto apenas GitHub);
3. Adicione até 5 subdomínios de tipo A ou CNAME, como demonstrado abaixo:
![GIF](/posts/images/eum.gif)


### Código
O projeto pode ser encontrado nesse [repositório](https://github.com/fortmea/e-um.dev) (actions e front-end flutter).

### Agradecimento
Quero deixar meus agradecimentos aos responsáveis pelo is-a.dev, o projeto gringo mencionado antes que me serviu de inspiração.