# NAJUÉ FRAGRANC’E — protótipo visual atualizado

## O que esta edição inclui
- Identidade visual floral em rosa claro, vermelho framboesa e vinho.
- Catálogo inicialmente vazio, pronto para receber produtos reais.
- Categorias iniciais: Perfumes Femininos, Perfumes Masculinos, Unissex e Body Splash.
- Painel local para cadastrar produtos, preços, volume, descrição, estoque e fotos.
- Gerenciamento local de categorias (adicionar, renomear e excluir categorias sem produtos associados).
- Pesquisa, filtros, sacola e encaminhamento do pedido pelo WhatsApp.
- O WhatsApp informado para a loja aparece preenchido nas configurações; confira antes de divulgar.
- Assistente simples de rascunho que organiza texto colado; não é uma integração real de IA.

## Limitações importantes
Este ZIP é um protótipo estático independente, baseado no arquivo inicial fornecido. Ele **não é a cópia completa do projeto atualmente publicado na Netlify** e não atualiza o endereço atual automaticamente.

Os produtos, categorias, carrinho e configurações são salvos apenas no armazenamento local do navegador. Isso significa que os produtos cadastrados em um celular não aparecem para outros clientes ou dispositivos. O painel também não tem autenticação segura nesta versão. Não use este protótipo como loja pública de produção nem substitua o projeto atual da Netlify por ele sem antes implementar banco de dados online, autenticação e regras de segurança.

Pagamentos online, confirmação automática de Pix, integração real de IA, sincronização entre dispositivos, estoque centralizado e gestão online de pedidos ainda não estão implementados.

## Testar
Extraia o ZIP e abra `index.html` em um navegador. Para usar service worker/PWA, sirva a pasta por HTTPS ou servidor local.

## Próximas etapas técnicas
1. Criar um ambiente de teste separado do site publicado.
2. Configurar banco de dados e autenticação (por exemplo, Supabase) com regras de acesso.
3. Hospedar imagens e sincronizar produtos/categorias/pedidos entre clientes e dispositivos.
4. Configurar integração de pagamento apenas por backend seguro e webhook verificado.
5. Integrar IA por backend, sem expor chaves no navegador.
6. Testar cadastro, estoque, carrinho, pedidos, segurança e acessibilidade antes de produção.
