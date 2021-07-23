Blog Town
College Major Project
Pre install

pipenv
ThenFirst, install the dependencies:

pip install -r requirements.txt

Then, create the database and insert a few examplesdatabase:

python load_database.py

   python
   from flaskblog import db
   db.create_all()
Then, you can run the project:

python run.py
