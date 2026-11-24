# HS Desentope

Site institucional estático (HTML/CSS/JS, sem build). Os arquivos publicados ficam em `dist/`.
Inspirado no site da Pioneira Desentupimentos (sinais de quando chamar, cartões de serviço, faixa de plantão,
passos, formulário que abre o WhatsApp e FAQ), com visual próprio: hero com foto de ponta a ponta, tipografia
Archivo condensada + Figtree, vermelho, branco e amarelo do cartão HYS e o azul da gota só na inspeção em vídeo.

## Vercel

Importar a raiz do repositório com framework **Other**. O `vercel.json` define a saída `dist`, sem build nem instalação.

## Estrutura

```
dist/
  index.html
  assets/css/styles.css
  assets/js/main.js          menu mobile, formulário -> WhatsApp, FAQ, reveal ao rolar, ano do rodapé
  assets/fonts/phosphor/     ícones Phosphor (woff2 local, licença MIT)
  assets/img/                fotos ilustrativas (Unsplash) e icon.svg
  assets/credits.html|md     créditos das fotos
```

## Dados usados (cartões de visita e mensagens encaminhadas, 24/11/2026)

| Campo | Valor |
|---|---|
| Nome | HS Desentope (definido pela AROE; os cartões dizem "HYS Desentope" e "Hidra Desentupidora") |
| Serviços | Desentupimento, caça vazamentos, limpeza de caixa d'água, encanador/canalização, reparação hidráulica e inspeção em vídeo (acrescentada a pedido) |
| Atendimento | "Piquete 24h" (cartão HYS) |
| Telefone / WhatsApp | (43) 99150-3695 (`wa.me/5543991503695`) |
| Endereço | Rua Waldomiro Batista de Araújo, 576, Jardim das Palmeiras, Londrina - PR, 86083-580 |
| Slogan | "Entupiu aí? Não se desespere. Nós temos a solução para o seu problema." |

## Confirmar com o cliente

- O número 86083580 foi encaminhado sozinho e foi usado como CEP (86083-580); conferir.
- Se o endereço é ponto de atendimento ou só base (o mapa mostra o endereço).
- Bairros/cidades atendidos, preços e se o plantão 24h vale todos os dias.
- Os cartões citam o site hidradesentupidora.com.br; verificar se o domínio será usado.
- Logo da HS Desentope e fotos reais (as fotos atuais são ilustrativas; a marca no topo é feita em texto).
