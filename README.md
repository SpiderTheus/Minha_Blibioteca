# Minha_Blibioteca
Projeto Java com Maven, JPA/Hibernate e interface gráfica (JavaFX/Swing). Realiza CRUD de livros, busca dados em API externa e permite salvar citações favoritas. Segue arquitetura em camadas (Modelo, Repositório, Serviço e Controle). Utiliza banco relacional e visa estudo de UML e desenvolvimento orientado a objetos.
Requisitos do sistema de gerenciamento de livros.

RF01: O sistema deve realizar um crud com livros.

RF02: O sistema deve ter uma interfase gráfica .

RF03: O sistema deve ter um banco de dados relacional próprio ou em nuvem.

RF04: O sistema deve pegar o nome do livro e buscar as informações em alguma api ou banco de dados e salvar no próprio banco de dados.

RNF01: O sistema deve ser implementado em java.

RF05: O sistema deve permitir que o usuário coloque citações favoritas de acordo com o livro. 

### **Próximos Passos**

- [ ]  **Definir Casos de Uso UML:** Criar diagramas de classes e sequência.
- [ ]  **Modelagem Inicial:** Estruturar as entidades `Livro` e `Citação`.
- [ ]  **Prototipagem:** Configurar a interface gráfica básica.
- [ ]  **Integração Inicial:** Persistência com JPA e chamadas API REST.

Classes

- `Livro` (entidade principal)
- `Citação` (entidade associada)
- `RepositorioLivro` (interface para persistência)
- `ServicoLivro` (interface para lógica de negócios)
- `ControladorLivro` (manipulação da interface gráfica ou API)
