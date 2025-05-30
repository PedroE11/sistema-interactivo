# Sistema Interactivo para la Práctica y Evaluación de Ejercicios de Matemáticas en Bachillerato

Este proyecto es un sistema interactivo desarrollado en Django para la práctica y evaluación de ejercicios matemáticos para estudiantes de bachillerato.

## Características

- Generación de ejercicios matemáticos aleatorios
- Diferentes niveles de dificultad
- Evaluación automática de respuestas
- Sistema de autenticación con roles
- Estadísticas de rendimiento

## Aplicaciones

1. **autenticacion**: Manejo de usuarios, roles y permisos
2. **ejercicios**: Generación y gestión de ejercicios matemáticos
3. **evaluacion**: Evaluación de respuestas y estadísticas

## Instalación

1. Clonar el repositorio:
\`\`\`bash
git clone https://github.com/tu-usuario/sistema-interactivo-matematicas.git
cd sistema-interactivo-matematicas
\`\`\`

2. Crear y activar entorno virtual:
\`\`\`bash
python -m venv env
# En Windows
env\Scripts\activate
# En Linux/macOS
source env/bin/activate
\`\`\`

3. Instalar dependencias:
\`\`\`bash
pip install -r requirements.txt
\`\`\`

4. Realizar migraciones:
\`\`\`bash
python manage.py makemigrations
python manage.py migrate
\`\`\`

5. Crear superusuario:
\`\`\`bash
python manage.py createsuperuser
\`\`\`

6. Ejecutar el servidor:
\`\`\`bash
python manage.py runserver
\`\`\`

## Uso

1. Acceder a la aplicación en `http://localhost:8000`
2. Iniciar sesión con las credenciales creadas
3. Seleccionar el tipo de ejercicio, dificultad y cantidad
4. Resolver los ejercicios y recibir retroalimentación inmediata

## Autores

- Juan Aguilar
- Felipe Lopez
- Jonathan Iguarán
- José Pirela
