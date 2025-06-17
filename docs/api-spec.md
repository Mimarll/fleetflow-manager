# API Endpoints (Draft)

## GET /api/trucks
**Description:** List all trucks with GPS coordinates  
**Response (200):**
```json
[
  { "id": 1, "lat": 3.14, "lng": 101.70, "status": "en route" },
  { "id": 2, "lat": 3.20, "lng": 101.66, "status": "delivered" }
]
