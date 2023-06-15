# Y.Afisha
Análise de negócio da Y.Afisha para otimizar as despesas com marketing

Neste projeto analisei os logs do servidor com dados sobre os acessos a Y.Afisha de janeiro de 2017 até dezembro de 2018, o arquivo de despejo com todos os pedidos feitos durante o período e as estatísticas de despesas
com marketing para para otimizar as despesas com marketing e responder:
- Como as pessoas usam o produto
- Quando elas começam a comprar
- Quanto dinheiro cada cliente traz para a empresa
- Quando as despesas serão cobertas

### Descrição dos dados

A tabela visits (os logs do servidor com dados sobre os acessos ao site):
- Uid — identificador unívoco do usuário
- Device — dispositivo do usuário
- Start Ts — data e hora do início da sessão
- End Ts — data e hora do final da sessão
- Source Id — identificador da origem do anúncio através do qual o usuário chegou

A tabela orders (dados sobre os pedidos):
- Uid — identificador unívoco do usuário que faz um pedido
- Buy Ts — data e hora do pedido
- Revenue — a receita da Y.Afisha com o pedido

A tabela costs (dados sobre as despesas com marketing):
- source_id — identificador da origem de anúncio
- dt — data
- costs — despesas com esta origem de anúncio neste dia

### Bibliotecas usadas
- pandas
- numpy
- seaborn
- matplotlib
