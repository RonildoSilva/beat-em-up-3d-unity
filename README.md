# Beat 'em up 3D em Unity

> Protótipo de jogo de luta 3D no estilo beat 'em up: movimentação do jogador, combos de socos e chutes e inimigos que perseguem e atacam.

![status](https://img.shields.io/badge/status-protótipo-yellow) ![unity](https://img.shields.io/badge/Unity-2020%2B-black) ![csharp](https://img.shields.io/badge/C%23-scripts-blue)

![Cena](./Pictures/src_001.png)

## Sobre
Projeto de estudo de desenvolvimento de jogos em Unity (2022), seguindo um curso. Foram implementados o controle do personagem, uma máquina de estados de combo (três socos e dois chutes, com janela de 0,4 s para encadear o próximo golpe), o controlador de animações e a IA básica dos inimigos (perseguir até 1,8 m, atacar em intervalos de 2 s).

## Stack
- Unity (C#), Rigidbody e Animator
- Modelos, animações e efeitos de acerto fornecidos pelo material do curso

## Estrutura de pastas
```text
Assets/
├── Scenes/SampleScene.unity              cena de teste
├── Scripts/Player Script/PlayerMovement.cs, PlayerAttack.cs, CharacterAnimation.cs
├── Scripts/EnemyScript/EnemyMovement.cs
├── Scripts/Helper Script/TagManager.cs   tags usadas nos scripts
├── Models/{Player,Enemy,Environment}/    FBX, animações e controladores
└── Hit FX/                               efeito de impacto
Pictures/                                 capturas de tela
```

## Como executar
Abra a pasta no Unity Hub e carregue `Assets/Scenes/SampleScene.unity`.

## Status
Protótipo. O desenvolvimento parou após a IA de movimentação dos inimigos; faltam vida, dano, HUD e níveis.

## Autor
Ronildo Silva · ronildo.comp@gmail.com
