**Бот работает только в термуксе, но вы его можете переписать/**


Вот что вам понадобится для запуска этого бота :
 - Прямые руки
 - Следовать инструкциям 
 
 **Инструкции**
 
 **Для начала поставим termux 0.118 с F-DROID и оттуда-же ставим termux-api**
 заходим в термукс и вводим:
```
 pkg install termux-tools && termux-change-repo
```
 нажимаем y и Enter на клавиатуре(позже так нужно будет сделать несколько раз)
 тут мы выбираем нужное нам зеркало термукса чтобы библиотеки быстро качались
 советую выбрать mirror group - Russia если вы из России
 Выбираем его(должна стоять звездочка на выбранном зеркале)
 Возможно телефон будет немного вибрировать.

  Когда зеркало выбралось пишем:
  
  `pkg install binutils coreutils rust python termux-api`
  
  клонируем этот репозиторий или скачиваем его в виде zip и распаковываем, заходим в папку из термукса с помощью похожей команды:
  
```cd /sdcard/downloads/ampersand```

или просто :

```cd ampersand```

(в зависимости от того в какой сейчас вы папке )

ставим все библиотеки с помощью:

`pip install -r requirements.txt -fopenmp-implicit-rpath`

если какая-то библиотека не доставилась - ставите её с помощью pip install <библиотека>

запускаем бота находясь в папке с ботом с помощью команды

`python main.py`



По вопросам или если есть какие-то проблемы пишите в личку vk.com/notparody 