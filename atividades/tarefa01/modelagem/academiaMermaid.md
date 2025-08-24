```mermaid
flowchart TD
    n3["Filled Circle"] --- n1["Instrutor"]
    n4["cpf"] --- n3
    n5["Small Circle"] --- n1
    n6["cref"] --- n5
    n7["Small Circle"] --- n1
    n8["endereco"] --- n7
    n9["Small Circle"] --- n1
    n10["nome"] --- n9
    n11["Small Circle"] --- n1
    n12["sexo"] --- n11
    n14["Filled Circle"] --- n13["Aluno"]
    n15["cpf"] --- n14
    n16["Small Circle"] --- n13
    n19["endereco"] --- n16
    n26["Small Circle"] --- n13
    n23["sexo"] --- n26
    n27["Small Circle"] --- n13
    n21["nome"] --- n27
    n2["Orienta"] --- n1 & n13
    n31["Possui"] --- n13
    n30["Realiza"] --- n13 & n28["Avaliação"]
    n29["Ficha de Treino"] --- n31
    n1 --- n32["Faz"]
    n32 --- n29
    n39["Filled Circle"] --- n28
    n40["cod (PK - SERIAL)"] --- n39
    n42["Small Circle"] --- n41["objetivo"] & n28
    n45["Small Circle"] --- n28
    n47["altura"] --- n45
    n43["Small Circle"] --- n28
    n49["imc"] --- n43
    n46["Small Circle"] --- n28
    n48["peso"] --- n46
    n50["Small Circle"] --- n28
    n51["data"] --- n50
    n53["Filled Circle"] --- n28
    n54["cpf (FK)"] --- n53
    n52["Small Circle"] --- n28
    n55["nome"] --- n52
    n57["Possui"] --- n29 & n56["Treino"]
    n56 --- n58["Contém"]
    n58 --- n59["Exercício"]
    n64["Filled Circle"] --- n56
    n65["idTreino"] --- n64
    n66["Small Circle"] --- n56
    n69["Small Circle"] --- n56
    n67["nome"] --- n66
    n68["descricao"] --- n69
    n71["idExercicio"] --- n70["Filled Circle"]
    n70 --- n59
    n72["Small Circle"] --- n73["nome"] & n59
    n77["Small Circle"] --- n74["series"] & n59
    n79["Small Circle"] --- n75["repeticoes"] & n59
    n78["Small Circle"] --- n59
    n76["carga"] --- n78
    n81["idFicha"] --- n80["Filled Circle"]
    n80 --- n29
    n24["(1,n)"]
    n25["(1,1)"]
    n33["(1,n)"]
    n34["(1,1)"]
    n35["(1,1)"]
    n36["(1,n)"]
    n37["(1,n)"]
    n38["(1,1)"]
    n60["(1,n)"]
    n61["(1,n)"]
    n62["(1,n)"]
    n63["(1,n)"]
    n3@{ shape: f-circ}
    n1@{ shape: rounded}
    n4@{ shape: text}
    n5@{ shape: sm-circ}
    n6@{ shape: text}
    n7@{ shape: sm-circ}
    n8@{ shape: text}
    n9@{ shape: sm-circ}
    n10@{ shape: text}
    n11@{ shape: sm-circ}
    n12@{ shape: text}
    n14@{ shape: f-circ}
    n13@{ shape: rounded}
    n15@{ shape: text}
    n16@{ shape: sm-circ}
    n19@{ shape: text}
    n26@{ shape: sm-circ}
    n23@{ shape: text}
    n27@{ shape: sm-circ}
    n21@{ shape: text}
    n2@{ shape: diam}
    n31@{ shape: diam}
    n30@{ shape: diam}
    n28@{ shape: rounded}
    n29@{ shape: rounded}
    n32@{ shape: diam}
    n39@{ shape: f-circ}
    n40@{ shape: text}
    n42@{ shape: sm-circ}
    n41@{ shape: text}
    n45@{ shape: sm-circ}
    n47@{ shape: text}
    n43@{ shape: sm-circ}
    n49@{ shape: text}
    n46@{ shape: sm-circ}
    n48@{ shape: text}
    n50@{ shape: sm-circ}
    n51@{ shape: text}
    n53@{ shape: f-circ}
    n54@{ shape: text}
    n52@{ shape: sm-circ}
    n55@{ shape: text}
    n57@{ shape: diam}
    n56@{ shape: rounded}
    n58@{ shape: diam}
    n59@{ shape: rounded}
    n64@{ shape: f-circ}
    n65@{ shape: text}
    n66@{ shape: sm-circ}
    n69@{ shape: sm-circ}
    n67@{ shape: text}
    n68@{ shape: text}
    n71@{ shape: text}
    n70@{ shape: f-circ}
    n72@{ shape: sm-circ}
    n73@{ shape: text}
    n77@{ shape: sm-circ}
    n74@{ shape: text}
    n79@{ shape: sm-circ}
    n75@{ shape: text}
    n78@{ shape: sm-circ}
    n76@{ shape: text}
    n81@{ shape: text}
    n80@{ shape: f-circ}
    n24@{ shape: text}
    n25@{ shape: text}
    n33@{ shape: text}
    n34@{ shape: text}
    n35@{ shape: text}
    n36@{ shape: text}
    n37@{ shape: text}
    n38@{ shape: text}
    n60@{ shape: text}
    n61@{ shape: text}
    n62@{ shape: text}
    n63@{ shape: text}
