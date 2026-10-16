# Scene data

| Object | Components and references |
|---|---|
| Fulcrum | Static Rigidbody2D, CircleCollider2D, stone sprite |
| Beam | Dynamic Rigidbody2D, BoxCollider2D, HingeJoint2D linked to fulcrum |
| Each player | Dynamic Rigidbody2D, BoxCollider2D, original controller, input script, GroundCheck, CeilingCheck, animated Visual |

There is no database, account system or saved progress. A scene reload resets the round.
