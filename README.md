# fifa-draft-simulator
***
This project is an attempt to replicate a program allowing fake drafting of soccer players in the fifa database. It also allows for a comprehensive search feature to find players based on search criteria and allows them to be added to a team. There is also the capability to create mulitple teams and change their names.
***
Steps to run the project:
- Download postgresql 
- Make sure postgresql is running
- Create a new database in postgresql called ‘fifa’
- Edit the config.py file to match your postgresql username, password, and database name
- Run psql -U ethanash fifa < data.sql to transfer data to database
- Go to the directory of the file and run python3 app.py localhost 5000
- Open https://localhost:5000/ on a browser
- Click alternate login (not Google, because it only works with Carleton College emails)
