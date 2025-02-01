# Projeto Spotify Clone

Este é um projeto Android desenvolvido com Kotlin, que replica a experiência de uso do Spotify. O objetivo principal é permitir que os usuários se autentiquem, explorem músicas, álbuns, playlists e toquem músicas diretamente no aplicativo.

## Descrição

O aplicativo permite o login via OAuth 2.0 com a API do Spotify e oferece funcionalidades para explorar playlists, álbuns e músicas, além de um player básico para tocar as músicas e salvar favoritas. Este projeto segue a arquitetura MVVM e utiliza diversas bibliotecas do Android, como ExoPlayer, DataStore e outras ferramentas modernas.

## Funcionalidades

### Fase 1: Configuração Inicial e Autenticação
- **Login via Spotify** utilizando OAuth 2.0.
- **Armazenamento de token de acesso** com DataStore.
- **Tela inicial pós-login** exibindo informações básicas do perfil do usuário.

### Fase 2: Exploração de Músicas e Playlists
- **Busca por playlists, álbuns, músicas e artistas**.
- **Exibição de resultados organizados por tipo** (músicas, álbuns, artistas).
- **Tela de detalhes** com informações sobre cada item.

### Fase 3: Player de Música
- **Player de música básico** com ExoPlayer para tocar prévias.
- **Mini player fixo** com informações sobre a música atual.
- **Tela completa do player** com controles avançados e barra de progresso.

### Fase 4: Favoritos e Histórico
- **Funcionalidade de Favoritos**: salvar músicas favoritas e exibi-las em uma tela específica.
- **Histórico de reprodução**: registrar músicas tocadas e exibi-las em uma tela de histórico.

### Fase 5: Melhorias e Funcionalidades Avançadas (Opcional)
- **Recomendações personalizadas** com base no histórico do usuário.
- **Suporte offline**: permitir o armazenamento de músicas favoritas para reprodução offline.
- **Melhoria de UI/UX** com animações e efeitos visuais.
- **Testes unitários e instrumentados** para as funcionalidades principais.

## Tecnologias Utilizadas

- **Kotlin**: Linguagem principal para desenvolvimento.
- **Android Studio**: Ambiente de desenvolvimento.
- **MVVM**: Arquitetura utilizada para separação de responsabilidades.
- **ExoPlayer**: Biblioteca para reprodução de músicas.
- **DataStore**: Armazenamento local de dados como token de acesso, favoritos e histórico.
- **Spotify API**: Para integração com o Spotify e autenticação via OAuth 2.0.