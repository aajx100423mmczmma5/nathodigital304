README.md

Plataforma Educativa sobre la lengua otomí y su
cultura de la comunidad de las Moras.
Proyecto integrador de la carrera de programación
3er Semestre grupo304.

-Página principal*Videojuegos*Las 6 casas de 
resguardo*Lecciones interactivas 

#Tecnologías 
-Backend:Django + Django REST Framewort (carpeta backend/)
-frontend:react + vite (carpeta frontend/)

#Instalaciones del frontend
cd backend
python -m venv env
.\env\Scripts\activate.ps1
pip install -r requeriments.txt
copy.env.example.env #y llenar los valores
python manage.py migrate
python manage.py runserver

##Instalacion de frontend
cd frontend
npm install
copy.env.example.env
npm run dev