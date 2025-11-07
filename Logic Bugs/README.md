# 🧩 Logic & Flow Bug Types

## 🔧 Input Handling Bugs
| Type | Description |
|------|--------------|
| **Parameter Manipulation** | An application's logic cannot properly handle a specific type of parameters. |
| **Validation Logic Disparity** | Where validation logic varies between front-end and back-end. |
| **Unexpected Input** | Where bugs are caused by different types of input the application cannot handle. |
| **Null Safety** | Where bugs are caused by not properly handling null parameters. |

---

## 🔁 Flow Logic Bugs
| Type | Description |
|------|--------------|
| **Flow Bypass** | An application's flow can be broken due to certain flaws in its design. |
| **Repeating One-off Actions** | Where we are able to repeatedly use actions that should only be carried out once. |
| **Out of Order Steps** | Where we break a multi-step process by performing steps out of order. |
| **Unexpected Behavior** | Covers all other flow logic bugs, usually caused by user behavior the application isn't designed to handle. |
