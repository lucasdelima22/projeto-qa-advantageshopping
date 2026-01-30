# language: pt
# PROJETO DE TESTES - ADVANTAGE SHOPPING

```gherkin

Funcionalidade: Persistência de Sessão - Analisar se ao duplicar a aba no mesmo navegador a sessão de usuário se mantém.
  Cenário: Persistir login ao duplicar aba do navegador.
    Dado: O usuário loga no site.
    Quando: Abre uma guia duplicada do site no mesmo navegador.
    Então: Sistema deve manter o usuário logado.
    REsultado: A sessão de usuário não se mantém, o usuário terá que logar novamente.



```
