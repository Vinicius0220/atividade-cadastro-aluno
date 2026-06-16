# Checkpoint V - Model binding

## Formulário de Cadastro de Aluno
1. Crie Models/Aluno.cs com: Nome, Email, RA, Curso e DataNascimento
2. Adicione Data Annotations: [Required], [EmailAddress], [StringLength]
3. Crie Controllers/AlunoController.cs
4. Crie o método [HttpGet] Cadastrar() que retorna a View vazia
5. Crie o método [HttpPost] Cadastrar(Aluno aluno) que valida com ModelState