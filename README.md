# rimfrost-service-permissions-openapi

OpenAPI-specifikation för Rimfrost permissions service.

## Endpoints

| Metod | Sökväg | Beskrivning |
|-------|--------|-------------|
| `GET` | `/{idTyp}/{idVarde}/hasSidPermission` | Kontrollera om en användare har SID-behörighet |

## Centrala begrepp

- **idTyp** — typ av identifierare som används för att identifiera användaren (t.ex. `kortnummer`)
- **idVarde** — identifierarens värde (t.ex. ett kortnummer)
- **SID-behörighet** — behörighet som styr om en användare har tillgång till SID-funktionalitet

