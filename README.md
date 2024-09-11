Projeto Integrado - Sistema de Gerenciamento de Estoque

Descrição
Este é um sistema básico para gerenciar o estoque de produtos. O sistema permite adicionar, remover e atualizar produtos no estoque, bem como consultar o estoque atual.

Como Executar
1. Clone o repositório com o seguinte comando:
    bash
    git clone <url-do-repositorio>
    
2. Navegue até o diretório do projeto:
    bash
    cd Projetointegrado
    
3. Compile e execute o projeto usando Maven:
    bash
    mvn clean package
    java -jar target/Projetointegrado-1.0-SNAPSHOT.jar
    

Estrutura do Projeto
O projeto está organizado nas seguintes classes principais:

- Produto: Classe que representa um produto no estoque.
- Estoque: Gerencia a lista de produtos disponíveis.
- Cliente: Representa um cliente no sistema.
- Fornecedor: Gerencia os fornecedores dos produtos.
- Main: Classe principal responsável pela execução do sistema.

Funcionalidades Principais
- Adicionar novos produtos ao estoque.
- Remover produtos do estoque.
- Atualizar informações de produtos existentes.
- Consultar a lista de produtos disponíveis.

Escolhas de Design
O projeto foi desenvolvido com uma estrutura simples para facilitar a expansão futura. As principais classes foram separadas em diferentes componentes (Produto, Estoque, Cliente e Fornecedor) para manter a responsabilidade de cada classe clara e focada.

Ferramentas Utilizadas
- Maven: Gerenciamento de dependências e automação de compilação.
- Git: Controle de versão do código.
- Java: Linguagem de programação principal.

Processos de Software Adotados
- DAO (Data Access Object): Utilizado para acessar e gerenciar os dados de produtos e estoque. Isso separa a lógica de negócios da lógica de persistência de dados.
- Controle de versão (Git): O projeto foi versionado usando Git, permitindo o controle completo das alterações e colaboração com outros desenvolvedores.

Publicação no GitHub
Este projeto está publicado no GitHub. Para acessar, siga o link:


Link do Repositório:( https://github.com/larissa2256/Projeto-Integrado-2.git )
