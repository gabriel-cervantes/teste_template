### Código externo
> OS 9961

### Problema
> Erro ao gerar relatório de movimentação de caixa detalhado e registro de inventário.
Quando acessa uma filial pelo multilojas os relatórios de movimentação de caixa detalhado e registro de inventário mostram as informações da loja local e não da que se está acessando.
Por exemplo, estou na matriz e conecto na filial, gero o relatório conectado (multilojas) na filial mas as informações são geradas da matriz.

> Outro problema é que esses relatórios utilizam o Gerador de Relatórios, e este projeto não está seguindo o padrão dos demais projetos. A conexão do banco de dados utilizada no Gerador de Relatórios é passado assim que aberto a tela de login, e quando trocado para utilizar uma filial do multilojas, não é alterado essa conexão.

### Solução
> Toda vez que for utilizar o Gerador de Relatórios, passar a conexão por parâmetro.

- [x] Tem OS
- [ ] Tem SM
- [ ] Importação Navi - Link
- [ ] Aprovada
- [ ] Testado
- [x] [Histórico de versões preenchido](https://docs.google.com/spreadsheets/d/1ilGvt5QhkrIqFddupZnBW5gmI18WaOQTIg6CtTcMVbQ/edit#gid=0&range=36:36)
- [ ] Roadmap
- [x] Não planejada
