# movie-theater-seat-api

OpenAPI spec for the seat part of a movie theater's ticketing backend. It's Part 2 of the A7 REST API Design assignment.

`seat-selection-api.yaml` (OpenAPI 3.0.3) has four operations:

- `GET /showtimes/{showtimeId}/seats` gets the seat map for a showtime
- `POST /showtimes/{showtimeId}/seat-holds` holds the picked seats for 10 minutes while the customer pays
- `GET /seat-holds/{holdId}` checks on a hold
- `DELETE /seat-holds/{holdId}` lets go of a hold so the seats go back on sale

It's a design, so the servers are made up and nothing's running behind them. To see it rendered, paste the YAML into https://editor.swagger.io.
