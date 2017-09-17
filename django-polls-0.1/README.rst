=====
Polls ENGLISH
=====

Polls is a simple Django app to conduct Web-based polls. For each
question, visitors can choose between a fixed number of answers.

Detailed documentation is in the "docs" directory.

Quick start
-----------

1. Add "polls" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'polls',
    ]

2. Include the polls URLconf in your project urls.py like this::

    url(r'^polls/', include('polls.urls')),

3. Run `python manage.py migrate` to create the polls models.

4. Start the development server and visit http://127.0.0.1:8000/admin/
   to create a poll (you'll need the Admin app enabled).

5. Visit http://127.0.0.1:8000/polls/ to participate in the poll.

############################

=====
Polls ESPAÑOL
=====

Polls es una simple app Django para conducir encuestas desde en la Web. 

Para cada pregunta, los visitantes pueden seleccionar entre un número determinado de respuestas.

Documentación detallada en el directorio "docs".

Inicio rápido
-----------

1. Agregue "polls" a su configuración INSTALLED_APPS como sigue::

    INSTALLED_APPS = [
        ...
        'polls',
    ]

2. Incluya el URLconf de polls en su proyecto urls.py como sigue::

    url(r'^polls/', include('polls.urls')),

3. Corra `python manage.py migrate` para crear los modelos de polls.

4. Arranque el servidor de desarrollo y visite http://127.0.0.1:8000/admin/
   para crear una encuesta (va a necesitar la app Admin habilitada).

5. Visite http://127.0.0.1:8000/polls/ para participar de la encuesta.
