```mermaid
erDiagram
    ALUNO {
        string cpf PK
        string nome
        string sexo
        string endereco
    }

    INSTRUTOR {
        string cref PK
        string cpf
        string nome
        string sexo
        string endereco
    }

    AVALIACAO {
        int id PK
        string objetivo
        float altura
        float peso
        float imc
        date data
        string cpf_aluno FK
    }

    FICHA_TREINO {
        int idFicha PK
        string cpf_aluno FK
    }

    TREINO {
        int idTreino PK
        string nome
        string descricao
        int idFicha FK
    }

    EXERCICIO {
        int idExercicio PK
        string nome
        int series
        int repeticoes
        float carga
        int idTreino FK
    }

    ALUNO ||--o{ AVALIACAO : "realiza"
    ALUNO ||--|| FICHA_TREINO : "possui"
    INSTRUTOR ||--o{ ALUNO : "orienta"
    FICHA_TREINO ||--o{ TREINO : "possui"
    TREINO ||--o{ EXERCICIO : "contém"