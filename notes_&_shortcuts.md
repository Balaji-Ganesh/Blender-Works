# Shortcut keys

## **General usage**

| Purpose                            |              Key              |                                                                  Notes |
| :--------------------------------- | :---------------------------: | ---------------------------------------------------------------------: |
| **S**caling<sup>\*</sup>           |         <kbd>S</kbd>          |                                                                        |
| **G**rabbing<sup>\*</sup> (Moving) |         <kbd>G</kbd>          |                                                                        |
| **R**otation<sup>\*</sup>          |         <kbd>G</kbd>          |                                                                        |
| Multi selection                    |         <kbd>B</kbd>          | drag with LMB to multi-select and MMB to multi-deselect<sup>\*\*</sup> |
| to select all objects              |         <kbd>A</kbd>          |                                                                        |
| duplicating selected objects       | <kbd>Shift</kbd>+<kbd>D</kbd> |                                                                        |

<sup>\*</sup> To constraint only in a specific direction, after it use <kbd>X</kbd> or <kbd>Y</kbd> or <kbd>Z</kbd> to constraint only in respective co-ordinates. To constraint only in two co-ordinates, use **two** co-ordinates. Ex:

- <kbd>S</kbd>+<kbd>X</kbd> &rarr; to constraint scaling only in X and
- <kbd>S</kbd>+<kbd>X</kbd>+<kbd>Z</kbd> &rarr; to constraint scaling only in X and Z.

<sup>\*\*</sup> LMB: Left Mouse Button, RMB: Right Mouse Button.

## **Resetting the transformation**

|           Purpose | Key                         |
| ----------------: | :-------------------------- |
|  to reset scaling | <kbd>Alt</kbd>+<kbd>S</kbd> |
| to reset rotation | <kbd>Alt</kbd>+<kbd>R</kbd> |
| to reset grabbing | <kbd>Alt</kbd>+<kbd>G</kbd> |

- To apply the transformation, _(i.e., should not get reset via Undo)_, then <kbd>Ctrl</kbd>+<kbd>A</kbd> _(to open **Apply** menu)_ &rarr; **All Transforms**. This sets all to their basic values _(check in the properties pane)_.

## **Various context menus**

| Context menu |              Key              | Notes                                                |
| -----------: | :---------------------------: | :--------------------------------------------------- |
|          Add | <kbd>Shift</kbd>+<kbd>A</kbd> | \* to add new objects into the scene at 3D cursor.   |
|        Apply | <kbd>ctrl</kbd>+<kbd>A</kbd>  | for applying the transformations performed till now. |

## **Changing view**

|           View |             Key              | Notes                                                                                |
| -------------: | :--------------------------: | :----------------------------------------------------------------------------------- |
|     Front view |         <kbd>1</kbd>         |                                                                                      |
|      Back view | <kbd>ctrl</kbd>+<kbd>1</kbd> |                                                                                      |
|      Left view |         <kbd>3</kbd>         |                                                                                      |
|     Right view | <kbd>ctrl</kbd>+<kbd>3</kbd> |                                                                                      |
|       Top view |         <kbd>7</kbd>         |                                                                                      |
|    Bottom view | <kbd>ctrl</kbd>+<kbd>7</kbd> |                                                                                      |
|   Focused view |         <kbd>.</kbd>         | Zooms the selected object(s) only (rest will be still visible )                      |
| Isolation view |         <kbd>/</kbd>         | Zooms the selected object(s) only (rest will be **hidden**). Use once more to reset. |

\*In the num pad

## Modelling tips

- While modelling, to focus onnly on single object, use <kbd>/</kbd> after selecting object. -- for **Isolation** of other objects. Use the same key to reset the isolation mode.

- **Adding more editors/views**:
  - Hover the cursor over any editor's corners and drag
  - place the cursor at the same place or in between the editors and drag in any of the direction to close.

# Notes Blender for beginners tutorials

## Day-1: Absolute Basics

- Basics related to scaling, grabbing, changing views .. (as noted above)

1. Rotating, scaling the objects w.r.t. **Global**, **Local** transform-orientations (at top-center menu)
2. Projecting individual elements on surface of another.
   - Select the objects.
   - Goto Snap menu (in top-center), select `Face` and tick the `Project Individual Elements` and `Align Rotation To Target` and enable `Affect`s.,
   - Make sure to **enable** Snap mode and test it out, else it won't
