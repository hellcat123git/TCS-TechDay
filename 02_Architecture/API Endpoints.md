# API Endpoints

## REST API Specification

### `GET /api/v1/resource`
- **Description:** Fetches a list of resources.
- **Auth Required:** Yes
- **Response:**
  ```json
  [ { "id": "123", "name": "example" } ]
  ```

### `POST /api/v1/resource`
- **Description:** Creates a new resource.
- **Auth Required:** Yes
- **Payload:**
  ```json
  { "name": "new item" }
  ```

## Related Context
- Interacts with: [[Database Schema]]
- Documented per requirements in: [[PRD]]
