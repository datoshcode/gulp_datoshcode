# gulp_datoshcode

<h2>Моя сборка Gulp-4 для веб разработки</h2>

<p>Сборка позволяет: </p>
<ol>
  <li>компилировать .SCSS в .CSS</li>
  <li>сжимать .CSS</li>
  <li>сжимать .JS</li>
  <li>сжимать изображения</li>
  <li>В режиме реального времени в 
    браузере отслеживаются все изменения в проекте</li>
  <li>По окончании работы над проектом, создается отдельна 
    папка /dist для публикации </li>
</ol>  

<p>Порядок установки:</p>
<ol>
  <li>Скачать проект как архив</li>
  <li>Распаковать в пустую папку нового проекта</li>
   <li>Если на компьютере не установлен Node.js и Gulp, то:
   Установить Node.js по ссылке: https://nodejs.org/ru/ </li>
  <li>Если не установлен Gulp глобально. то установить:<code> npm i gulp -j </code> </li>
  <li>Установить Gulp в пустой проект:<code> npm i gulp --save-dev </code></li>
   <li>Устанавливаем Sass командой:
     <code> npm install sass gulp-sass --save-dev </code></li>
  <li>Проверяем работоспособность сборки. В терминале вводим команду:<code> gulp</code>
Если отобразится окно приветствия, как указано на скриншоте, то сборка рабочая.</li>
  <li>Работаем в сборке. Где код html пишем в index.html, scss складываем в папку /scss. 
Изображения, скрипты и шрифты складываем в папку /app</li>
   <li>Для отображения результата своей работы, в терминале вводим команду:<code> gulp</code>
Для выхода, в терминале нажимаем комбинацию: Ctrl+C.</li>
   <li>Для сборки готового проекта, следует ввести команду:<code> gulp build</code> 
   После чего появится папка /dist, содержимое которой можно выкладывать на хостинг.</li>
</ol>  

<img src="img.png" alt="gulp">
  
