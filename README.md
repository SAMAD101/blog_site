This is a simple blog app built using Django, and Postgresql. This was made as a means to become better at Django, to design and work with some complex models, views, user management and routes, and some other features like pagination.

## To see for yourself and run the project:
1. Install Python(3), Django, PDM, and Postgresql on your computer.
2. Clone this project
    ```bash
    git clone https://github.com/SAMAD101/blog_site.git
    ```
3. Go into the project folder
   ```bash
   cd blog_site
   ```
4. Make a virtual environment and activate it. This step is optional but preferred. You can use any virtualization tool you like.
5. This project uses PDM for managing dependencies. So just run:
   ```bash
   pdm install
   ```
   This will install all the dependencies needed for this project to run.
6. Run migrations:
   ```bash
   python manage.py migrate users
   python manage.py migrate
   ```
7. Finally, run the server:
   ```bash
   python manage.py runserver
   ```
