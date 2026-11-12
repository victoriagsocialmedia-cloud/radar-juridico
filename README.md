# Radar Jurídico · Marcos Inácio Advogados

Radar de notícias quentes por área do direito (Administrativo, Aduaneiro, Agrário, Civil, Empresarial, Penal Tributário, Público, Trabalhista e Tributário), com pauta sugerida e nota de oportunidade ligadas aos serviços do site marcosinacio.adv.br.

- `index.html`: o site. Lê o `data.json` a cada acesso.
- `vercel.json`: configuração da hospedagem na Vercel (o `data.json` não fica em cache).
- `assets/`: logos da marca (versões escuras e claras).
- `data.json`: todas as notícias, prazos e serviços. É o único arquivo que muda nas atualizações.

Regra de atualização: só entra notícia verificada em fonte aberta e ligada a um serviço do site. Sem novidade verificada, o `data.json` não é alterado.
O Previdenciário tem radar próprio (`radar-previdenciario`).

Identidade visual: paleta da marca (Preto #24201e, Marrom #b0917b, Cinza #f7f1eb, Coral #de5a3c, Taupe #d7cabd) e fonte Inter.
Hospedagem: Vercel, ligada a este repositório. Cada push na `main` publica sozinho.
