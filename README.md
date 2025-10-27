# 🐔🚗 Freeway

Recriação do clássico jogo **Freeway** do Atari 2600, desenvolvido em **GDScript** utilizando a **Godot Engine**. O objetivo é atravessar a rodovia movimentada sem ser atropelado pelos carros!

## 🔗 Deploy

Visualize agora: [**Freeway**](https://www.youtube.com/watch?v=Y1YSnnH31XY)

## 🎮 Sobre o Jogo

Freeway é um clássico dos videogames lançado originalmente em 1981 para o Atari 2600. Nesta versão recriada, o jogador controla uma galinha que precisa atravessar uma rodovia cheia de carros em alta velocidade. Quanto mais você atravessar, maior sua pontuação!

### Como Jogar

- **Setas ↑ ↓**: Movimentar a galinha para cima ou para baixo
- **Objetivo**: Atravesse a rodovia sem ser atropelado
- **Pontuação**: Cada travessia bem-sucedida aumenta seu score

## 🚀 Tecnologias Utilizadas

- **Godot Engine** - Motor de jogo 2D/3D
- **GDScript** - Linguagem de programação nativa do Godot
- **Pixel Art** - Arte em estilo retrô

## ✨ Funcionalidades

- Sistema de movimentação suave do jogador
- Carros com velocidades variadas
- Sistema de colisão e detecção de atropelamento
- Contador de pontuação
- Reset do jogo ao ser atropelado
- Visual retrô inspirado no jogo original

## 💡 Conceitos de Game Dev Aplicados

- **Física 2D**: Movimentação e colisões
- **Cenas e Nós**: Estruturação de objetos no Godot
- **Sinais (Signals)**: Comunicação entre objetos
- **Instanciação**: Criação dinâmica de carros
- **Game Loop**: Ciclo principal do jogo
- **Collision Detection**: Detecção de colisões entre objetos

## 🛠️ Como Executar o Projeto

### Pré-requisitos

- [Godot Engine](https://godotengine.org/download) (versão 3.x ou 4.x)

### Passos

1. Clone o repositório:
```bash
git clone https://github.com/herculanaline/freeway.git
```

2. Navegue até o diretório do projeto:
```bash
cd freeway
```

3. Abra o projeto no Godot Engine:
   - Abra o Godot
   - Clique em "Import"
   - Navegue até a pasta do projeto
   - Selecione o arquivo `project.godot`

4. Pressione **F5** ou clique em "Play" para jogar!

## 📂 Estrutura do Projeto

```
freeway/
├── scenes/
│   ├── Main.tscn
│   ├── Player.tscn
│   └── Car.tscn
├── scripts/
│   ├── main.gd
│   ├── player.gd
│   └── car.gd
├── assets/
│   ├── sprites/
│   └── sounds/
├── project.godot
└── README.md
```

## 🎯 Desafios e Melhorias Futuras

- [ ] Adicionar níveis de dificuldade crescente
- [ ] Implementar sistema de vidas
- [ ] Adicionar efeitos sonoros e música
- [ ] Criar power-ups especiais
- [ ] Adicionar tabela de recordes (high score)
- [ ] Implementar modo multiplayer local

## 📸 Screenshots

<img width="1272" height="678" alt="image" src="https://github.com/user-attachments/assets/a729de1b-e65c-41da-b564-f6a432130d77" />

## 🎓 Aprendizados

Este projeto me permitiu desenvolver habilidades em:

- Fundamentos de desenvolvimento de jogos 2D
- Programação em GDScript
- Utilização da Godot Engine
- Implementação de física e colisões
- Gerenciamento de estados do jogo
- Criação de mecânicas de gameplay clássicas
- Design de jogos retrô

## 🎮 Sobre o Jogo Original

Freeway foi lançado em 1981 pela Activision para o Atari 2600. O jogo foi desenvolvido por David Crane e tornou-se um dos clássicos atemporais dos videogames, conhecido por sua simplicidade viciante e desafio crescente.

## 👩‍💻 Autora

**Hercúlana Line**

- GitHub: [@herculanaline](https://github.com/herculanaline)
- LinkedIn: [aline_herculano](https://www.linkedin.com/in/aline-herculano/)

## 📝 Licença

Este projeto foi desenvolvido para fins educacionais e de portfólio.

---

🎮 Desenvolvido com paixão por games clássicos | Powered by [Godot Engine](https://godotengine.org/)
