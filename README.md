para buscar: cmd  +  F
para visualizar: cmd + altizq + v
para guardar: cmd + s

## Git Hub

Pasos para conectar tu proyecto a GitHub

1. Crea el repositorio en GitHub
Ve a github.com

Inicia sesión.

Haz clic en "New" o "Nuevo repositorio"

Asigna un nombre, por ejemplo: Procesamiento_de_Lenguaje_Natural_con_Python_y_NLTK

No marques la opción de crear README si ya tienes archivos locales.

Crea el repositorio y copia la URL SSH.

2. Desde la terminal: entra a la carpeta del proyecto local
```sh
cd ruta/a/tu/proyecto
```

3. Inicializa Git
```sh
git init
```

4. Agrega todos los archivos al área de preparación
```sh
git add .
```

5. Haz el primer commit
```sh
git commit -m "primero 28_6_25"
```

6. Conecta tu proyecto local con el repositorio de GitHub
Asegúrate de copiar tu enlace SSH correcto. Por ejemplo:

```sh
git remote add origin git@github.com:joanflorez-alt/Procesamiento_de_Lenguaje_Natural_con_Python_y_NLTK.git
```

7. Envía tu proyecto a GitHub (rama main)
```sh
git push -u origin main
```

# Próximos pasos útiles

🔸 Para subir futuros cambios:
```sh
git add .
git commit -m "Mi nuevo cambio"
git push
```

🔸 Para ver el estado actual del repositorio:
sh
Copy
Edit
git status
🔸 Para clonar el repositorio en otro equipo:
sh
Copy
Edit
git clone git@github.com:joanflorez-alt/Procesamiento_de_Lenguaje_Natural_con_Python_y_NLTK.git



## Procesamiento de Lenguaje Natural con Python y NLTK


¿Qué es el procesamiento del lenguaje natural?
El procesamiento del lenguaje natural (NLP) es un campo que fusiona ciencias de la computación, lingüística e inteligencia artificial. Su objetivo es lograr que las máquinas interactúen de manera efectiva con los humanos usando el lenguaje que utilizamos para comunicarnos día a día. Dentro del NLP, el Entendimiento del Lenguaje Natural (NLU, por sus siglas en inglés) se dedica a tareas específicas que demuestran que una máquina no solo puede procesar nuestro idioma, sino también comprenderlo para responder de manera coherente.

¿Cuál es el papel del test de Turing en la inteligencia artificial?
Alan Turing, un matemático brillante de la Segunda Guerra Mundial, es conocido por haber contribuido al desarrollo de la inteligencia artificial. Su legado incluye el Test de Turing, que propone una idea sencilla y poderosa: si un humano no puede distinguir a una máquina de una persona durante una conversación, la máquina alcanza un nivel de inteligencia comparable al humano. Este test representa un hito en la identificación del lenguaje como una medida de la inteligencia de una máquina.

Un ejemplo popular en la cultura es el test de Beuyk Kampff de la película "Blade Runner", donde se verifica si un individuo es humano o un replicante. Esta referencia cultural refuerza la importancia del procesamiento del lenguaje natural en el avance hacia la identificación de la inteligencia artificial.

¿Cuáles son las aplicaciones actuales del NLP?
El procesamiento del lenguaje natural se utiliza en diversas aplicaciones cotidianas:

Motores de búsqueda: Google, por ejemplo, usa algoritmos de NLP para interpretar consultas y brindar respuestas precisas.

Traducción automática: Herramientas como Google Translate dependen del NLP para convertir texto entre diferentes idiomas.

Chatbots: Los asistentes virtuales conversacionales son uno de los usos más reconocidos del NLP.

Análisis de discurso y reconocimiento del habla: Estos algoritmos identifican y transforman el lenguaje hablado en texto y viceversa.

¿Por qué es difícil el procesamiento del lenguaje natural?
El principal reto del NLP radica en la complejidad y ambigüedad del lenguaje humano. Un ejemplo claro es interpretaciones posibles para un anuncio de trabajo que busque "gente para trabajar entre dieciocho y treinta años". Una persona entiende que se refiere a la edad del candidato, pero un algoritmo, sin contexto, podría interpretar esto de manera distinta. El lenguaje humano es intrínsecamente difuso y requiere una comprensión contextual que a menudo no está explícita. Por ello, el avance en este campo es desafiante, pero también crucial para mejorar la interacción entre máquinas y humanos.

