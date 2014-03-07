premo.py
========
Genera direcciones bitcoin partiendo de una password creada con la funcion siguiente, 8 caracteres con numeros y manuysculas minusculas.


def id_generator(size=8, chars=string.ascii_uppercase + string.digits + string.ascii_lowercase): return ''.join(random.choice(chars) for x in range(size))
