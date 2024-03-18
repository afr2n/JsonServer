# json-server

## Installation Backend 
To host the Backend locally, please run the following command:
1. Clone the repository:
```bash
git clone https://github.com/afr2n/json-server.git
```
2. Navigate to the project directory:

```bash
cd json-server
```
3. Install dependencies:

```bash
npm install
```

## Usage Backend
Once the installation is complete, you can start the development server to use the Schedules Filter:

```bash
npm run dev
```

## Usage

Created a `db.json` file of the format

```json
{
  "schedules": [
    {
      "id": "1",
      "title": "500 Startups",
      "description": "Venture capital firm providing seed funding and accelerator programs to startups.",
      "retire": false
    },
    {
      "id": "2",
      "title": "Guy Kawasaki",
      "description": "Entrepreneur, author, and former chief evangelist of Apple.",
      "retire": false
    },
  ],
  "scheduleLogs": [
    {
      "id": "3",
      "scheduleId": 1,
      "date": "2024-03-15",
      "time": "9:00 AM - 10:00 AM",
      "activity": "Investor Pitch",
      "location": "Investor's Office",
      "presenters": [
        "John",
        "CEO"
      ],
      "audience": "Potential Investors",
      "purpose_objective": "Convince investors to fund our project",
      "notes": "Highlighted market opportunities and financial projections."
    },
    {
      "id": "4",
      "scheduleId": 2,
      "date": "2024-03-18",
      "time": "11:00 AM - 12:00 PM",
      "activity": "Investor Meeting",
      "location": "Zoom Call",
      "presenters": [
        "Alex",
        "Sarah"
      ],
      "audience": "Angel Investors",
      "purpose_objective": "Discuss investment opportunities and growth plans",
      "notes": "Reviewed financial projections and answered investor questions."
    },
  ],
}
```

The following endpoints are available on the Backend: 
1. http://localhost:3000/schedules
2. http://localhost:3000/schedules/:id
3. http://localhost:3000/scheduleLogs


