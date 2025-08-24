```mermaid
flowchart TD
    n1["Aluno"] --- n2["Academia"] & n5["Treino"]
    n2 --- n3["Instrutor"]
    n4["Avaliação"] --- n1
    n1@{ shape: rounded}
    n2@{ shape: rounded}
    n5@{ shape: rounded}
    n3@{ shape: rounded}
    n4@{ shape: rounded}
