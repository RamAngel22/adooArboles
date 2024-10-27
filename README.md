Instrucciones

1. Clona este repositorio:
   ```bash
   git clone https://github.com/RamAngel22/adooArboles.git
   cd adooArboles
   
2. Crea y activa un entorno virtual:
  python -m venv env
  source env/bin/activate  # En Windows: env\Scripts\activate

3. Instala las dependencias:
  pip install -r requirements.txt

4. Corre las migraciones:
  python manage.py migrate

5. Ejecuta el servidor de desarrollo:
   python manage.py runserver

Accede a http://127.0.0.1:8000/accounts/register/ para registrarte y a http://127.0.0.1:8000/accounts/login/ para iniciar sesión.
