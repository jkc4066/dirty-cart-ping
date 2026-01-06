# dirty-cart-ping
## Business Rules
- Only one open cart request per unit
- Requests escalate in severity only (EMPTY → HALF → FULL)
- Duplicate submissions update the existing request
