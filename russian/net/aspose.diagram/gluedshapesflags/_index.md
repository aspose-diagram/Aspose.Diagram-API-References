---
title: GluedShapesFlags
second_title: Справочник по Aspose.Diagram для .NET API
description: Определяет константы определяющие какие фигуры возвращать исходя из размерности и направленности точек соединения приклеенных к конкретной фигуре передается методу Shape.GluedShapes.
type: docs
weight: 1730
url: /ru/net/aspose.diagram/gluedshapesflags/
---
## GluedShapesFlags enumeration

Определяет константы, определяющие, какие фигуры возвращать, исходя из размерности и направленности точек соединения, приклеенных к конкретной фигуре; передается методу Shape.GluedShapes.

```csharp
public enum GluedShapesFlags
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| GluedShapesAll1D | `0` | Возвращает идентификаторы всех одномерных фигур, которые приклеены к этой фигуре. |
| GluedShapesIncoming1D | `1` | Возвращает идентификаторы одномерных фигур, конечные точки которых приклеены к этой фигуре. |
| GluedShapesOutgoing1D | `2` | Возвращает идентификаторы одномерных фигур, начальные точки которых приклеены к этой фигуре. |
| GluedShapesAll2D | `3` | Вернуть все двумерные фигуры, которые приклеены к этой фигуре, и все двумерные фигуры, к которым приклеена эта фигура. |
| GluedShapesIncoming2D | `4` | Если исходный объект представляет собой одномерную форму, вернуть идентификаторы двухмерной формы, к которой приклеена начальная точка. Если исходный объект представляет собой двумерную фигуру, вернуть идентификаторы двухмерных фигур, которые приклеены к этой фигуре. |
| GluedShapesOutgoing2D | `5` | Если исходный объект представляет собой одномерную фигуру, вернуть идентификаторы двумерной фигуры, к которой приклеена конечная точка. Если исходный объект представляет собой двумерную фигуру, вернуть идентификаторы двухмерных фигур, к которым эта фигура приклеена. |

### Смотрите также

* пространство имен [Aspose.Diagram](../../aspose.diagram/)
* сборка [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
