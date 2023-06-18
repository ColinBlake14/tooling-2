# Tooling - part 2

## 1) На вкладке Network
### Неоптимальные места
#### дублирование ресурсов
5 раз загружается одно и то же gif-изображение
![image](https://github.com/ColinBlake14/tooling-2/assets/90147314/3f0da632-526c-419c-85e4-9da9d6cc4a90)

дважды грузим один скрипт
![image](https://github.com/ColinBlake14/tooling-2/assets/90147314/991c47a2-05c8-4e7d-a648-54b3691f119e)

дважды грузим один шрифт
![image](https://github.com/ColinBlake14/tooling-2/assets/90147314/0258b5bf-2ca1-4087-9548-ef02d0a09a9c)

10 файлов из тех, чей размер больше 50кб грузится со сжатием gzip вместо br
![image](https://github.com/ColinBlake14/tooling-2/assets/90147314/458ef8d0-2ac0-440b-853f-eabbaaf14612)

10 файлов из тех, чей размер больше 10кб грузится вообще без сжатия
![image](https://github.com/ColinBlake14/tooling-2/assets/90147314/52e3c658-95cd-413a-b91e-14fb70473ff8)


