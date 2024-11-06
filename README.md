Project API Documentation
This API allows for retrieving and creating projects.

Endpoints
1. Get All Projects
URL: /api/projects
Method: GET
Description: Retrieves a list of all projects.
Response:
Success (200): Returns a JSON array of projects.
Error (500): Returns an error message if there is an issue retrieving projects.
Example Response:
[
  {
    "id": 1,
    "name": "Project Alpha",
    "description": "Description of Project Alpha",
    "startDate": "2024-01-01T00:00:00Z",
    "endDate": "2024-12-31T23:59:59Z"
  },
  {
    "id": 2,
    "name": "Project Beta",
    "description": "Description of Project Beta",
    "startDate": "2024-02-01T00:00:00Z",
    "endDate": "2024-11-30T23:59:59Z"
  }
]
