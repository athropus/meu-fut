# Meu Fut — prévia web 4.0

## Publicar no GitHub + Vercel
1. Crie um repositório no GitHub e envie `index.html`.
2. Na Vercel, importe o repositório e escolha **Other** / site estático, sem build command.
3. Publique e abra o endereço HTTPS no celular.

## Estado atual
- Interface local com tela inicial, menu de acesso por código e relatório imprimível em PDF.
- As regras da pelada continuam no HTML original, com dados em `localStorage`.
- **Ainda não há** login real, salas online, código válido, sincronização entre dispositivos nem exclusão automática em 24 horas.
- Não use o site para organizar uma pelada compartilhada antes da etapa do servidor.

## Próxima etapa
Configurar projeto Supabase, autenticação, tabelas de salas/jogadores/partidas, políticas de acesso e operações atômicas; depois integrar com este frontend. Não colocar chave `service_role` no navegador.
