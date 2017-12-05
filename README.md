# DevelopperUtilTools
Создание классов из BIN файлов

Developper.UtilTools.ClassFromBin.xml - CSP страница 
  http://localhost:57772/csp/user/Developper.UtilTools.ClassFromBin.cls

<h4>
Загрузить HTML проект из директории  "C:\AppServ\www\css3_modalwin\" в пакет "Demo.ModalWindowCSS"
</h4>
<br>  do ##class(Developper.UtilTools.ClassFromDir).run("Demo.ModalWindowCSS","C:\AppServ\www\css3_modalwin\")
<br>
<br>
<br>
<h4>
Загрузить бинарный файл в Cache' класс можно из вэб интерфейса Cache' (класс Developper.UtilTools.ClassFromBin)
</h4>
<br>
   http://localhost:57773/csp/user/Developper.UtilTools.ClassFromBin.cls
<br><br>
<h3>Дополнительноые утилиты </h3>
 <br> Перенести все классы из пакета “User” в другой “MyNewPac”
 <pre>      do ##class(Developper.UtilTools.ClassFromDir).RenamePacket("User","MyNewPac")</pre>
<br> Скопировать класс "HTML.x3dom" в "DELETE.dom"
  <pre>   do ##class(Developper.UtilTools.ClassFromDir).CopyClass("HTML.x3dom","DELETE.dom")</pre>
<br> Заменить текст "HTML.js.WebGL.cls" на "HTML.GL.cls" в классах внутри пакета "Demo"
  <pre>   do ##class(Developper.UtilTools.ClassFromDir).replaceTXT("Demo","HTML.js.WebGL.cls","HTML.GL.cls")</pre>
