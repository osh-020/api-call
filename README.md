Author: Joshua S Rosario

Project Title
API Call

Description
This is a simple practice Laravel project. It shows how to make API calls, add routes, and use controllers.

Setup Instructions
1. Clone this repository and open the project folder.
2. Install LaravelHerd, then use the SQLite Viewer extension in VS Code to view the SQLite database.
3. In the project folder, run `composer install`.
4. Copy `.env.example` to `.env` and set your database details.
5. Run `php artisan key:generate`.
6. Run `php artisan migrate`.
7. Start the local server with `php artisan serve`.
8. Open `http://127.0.0.1:8000/api/students` in your browser to get the students table data.

Testing with Postman
Open Postman and make a new collection for this project.
Use `http://127.0.0.1:8000/api/students` to get students table data.
To get one student, use `http://127.0.0.1:8000/api/students/1` where `1` is the student number.
Example requests:
`GET /api/fetch-student-data`
`GET /api/fetch-student-data-id`
`POST /api/insert-student-data-id`
`PUT /api/modify-all-fields-student-data`
`PATCH /api/patch-fields-student-data-id`
`DELETE /api/delete-student-data-id`
`DELETE /api/delete-all-student-data`
For POST, PUT, and PATCH requests, choose JSON body and add the needed fields.

Demo Tutorial
Watch the demo tutorial here: https://drive.google.com/file/d/1EpbO5qC8n36O2hjcr9-B6zY4q1EHg-De/view?usp=sharing
This demo shows how to use Postman to send API requests.

