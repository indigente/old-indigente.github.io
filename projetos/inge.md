---
layout: page
title: "InGE - Indigente Game Engine"
---

- Atividade: abril 2005 - abril 2007
- Agência financiadora: 
    - Recursos próprios
    - FAPESB (?)

O InGE, Indigente Game Engine, é um motor livre e multi-plataforma para o desenvolvimento de jogos 3D.

## Notícias

Atualmente o motor se encontra no SVN do Departamento de Ciência da Computação na UFBA. O download pode ser efetuado através do comando:

    svn co https://intranet.dcc.ufba.br/svn/indigente/trunk/libinge/ .

## Funções da Engine

- **REFACTORING** Carregar MD2 com suporte a Keyframes e Textura
- **OK** Carregar MD3 com suporte a Keyframes de Bones
- **OK** Carregar BSP de Quake 3
- **Em andamento** Funções de controle abstraindo a origem(Teclado, Mouse ou Joystick)
- Física
    + **Em andamento** Colisão
    + **OK** Gravidade
    + Atrito
- **OK** Limitar Área de Renderização da Camera
- **OK** Funções para PCs(Player Characters)
- **Em andamento** Funções para nPCs(non-Player Characters)
- **OK** Suporte para Multi-player
- Efeitos Especiais
    + Efeitos Sonoros e Músicas
    + Luz
        * **Em andamento** Per-vertex
        * Per-pixel
        * Lightmapping
        * Gloss maps
        * Anisotropic
    + Sombra
        + Shadow Volume
    + **Em andamento** Fog
    + Textura
        * **OK** Basic
        * **OK** Multi-texturing
        * **OK** Lightmaps lido do BSP
        * Bumpmapping
        * Mipmapping
    + Sistema de Particulas
    + **OK** Suporte para vídeos - SMPEG
    + Environment Mapping
    + Lens Flares
    + Billboarding
    + Sky
    + **Em andamento** Water
    + Decals
    + Mirror
- IA
- **Em andamento** Fazer interface gráfica com o usuário
- Desenvolver Formato de Modelo próprio
- Desenvolver Formato de Cenario próprio

## Documentação

[Documentação HTML](http://indigente.sourceforge.net/documents/)

## Responsáveis

- BeTo
- IvanMonteiro

## Projetos de Pesquisa

- [ProjetoFapesb](https://wiki.dcc.ufba.br/bin/view/Indigente/ProjetoFapesb)
- [Poster para o SBGames](https://wiki.dcc.ufba.br/bin/view/Indigente/PosterSBGames)

## Arquivos

- [testemd2.tar.bz2](https://wiki.dcc.ufba.br/pub/Indigente/EngineIndigente/testemd2.tar.bz2): Teste para carregar arquivo md2
- [modelo.xmi](https://wiki.dcc.ufba.br/pub/Indigente/EngineIndigente/modelo.xmi): UML de arquitetura de Modelos
- [modelokeyframe.png](https://wiki.dcc.ufba.br/pub/Indigente/EngineIndigente/ModeloKeyFrame.png): UML das Classes referentes ao novo gerenciamento de Modelo Key Frame

## Publicações

- Uma abordagem para o desenvolvimento de jogos adaptáveis a diversos controladores
- O Desenvolvimento de um Motor Multiplataforma para Jogos 3D
