---
navigation:
  parent: /items-blocks-index.md
  title: Фасады
  icon: facade
  icon_nbt: '{item: "minecraft:stone"}'
  position: 110
categories:
- network infrastructure
item_ids:
- ae2:facade
---

# Фасады

Фасады можно использовать, чтобы твоя база выглядела чище. Они могут покрыть оба размера кабеля и могут быть сделаны из разных блоков.

<GameScene zoom="6" background="transparent">
  <ImportStructure src="../assets/assemblies/facades_1.snbt" />
  <IsometricCamera yaw="195" pitch="30" />
</GameScene>

Они могут покрываать все стороны кабеля, но всё позволяет но при этом позволяют [компонентам](../ae2-mechanics/cables-subparts.md) и кабелям соединяться сквозь них.

<GameScene zoom="6"  interactive={true}>
  <ImportStructure src="../assets/assemblies/facades_2.snbt" />
  <IsometricCamera yaw="195" pitch="30" />
</GameScene>

При правильном использовании они могут улучшить вид твоей базы или позволить создавать блоки с разными текстурами на каждой стороне.

<GameScene zoom="4" interactive={true}>
  <ImportStructure src="../assets/assemblies/facades_3.snbt" />
  <IsometricCamera yaw="195" pitch="30" />
</GameScene>

## Скрытие фасадов

Фасады остаются скрытыми, пока вы держите <a href="network_tool.md">сетевой инструмент</a> в любой из рук.

Вы можете взаимодействовать с блоками, расположенными за скрытыми фасадами, не убирая сами фасады.

## Рецепт

Поместите блок, текстуру которого вы хотите использовать, в центре 4 <ItemLink id="cable_anchor" />.

![Рецепт фасада](../assets/diagrams/facade_recipe.png)