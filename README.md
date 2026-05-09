# Herramientas-Propias
Las son buenas herramientas en Python enfocadas a ciberseguridad generadas con IA, pero compruebo que si están bien hechas y les agrego cosas para mejorarlas poco a poco

Requerimientos:

pip install PySocks 
pip install requests

Ejemplos:
# Normal
python3 EscanerPro.py 192.168.1.1 

# Escaneo rápido
python3 EscanerPro.py 192.168.1.1 --fast -p 22,80,443,3306
# Salida: Escaneo_192.168.1.1.zip

# Escaneo a dominio
python3 EscanerPro.py google.com -p 80,443
# Salida: Escaneo_142.250.185.46.zip

# Modo INSANO
python3 EscanerPro.py 192.168.1.1 --insane -p 1-500
