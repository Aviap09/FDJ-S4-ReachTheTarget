# Reach the Target
Ferramentas de Desenvolvimento de Jogos | Semana 4

Tutorial prático - Reach the Target | Godot 4 .NET e Unity | Página 12

## Engine
Godot 4 .NET / Unity

## Objetivo
Aprender a implementar um código para movimentar o jogador e ativar triggers com outros objetos.

## Controlos
WASD ou setas.

## Funcionalidades
- Movimento
- Colisão
- Targets
- Feedback

## Desafios Realizados
- Godot: G1, G2, G3, G4,
- Unity:

## Questão de Análise
A variável foi exportada do codigo com "[Export]", para que fosse possivel alterar o valor no Inspector.

## Comparar as duas engines

| Aspeto | Godot 4 .NET | Unity |
|---|---|---|
| Objeto principal do jogador | CharacterBody2D | GameObject + Componentes(3+) |
| Organização da cena | Estrututra de Árvore | Hierarquia |
| Visual | Sprite2D - Retangulo Vermelho | SpriteRenderer - Capsule |
| Colisão | CollisionShape2D - RectangleShape2D | Collider2D - Box Collider 2D |
| Input |  Input Map / Input.GetVector | Input Map |
| Código | Script associado ao Node | MonoBehaviour associado ao GameObject |
| Reutilização | - | Prefab do Target |
| Feedback | Label / nós de UI | Canvas / UI |

Reflexão Curta: Na minha opinião, o Godot é bem mais intuitivo que o Unity. Um dos pontos principais é o design do UI do Godot ser bem mais moderno e os componentes terem nomes bem mais intuitivos e fáceis de lembrar. Também penso que o Godot ter métodos semi-prontos e signals é uma grande ajuda quando se está a implementar qualquer código.

## Melhorias implementadas
- 
- 
-






## Reflexão Final
1.Qual foi a principal diferença que encontrou entre a criação do Player no Unity e no Godot?

Penso que a criação em ambas as engines foi bastante parecida, mas no Godot a criação é um pouco mais simples e intuitiva enquanto que no Unity ela é um pouco menos óbvia e complexa.

2.Onde ficou definido o comportamento do Player em cada motor?

No Unity ficou num script chamado PlayerController, dentro do método Update que a cada frame carrega o código dentro dele. No Godot fica num scipt chamado Player, dentro do método _PhysicsProcess que carrega o código dentro dele 60 vezes por segundo (physics frame).

3.Que papel teve o motor e que papel teve o código?

As engines tinham o papel de dar os objetos e conectar o código aos objetos, enquanto o código contêm as interações, relações e ações que os objetos relacionados vão realizar.

4.Qual das melhorias exigiu mais experimentação e porquê?

5.Que utilidade encontrou no histórico de commits?

6.Se continuasse o projeto durante mais uma semana, qual seria a próxima funcionalidade a implementar?


## Links Importantes
[Repositório do Reach The Target - Godot](https://github.com/Aviap09/reach-the-target-godot)

[Repositório do Reach The Target - Unity](https://github.com/Aviap09/reach-the-target-unity)

[Projeto Github](https://github.com/users/Aviap09/projects/2/views/2)

## Autor
Luís Paiva A051646
