## Interaction Types

Table of Contents

- [File Details](#file-details)
- [Enum Values](#enum-values)

<br>

## File Details

| Attribute         | Description                                  |
| ----------------- | -------------------------------------------- |
| File Name         | `EInteractType`                              |
| Containing Folder | `/Content/Core/Interaction/DataTypes/`       |
| Type              | `Enum`                                       |
| Used In           | [Interact Component](./InteractComponent.md) |

<br>

## Enum Values

| Name               | Description                                                  |
| ------------------ | ------------------------------------------------------------ |
| `AutoInRange`      | The interaction will trigger as soon as the player pawn starts overlapping the parent actor's collision. |
| `AutoWhenLanded`   | The interaction will trigger as soon as the player pawn lands on a [Landing Point Component](../Landing_Points/LandingPointComponent.md) owned by the parent actor. |
| `ButtonInRange`    | The interaction will trigger if the player presses **Interact** while overlapping the parent actor's collision. |
| `ButtonWhenLanded` | The interaction will trigger if the player presses **Interact** while landed on a [Landing Point Component](../Landing_Points/LandingPointComponent.md) owned by the parent actor. |

