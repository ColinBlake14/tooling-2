# Tooling - part 2

## 1) На вкладке Network
### Неоптимальные места
#### Дублирование ресурсов
5 раз загружается одно и то же gif-изображение
![image](https://github.com/ColinBlake14/tooling-2/assets/90147314/3f0da632-526c-419c-85e4-9da9d6cc4a90)

дважды грузим один скрипт
![image](https://github.com/ColinBlake14/tooling-2/assets/90147314/991c47a2-05c8-4e7d-a648-54b3691f119e)

дважды грузим один шрифт
![image](https://github.com/ColinBlake14/tooling-2/assets/90147314/0258b5bf-2ca1-4087-9548-ef02d0a09a9c)

10 файлов из тех, чей размер больше 50kB грузится со сжатием gzip вместо br
![image](https://github.com/ColinBlake14/tooling-2/assets/90147314/458ef8d0-2ac0-440b-853f-eabbaaf14612)

14 файлов из тех, чей размер больше 10kB грузится вообще без сжатия
![image](https://github.com/ColinBlake14/tooling-2/assets/90147314/52e3c658-95cd-413a-b91e-14fb70473ff8)

## 2) На вкладке Performance
### Показатели:
- FP = FCP = 408ms
- DCL = 1.48s
- LCP = 1.71s
- Load = 2.34s

### LCP происходит на img-элементе
![image](https://github.com/ColinBlake14/tooling-2/assets/90147314/dc68cf0d-b977-4ffb-bf03-ff654ad1448a)

### Этапы обработки документа
- Loading: 49 ms
- Scripting: 1426 ms
- Rendering: 513 ms
- Painting: 33 ms
  
![image](https://github.com/ColinBlake14/tooling-2/assets/90147314/b42f810b-3130-4767-949b-6fb4f0b457a5)

## 3) На вкладке Coverage
![image](https://github.com/ColinBlake14/tooling-2/assets/90147314/335c299e-d3b4-46d5-b729-204c1c71ef2b)

### Объём неиспользованного CSS в ходе загрузки страницы: 567kB
![image](https://github.com/ColinBlake14/tooling-2/assets/90147314/395e05b6-58d5-463d-9e77-e98f0ce6cb3f)

### Объём неиспользованного JS в ходе загрузки страницы: 2.3MB
![image](https://github.com/ColinBlake14/tooling-2/assets/90147314/2a287267-c43b-464b-90ba-3d7d28090b6c)




