Título:
# Projeto de Desenvolvimento - TDSV3

## Descrição do Projeto

Este projeto realiza a coleta e análise de dados históricos do Bitcoin (BTC) utilizando a API da OKX. Ele permite visualizar informações sobre preços e volumes de negociação de forma estruturada, facilitando análises financeiras e de mercado.


## Tecnologias Utilizadas

- **Linguagem**: Python 3
- **Bibliotecas**: requests, pandas, matplotlib, datetime, pytz
- **Fonte de Dados**: API da OKX
- **IDE**: VS Code
- **Deploy**: GitHub


## Estrutura do Projeto

├── projeto_desenvovlimento_tdsv3/
│   ├── bitcoin_analysis.py  # Script principal de coleta e análise
│   ├── requirements.txt     # Lista de dependências
│   ├── README.md            # Documentação do projeto


## Funcionalidades do Projeto

- **Coleta de Dados**: Obtém informações sobre preço de fechamento e volume de negociação do Bitcoin nos últimos 100 dias.
- **Processamento dos Dados**: Formata timestamps, converte valores e cria um DataFrame estruturado.
- **Análise e Exibição**: Permite visualizar os primeiros registros, acessar linhas específicas, remover e adicionar registros.
- **Gráficos**: Gera visualizações dos dados históricos coletados.

  
## Contribuição

Contribuições são bem-vindas! Para contribuir:

Faça um fork do repositório
Crie uma branch para sua funcionalidade (git checkout -b minha-feature)
Faça o commit das suas alterações (git commit -m 'Adicionando nova feature')
Faça um push para a branch (git push origin minha-feature)
Abra um Pull Request 🚀


## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

