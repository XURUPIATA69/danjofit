# DanJoFIT — PWA de musculação

## O que está incluído
- Rotina de segunda a sexta, com múltiplos grupos musculares por dia.
- Exercícios personalizados, edição/exclusão e séries individuais com carga, repetições e caixa para marcar cada série como feita.
- Iniciar/finalizar treino e histórico datado.
- Estatísticas de volume, recordes pessoais e gráfico de cargas.
- Cronômetro de descanso configurável.
- Salvamento automático local e backup JSON.
- PWA com manifest, ícones SVG e service worker para cache offline.

## Publicar grátis no GitHub Pages
1. Descompacte `DanJoFIT.zip`.
2. Crie um repositório no GitHub, por exemplo `danjofit`.
3. Envie os arquivos e a pasta `icons` para a raiz do repositório (não envie a pasta `DanJoFIT` como subpasta).
4. No repositório, entre em **Settings → Pages**.
5. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
6. Aguarde o endereço HTTPS aparecer na seção Pages.

## Instalar
- **iPhone:** abra o link HTTPS no Safari → Compartilhar → Adicionar à Tela de Início → Adicionar.
- **PC (Chrome/Edge):** abra o link HTTPS e clique em Instalar na barra de endereço ou no botão “Instalar app” quando disponível.
- Abra uma vez online para carregar os arquivos e depois o app poderá abrir offline pelo cache.

## Como mudar o descanso
Abra **Ajustes → Tempo de descanso** e escolha 30 s, 45 s, 1, 1:30, 2, 3, 4 ou 5 minutos. O cronômetro também permite iniciar, pausar e reiniciar durante o treino. Ao tocar em “Descanso” em um exercício, o cronômetro aparece.

## Armazenamento e sincronização
Os dados são guardados automaticamente no `localStorage` do navegador/dispositivo. O iPhone e o PC **não sincronizam automaticamente entre si** nesta versão; use **Ajustes → Exportar backup** em um aparelho e **Importar backup** no outro. Guarde backups importantes em local seguro. Não há autenticação ou banco de dados em nuvem configurados.

## Limitações honestas
O cache offline depende de uma primeira abertura online e de o navegador manter os dados do site. A fonte DM Sans/Manrope é carregada externamente; o app continua funcional offline usando fontes de sistema. Esta versão foi montada para execução estática, sem backend.