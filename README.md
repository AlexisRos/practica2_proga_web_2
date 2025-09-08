# practica2_proga_web_2
practica 2 

enlaces para la funcinalidad de la practica y ejemplos:

Todos son en metodo POST

REGISTRAR:
http://localhost:3000/auth/register
{
  "username": "Alexis Rosales",
  "email": "ros20639@uvg.edu.gt",
  "password": "123456789"
}

LOGIN:
http://localhost:3000/auth/login
{
  "username": "Alexis Rosales",
  "password": "123456789"
}

CONTRASEÑA OLVIDADA:
http://localhost:3000/auth/forgot-password
{
  "usernameOrEmail": "ros20639@uvg.edu.gt"
}

CAMBIAR LA CONTRASEÑA:
para esto el enlace lo da forgot-password

{
  "usernameOrEmail": "ros20639@uvg.edu.gt"
}
