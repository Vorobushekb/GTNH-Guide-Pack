---
navigation:
  parent: /items-blocks-index.md
  title: Простраственные ячейки хранения
  icon: appliedenergistics2:item.ItemSpatialStorageCell.2Cubed
categories:
- tools
item_ids:
- appliedenergistics2:item.ItemSpatialStorageCell.2Cubed
- appliedenergistics2:item.ItemSpatialStorageCell.16Cubed
- appliedenergistics2:item.ItemSpatialStorageCell.128Cubed
---

<Row>
<ItemImage id="appliedenergistics2:item.ItemSpatialStorageCell.2Cubed" scale="4"/>

<ItemImage id="appliedenergistics2:item.ItemSpatialStorageCell.16Cubed" scale="4"/>

<ItemImage id="appliedenergistics2:item.ItemSpatialStorageCell.128Cubed" scale="4"/>
</Row>

Пространственная ячейка хранения — это носитель данных, используемый системой [пространственного ввода/вывода](../ae2-mechanics/spatial-io.md). При работе системы объем выбранной области должен быть меньше или равен емкости используемой ячейки. Существует три тира ячеек с емкостью 2, 16 и 128 кубических метров.

Внутренне пространственная ячейка хранения фактически представляет собой отдельное измерение. Работа пространственного пилона заключается в замене всей выбранной области на область того же размера внутри ячейки. При первом использовании новой пространственной ячейки хранения создаётся измерение, соответствующее её внутреннему размеру. На практике каждую новую пространственную ячейку хранения можно представить как заполненную блоками воздуха. При первом пространственном перемещении эта заполненная воздухом область возвращается обратно в мир.

<Color id="RED">После использования пространственной ячейки хранения её нельзя сбросить, переформатировать или изменить размер. Если вам нужен другой размер, создайте новую ячейку.</Color>