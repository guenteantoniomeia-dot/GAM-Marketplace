# GAM — Possibilidade Imediata (MVP inicial)

## O que esta versão já demonstra
- Página inicial responsiva com identidade preta e dourada
- Pesquisa e filtros por categoria
- Catálogo inicial de exemplo
- Formulário para adicionar produtos
- Carrinho demonstrativo
- Manifesto e service worker para preparar instalação como PWA

## Limitações importantes
Esta é uma primeira versão de interface e demonstração local. Os produtos são guardados no armazenamento do navegador do dispositivo; ainda não são partilhados entre utilizadores. Não inclui autenticação real, base de dados online, upload de fotografias, checkout, pagamentos M-Pesa/e-Mola, chat real ou painel administrativo seguro.

## Publicar
Carregue `index.html`, `manifest.json` e `sw.js` para a raiz do repositório GitHub. Depois ligue o repositório a um serviço de alojamento estático compatível com páginas HTML. A aplicação precisa de HTTPS para instalar como PWA.
