```mermaid
usecase "Sistema PreveAgro" {
    actor "Visitante" as V
    actor "Produtor Rural" as P

    // Casos de Uso
    uc1[Cadastrar-se]
    uc2[Fazer Login]
    uc3[Gerenciar Commodities]
    uc4[Visualizar Dashboard de Análise]
    uc5[Acessar Hub de Notícias]

    // Ações dos Atores
    V -- uc1  // O Visitante pode se cadastrar

    P -- uc2  // O Produtor Rural faz login
    P -- uc3  // O Produtor Rural gerencia suas commodities
    P -- uc4  // O Produtor Rural visualiza o dashboard
    P -- uc5  // O Produtor Rural acessa o hub de notícias

    // Relações <<include>>
    uc3 ..> uc2 : <<include>>
    uc4 ..> uc2 : <<include>>
    uc5 ..> uc2 : <<include>>
}
```
