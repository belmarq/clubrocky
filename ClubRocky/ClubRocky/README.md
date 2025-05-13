# Actualizar pip
python3 -m pip install --upgrade pip

# Crear entorno virtual
python3 -m venv venv

## activar entorno virtual
source venv/bin/activate

# Instalar Django
pip install Django

# Grabar las librerias instaladas
pip freeze >> librerias.txt

# Instalar en un venv librerias listadas en un archivo de tipo freeze
pip install -r librerias.txt

# configurar git
git config --global user.email "email@email.com"

git config --global user.name "Luis Beltran"