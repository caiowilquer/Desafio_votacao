# Desafio Sicredi-API REST 

  
#  Objetivo

Gerenciar sessões de votação com os sequintes parametros:

- Cadastrar uma nova pauta;

- Abrir uma sessão de votação em uma pauta (a sessão de votação deve ficar aberta por um tempo 
determinado na chamada de abertura ou 1 minuto por default);

- Receber votos dos associados em pautas (os votos são apenas 'Sim'/'Não'. Cada associado é 
identificado por um id único e pode votar apenas uma vez por pauta);

- Contabilizar os votos e dar o resultado da votação na pauta.


# Banco de Dados
   -Ja esta configurado pra criar todas as tabelas ao executar


# Tecnologias
    - Linguagem de programação Java(versão 8)
    - SpringFramework (SpringBoot ) →(Boot para facilitar construção da API REST)
    - Hibernate →(Para realizar o gerenciamento do Banco de Dados)
    - API REST →(Para comunicação seguindo os padrões REST "Requisição e Resposta")
    - Ecplise →(Para o código em si)
    - Postman →(Testarmos nossas requisições)
    - jUnit →(Realizão de testes unitarios)


# Funcionamento da API

- O administrador possui o controle sobre as pautas. O mesmo pode cadastrar,buscar ou deletar pautas ou associados.
- Cada associado tem direito a apenas 1 voto por pauta,como as pautas possuem a duração de apenas 1 minuto setei para que o associado possa votar em uma nova pauta assim que a anterior estiver finalizada. 
 
 