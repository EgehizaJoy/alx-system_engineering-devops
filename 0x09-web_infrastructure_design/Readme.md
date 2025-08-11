[⚠️ Suspicious Content] 1. Application Server vs Web Server
Web Server (e.g., Nginx, Apache)
Purpose: Handles incoming HTTP/HTTPS requests.

Serves static content: HTML, CSS, JS, images.

Forwards dynamic requests to the application server.

Example: A browser requests /styles.css; the web server serves it directly.

Application Server (e.g., Gunicorn, uWSGI, Tomcat, Node.js runtime)
Purpose: Executes the application’s backend logic.

Processes dynamic content: queries databases, applies business rules.

Returns processed results to the web server.

Example: A browser requests /user/42; the application server fetches data from the database and returns a JSON response.

💡 Analogy:

Web Server = Reception desk – greets visitors, hands them brochures (static content), or directs them to the right department.

Application Server = Department office – does the actual work of processing the visitor’s request.
