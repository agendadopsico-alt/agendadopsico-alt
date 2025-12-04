Agenda do Psicólogo — versão estática (replica)
=============================================

O que tem aqui:
- index.html
- style.css
- assets/ (contém imagens placeholders em SVG)
- Este pacote é uma réplica **estática** do site original, não inclui scripts, formulários ou integrações do Tilda/Notion.

Por que as imagens estão diferentes?
- Usei imagens placeholder genéricas para evitar copiar arquivos que podem estar protegidos.
- Para deixar o site igual ao original, substitua os arquivos em `assets/` pelos arquivos reais.

Como pegar as imagens reais (duas opções simples):
1) Pelo navegador:
   - Abra https://agendadopsicologo.tilda.ws/
   - Clique com o botão direito na imagem → "Salvar imagem como..." e salve em `assets/` com o mesmo nome (ex: hero-image.svg).
2) Usando `wget` (linha de comando) — exemplo:
   - wget -O assets/hero-image.svg "URL_DA_IMAGEM"
   - Repita para cada imagem.

Sugestão de nomes (ou mantenha os originais):
- assets/hero-image.svg
- assets/feature-1.svg
- assets/feature-2.svg
- assets/feature-3.svg

Publicar no GitHub Pages:
1) Crie um repositório no GitHub e suba todos os arquivos.
2) Nas configurações do repositório -> Pages -> Fonte: `gh-pages` branch ou `main` /docs folder.
3) Ou use a branch `main` e ative GitHub Pages para a pasta raiz.

Se quiser, eu posso:
- tentar baixar as imagens reais e substituir os placeholders aqui (posso falhar com algumas proteções do Tilda),
- ou gerar um repositório Git pronto com commits e um README.md personalizado.

Diga qual opção prefere que eu faça agora.
