# Lab1-Task2-Movie-Map
Lab1 Task2 Movie Map

Цей модуль генерує карту, на якій позначено 10 найближчих до користувача локацій зйомки фільмів для обраного року.
Цю інформацію можна використовувати як в розважальних, так і в пізнавальних цілях.

Приклад роботи:
Для прикладу оберемо рік мого народження - 2004, та місце мого проживання - м. Тернопіль, проспект Злуки, 8 (координати - (49.56067, 25.61824)). Датасетом скористаємось стандартним, тим, який нам надано в завданнi на CMS, під назвою locations.list.(можна завантажити за посиланням https://drive.google.com/file/d/11KVCDMVb8H0vKzb8bx7VvqOlBUxUfL6x/view)
З метою оптимізації часу роботи програми, і для запобігання надзвичайно довгого часу виконання у користувача є можливість обмежити кількість локацій, з переліку яких шукатимуться найближчі за допомогою опційного аргументу -number --n, який за замовчуванням встановлений на 70. До прикладу, при значенні 70 пошук нових фільмів припиниться, і програма обере 10 найближчих локацій з 70 знайдених (тих, які знаходяться першими в файлі).
<img width="804" alt="Знімок екрана 2022-02-06 о 15 52 52" src="https://user-images.githubusercontent.com/92430278/152684149-a6cfdbd9-b19c-4239-983f-2dbcd3cd7fdf.png">

Після запуску, бачимо повідомлення "Please wait, program is working...", а після виконання бачимо повідомлення про завершення роботи і затрачений на неї час.<img width="804" alt="Знімок екрана 2022-02-06 о 15 55 09" src="https://user-images.githubusercontent.com/92430278/152684249-687e170b-a660-4e9d-a765-6afb27566a42.png">

Мапу збережено у файлі Movie_map.html
<img width="359" alt="Знімок екрана 2022-02-06 о 15 56 54" src="https://user-images.githubusercontent.com/92430278/152684277-eb87cfc4-6428-4f18-87b2-123509cd5b00.png">

<img width="1440" alt="Знімок екрана 2022-02-06 о 15 57 54" src="https://user-images.githubusercontent.com/92430278/152684332-ba417ec9-839d-4169-8e3d-3dbfc8a11e38.png">
Так виглядає згенерована мапа. При натисканні на відрізки, що з'єднують початкову мітку із місцями зйомки фільмів, бачимо відстань між цими двома об'єктами. Існує можливість приховати шар міток чи відстаней.
