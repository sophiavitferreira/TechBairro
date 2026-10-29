# TechBairro — Sistema de Cadastro de Clientes

## 1. Sobre o projeto

O TechBairro é um sistema desenvolvido em Python para auxiliar no gerenciamento de clientes. O projeto tem como objetivo facilitar o cadastro, a consulta, a alteração e a exclusão de informações, utilizando uma interface gráfica simples e organizada.

O sistema foi desenvolvido como parte das atividades do curso Técnico em Desenvolvimento de Sistemas do SENAC, com foco na aplicação dos conhecimentos de programação, banco de dados, validação de dados, testes e organização de código.

## 2. Funcionalidades

- Cadastro de clientes.
- Consulta de clientes cadastrados.
- Pesquisa de clientes pelo nome.
- Alteração dos dados dos clientes.
- Exclusão de registros.
- Validação dos dados informados.
- Armazenamento de informações utilizando SQLite.
- Interface gráfica para facilitar a utilização do sistema.

## 3. Tecnologias utilizadas

- **Python:** linguagem de programação utilizada no desenvolvimento.
- **Tkinter:** criação da interface gráfica.
- **SQLite:** armazenamento dos dados dos clientes.
- **Git:** controle de versão do projeto.
- **GitHub:** hospedagem do repositório e acompanhamento do desenvolvimento.

## 4. Estrutura do projeto

O projeto está organizado nos seguintes arquivos:

- `techbairro.py` — arquivo principal do sistema e da interface gráfica.
- `banco.py` — módulo responsável pelas operações relacionadas ao banco de dados.
- `cliente.py` — módulo de gerenciamento de clientes.
- `validacao.py` — módulo responsável pela validação dos dados.
- `testar_validacao.py` — arquivo utilizado para executar os testes de validação.
- `CHANGELOG.md` — histórico de alterações e versões do projeto.
- `.gitignore` — define os arquivos e diretórios que não devem ser enviados ao GitHub.

## 5. Requisitos

Para executar o projeto, é necessário ter:

- Python 3 instalado.
- Um editor de código, como o Visual Studio Code.
- Os arquivos do projeto salvos na mesma estrutura de pastas.
- Os módulos e as dependências necessários para a execução do sistema.

O Tkinter e o SQLite fazem parte da biblioteca padrão das instalações comuns do Python, embora sua disponibilidade possa variar conforme a instalação e o sistema operacional.

## 6. Como executar o projeto

1. Baixe ou clone este repositório.
2. Abra a pasta do projeto no Visual Studio Code.
3. Verifique se o Python está instalado.
4. Abra o terminal na pasta do projeto.
5. Execute o arquivo principal com o comando:

```bash
python techbairro.py
```

Caso o comando acima não funcione no Windows, tente:

```bash
py techbairro.py
```

## 7. Testes

O projeto possui o arquivo `testar_validacao.py`, destinado à verificação das regras de validação dos dados.

Para executar os testes, utilize o terminal na pasta do projeto:

```bash
python testar_validacao.py
```

Os testes devem ser executados após alterações nas regras de validação para verificar se o comportamento esperado continua funcionando.

## 8. Controle de versão

O Git é utilizado para registrar as alterações realizadas no código e permitir a consulta ao histórico de desenvolvimento.

O arquivo `CHANGELOG.md` complementa esse processo, documentando as mudanças mais importantes de cada versão.

## 9. Segurança e organização

O arquivo `.gitignore` é utilizado para evitar o envio de arquivos desnecessários, como ambientes virtuais, arquivos temporários e bancos de dados locais.

Dados pessoais de clientes e outras informações confidenciais não devem ser publicados no repositório.

## 10. Autor

Projeto desenvolvido por Sophia Vitória Silva Ferreira, como parte das atividades do curso Técnico em Desenvolvimento de Sistemas do SENAC.

---

**TechBairro — Tecnologia e organização para o gerenciamento de clientes.**