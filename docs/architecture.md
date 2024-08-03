# Arquitetura do Gestão de Livros Acadêmicos

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

Biblioteca/
├── Biblioteca_Academica_Py/
│   ├── ARQUIVOS/
│   │   ├── _BIBLIOTECAS/         # Livros referenciados
│   │   ├── tmp/                  # Livros não referenciados e lixo
│   ├── db/                       # Módulo de banco de dados
│   ├── formatacao/               # Módulo para formatação de referências
│   ├── interfaces/               # Módulo de configuração e interação com interfaces externas
│   ├── import_export/            # Módulo para importação e exportação
│   ├── organizacao/              # Módulo para organização e pesquisa
│   ├── referencias/              # Módulo para manipulação de referências
│   ├── utils/                    # Módulo para funções utilitárias
├── docs/                         # Documentação do projeto



### Descrição dos Módulos

- **db/**: Contém scripts e configurações para a interação com o banco de dados.
- **formatacao/**: Inclui funções e classes para formatação de referências.
- **interfaces/**: Gerencia configurações e interações com interfaces externas.
- **import_export/**: Módulo responsável pela importação e exportação de dados.
- **organizacao/**: Ferramentas para organização e pesquisa dentro da biblioteca.
- **referencias/**: Manipulação de referências de livros e outros materiais.
- **utils/**: Funções utilitárias que suportam outros módulos.

## Fluxo de Trabalho

1. **Adição de Livros**: Os livros são adicionados na pasta `ARQUIVOS/_BIBLIOTECAS/` e seus metadados são catalogados no banco de dados.
2. **Importação/Exportação**: O módulo de importação/exportação gerencia a entrada e saída de dados, garantindo a integração com outras ferramentas e formatos.
3. **Organização**: Os livros são organizados por categorias, autores e outros critérios definidos.
4. **Formatação de Referências**: As referências são formatadas de acordo com padrões acadêmicos.

Para mais detalhes sobre cada módulo e sua funcionalidade, consulte os arquivos de documentação dentro de cada pasta ou entre em contato através das issues.
