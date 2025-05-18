# Spotifei

Spotifei — Projeto em java de um gerenciador de musicas 

Projeto de aplicação desktop feito em Java com interface Swing e banco de dados PostgreSQL.

Funcionalidades:

✅ Cadastro e login de usuários

✅ Buscar músicas por nome

✅ Curtir e descurtir músicas

✅ Criar playlists personalizadas

✅ Adicionar músicas a playlists

✅ Visualizar playlists e seu conteúdo

✅ Histórico de buscas, curtidas e descurtidas


 Estrutura do Projeto

spotifei/
├── controller/
│   └── UsuarioController.java
│   └── MusicaController.java
│   └── PlaylistController.java
│   └── HistoricoController.java
│
├── model/
│   └── Usuario.java
│   └── Musica.java
│   └── Playlist.java
│   └── Historico.java
│
├── repository/
│   └── Conexao.java
│   └── UsuarioRepository.java
│   └── MusicaRepository.java
│   └── PlaylistRepository.java
│   └── HistoricoRepository.java
│
├── view/
│   └── TelaLogin.java
│   └── TelaCadastro.java
│   └── TelaPrincipal.java
│   └── TelaPlaylist.java
│   └── TelaHistorico.java
│
└── Main.java

Modo de uso:

Se for rodar o codigo clone esse repositorio e conecte o banco de dados.
Todas as tables e inserts estao no arquivo txt.

Feito por:

Felipe Franco Falcon 
RA: 22 125 073 - 1 
