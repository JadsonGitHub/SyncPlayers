# 📊 Diagramas UML do Sistema

> Visão Geral

## 🔹 Diagrama de Casos de Uso

:white_circle: [DIAGRAMA DE CASOS DE USO (PNG)](./DiagramaCasodeUso/Diagrama%20Caso%20de%20Uso.png)

> Ferramenta: LucidChart


| Nome                   | Ator    | Descrição breve                        |
| ---------------------- | ------- | -------------------------------------- |
| Fazer Login            | Jogador | Permite acesso ao sistema              |
| Fazer Cadastro         | Jogador | Permite acesso ao sistemas             |
| Editar Perfil          | Jogador | Permite inserir informações no sistema |
| Buscar Jogadores       | Jogador | Permite integração entre usuários      |
| Visualizar Perfil      | Jogador | Permite obter informações de usuários  |
| Verificar Login        | Sistema | Permite validar o acesso ao sistema    |
| Cadastrar Jogos        | Jogador | Permite listar preferências            |
| Cadastrar Estilos      | Jogador | Permite listar preferências            |
| Cadastrar Horários     | Jogador | Permite listar preferências            |
| Cadastrar Plataformas  | Jogador | Permite listar preferências            |
| Filtrar por Plataforma | Jogador | Permite selecionar preferências        |
| Filtrar por Região     | Jogador | Permite selecionar preferências        |
| Filtrar por Jogos      | Jogador | Permite selecionar preferências        |
| Enviar Convites        | Jogador | Permite comunicação entre usuários     |
| Conversar com Jogadores| Jogador | Permite comunicação entre usuários     |
| Avaliar Jogadores      | Jogador | Permite rankear usuários               |
| Bloquear Jogadores     | Jogador | Permite gerenciar preferências         |
| Sugerir Jogadores      | Sistema | Permite integração entre usuários      |
| Gerenciar Chat         | Sistema | Permite boa experiência ao usuário     |
| Eviar Notificações     | Sistema | Permite integração entre usuários      |

## 🔹 Diagrama de Atividade

### Fluxo de Ações

> Ferramenta: LucidChart

| Nome                                                                         | Obs                               |
| ---------------------------------------------------------------------------- | --------------------------------- |
| [Buscar Jogadores](./DiagramaDeAtividade/DiagramaDeATVbuscarJogadores.png)   | Filtro, Sugestões e Notificações  |
| [Editar Perfil](./DiagramaDeAtividade/DiagramaDeATVeditarPerfil.png)         | Preferências                      |
| [Acessar](./DiagramaDeAtividade/DiagramaDeATVloginCadastro.png)              | Cadastro, Login                   |
| [Enviar Mensagem](./DiagramaDeAtividade/DiagramaDeATVmensagem.png)           | Chat, Notificação                 |
| [Vizualizar Perfil](./DiagramaDeAtividade/DiagramaDeATVvisualizarPerfil.png) | Vizualização, Bloqueio, Avaliação |

## 🔹 Diagrama de Classes

### Módulo de Usuário

> BREVE DESCRIÇÃO/LEGENDA

[ADICIONAR IMAGEM OU CODIGO (EXEMPLO)]([./DiagramaCasodeUso/Diagrama%20Caso%20de%20Uso.png)

## 🔹 Diagrama de Estados

### TITULO DO DIAGRAMA

> Mostra os estados possíveis de cada entidade [ex: login] e as transições entre eles.

| Nome                            | Finalidade / Obs  |
| ------------------------------- | ----------------- |
| [Status Usuário](./DE_login.md) | Status do usuário |
| A2                              | B2                |
| A3                              | B3                |

