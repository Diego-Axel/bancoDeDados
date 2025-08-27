# 🎓 Banco de Dados - Universidade

Este projeto faz parte das atividades da disciplina de **Banco de Dados** do curso de **Sistemas de Informação**.  
O objetivo é construir o **Diagrama Entidade-Relacionamento (DER)** para o cenário de uma **Universidade**, considerando os requisitos apresentados.

---

## 📌 Requisitos do Sistema

1. Um **Centro** possui um ou vários **Cursos**;  
2. Um **Centro** pode ter vários **Departamentos**;  
3. Um **Aluno** está matriculado em apenas **um Curso**;  
4. Um **Curso** possui vários **Componentes Curriculares**;  
5. Um **Componente Curricular** pode ser do tipo **Disciplina** ou do tipo **Atividade**;  
6. Um **Componente Curricular** pode ter vários **Requisitos** (expressão de requisitos);  
7. Um **Departamento** é responsável por vários **Componentes Curriculares**;  
8. Um **Docente** leciona em muitas **Turmas**;  
9. Uma **Turma** pode ter mais de um **Docente**;  
10. Uma **Turma** tem muitos **Alunos**;  
11. Uma **Turma** está associada a uma **Disciplina**;  
12. **Alunos** podem estar em muitas **Turmas**;  
13. Uma **Turma** pode ter mais de um **Aluno Monitor**;  
14. Um **Aluno Monitor** só trabalha em **uma Turma**;  
15. Um **Docente** está vinculado a apenas **um Departamento**;  
16. Um **Departamento** possui muitos **Docentes**;  
17. Um **Aluno** tem **3 notas** em uma turma e uma **situação (APROVADO ou REPROVADO)**.  

---

## 📊 Modelo Entidade-Relacionamento (DER)

O DER foi construído a partir dos requisitos acima, representando as entidades principais (**Centro, Curso, Departamento, Aluno, Docente, Componente Curricular, Turma, Monitoria, Avaliação**), bem como seus relacionamentos e cardinalidades.

---

## 👨‍🏫 Professor
- **Taciano** – Disciplina de Banco de Dados  
- Curso: **Sistemas de Informação**

---

Projeto acadêmico desenvolvido para fins educacionais.