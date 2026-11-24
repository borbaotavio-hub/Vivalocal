# VivaLocal — projeto inicial

## Como executar
1. Baixe e extraia `vivalocal.zip`.
2. Abra a pasta no Visual Studio Code.
3. Abra `index.html` no navegador (recomendado: extensão Live Server no VS Code).

## Arquivos
- `index.html`: estrutura das telas de cadastro e painel.
- `styles.css`: identidade visual Frutiger Aero em branco, laranja e tons azulados.
- `script.js`: cadastro local, pesquisa, filtros, favoritos, histórico de visitas e sugestões.

## Observações importantes
- Esta é uma demonstração front-end. Os dados ficam no `localStorage` do navegador e não são compartilhados entre usuários ou dispositivos.
- Para um sistema real com contas, vários usuários, envio de fotos e sugestões públicas, será necessário conectar um back-end e banco de dados (por exemplo, Supabase ou Firebase).
- As seis atrações iniciais cobrem uma cidade de cada região do Brasil. As fotos são imagens reais de cada ponto turístico, obtidas no Wikimedia Commons, todas em domínio público ou CC0 (livres para uso, sem exigência de atribuição). Os arquivos ficam em `images/places/`, e o autor, a licença e o link da fonte de cada foto estão registrados no campo `credit` de cada atração em `script.js` e aparecem na janela de detalhes.

| Atração | Autor | Licença |
|---|---|---|
| Jardim Botânico (Curitiba) | Wilfredor | CC0 |
| Ópera de Arame (Curitiba) | Renato Soares / MTur Destinos | Domínio público |
| Cristo Redentor (Rio de Janeiro) | Wilfredor | CC0 |
| Pelourinho (Salvador) | Márcio Filho / MTur Destinos | Domínio público |
| Teatro Amazonas (Manaus) | Ridiculopathy | CC0 |
| Catedral de Brasília | Adeilton O. de Souza | CC0 |
- Os textos históricos são resumos introdutórios; recomenda-se revisão e inclusão de fontes oficiais locais antes da apresentação/publicação.
