# Trabalho-Final
Trabalho Prático: Programação de Soluções Computacionais



Estrutura do Trabalho

1. Proposta de Problema:
   Desenvolver um sistema que permita a uma biblioteca de faculdade gerenciar empréstimos e devoluções de livros, bem como o cadastro de novos livros e alunos.

2. Requisitos Funcionais:
   Utilizando uma IA Generativa (como ChatGPT), identificamos os seguintes requisitos funcionais para o sistema de biblioteca:
   - Cadastro de livros e alunos.
   - Empréstimo de livros.
   - Devolução de livros.
   - Consulta de disponibilidade de livros.
   - Geração de relatórios de empréstimos.

3. Crítica à IA:
   A IA foi eficaz em identificar os requisitos funcionais principais para o sistema de biblioteca. No entanto, a precisão e a utilidade das sugestões podem variar dependendo da clareza do enunciado do problema e das instruções fornecidas. É essencial verificar se todos os requisitos relevantes foram capturados e se há alguma funcionalidade adicional necessária.

4. Diagrama de Classes:
   Descrição textual do diagrama de classes para o sistema de biblioteca:

   - Classe Livro:
     - Propriedades:
       - String titulo: Título do livro.
       - String autor: Autor do livro.
       - boolean emprestado: Indica se o livro está emprestado.
     - Métodos:
       - Livro(String titulo, String autor): Construtor da classe.
       - String getTitulo(), String getAutor(),  boolean isEmprestado(), void setEmprestado(boolean emprestado): Métodos para acessar e modificar as propriedades.

   - Classe Aluno:
     - Propriedades:
       - String nome: Nome do aluno.
       - String matricula: Matrícula do aluno.
     - Métodos:
       - Aluno(String nome, String matricula): Construtor da classe.
       - String getNome(), String getMatricula(): Métodos para acessar as propriedades.

   - Classe Biblioteca:
     - Propriedades:
       - List<Livro> livros: Lista de livros cadastrados.
       - List<Aluno> alunos: Lista de alunos cadastrados.
       - Map<Livro, Aluno> emprestimos: Mapa que relaciona livros emprestados com os alunos.
     - Métodos:
       - void cadastrarLivro(String titulo, String autor): Cadastra um novo livro.
       - void cadastrarAluno(String nome, String matricula): Cadastra um novo aluno.
       - void emprestarLivro(String titulo, String matricula): Realiza o empréstimo de um livro.
       - void devolverLivro(String titulo): Realiza a devolução de um livro.
       - void consultarDisponibilidade(String titulo): Consulta a disponibilidade de um livro.
       - void gerarRelatorioEmprestimos(): Gera um relatório dos empréstimos.
       - Livro encontrarLivro(String titulo), Aluno encontrarAluno(String matricula): Métodos auxiliares para encontrar livro e aluno.
       - void salvarDados(), void carregarDados(): Métodos para salvar e carregar os dados.

5. Estratégia de Programação com IA:
   - Revisão de Código: Escrever o código e solicitar à IA uma revisão para encontrar erros ou melhorias.
   - Programação por Pares com IA: Trabalhar em conjunto com a IA, solicitando sugestões de código e implementações para resolver partes específicas do problema.
   - Estudo Assistido por IA: Utilizar a IA para obter explicações sobre conceitos difíceis ou solicitar exemplos de exercícios para praticar.

6. Codificação do Programa:
   - A codificação foi realizada utilizando a linguagem Java, implementando todos os requisitos funcionais identificados. O código foi estruturado com classes bem definidas e métodos claros para cada funcionalidade do sistema.
