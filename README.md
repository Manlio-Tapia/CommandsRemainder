# CommandsRemainder
#Escuchar Reverse Shell NetCat
nc -v -n -l -p 1234

Obtener shell despues de entrar con reverse 
echo "import pty; pty.spawn('/bin/bash')" > /tmp/asdf.py
python /tmp/asdf.py
