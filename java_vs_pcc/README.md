<h1 class="title">Java vs C++ (34%)</h1>
<p><a href="https://acmp.ru/index.asp?main=task&id_task=270" target="_blank">Ссылка на задачу</a></p>
<p><b>Время: 1 сек.<br>Память: 16 Мб<br>Сложность: 34%</b></p>
<p class=text>
Сторонники языков Java и C++ часто спорят о том, какой язык лучше для решения олимпиадных задач. Одни говорят, что в Java есть масса полезных библиотек для работы со строками, хорошо реализованы механизмы чтения и вывода данных, а так же радует встроенные возможности для реализации длинной арифметики. С другой стороны, С++ является классическим языком, скорость выполнения программ благодаря существующим компиляторам (например, Intel Compiler 10.0) гораздо выше, чем у Java.
</p>
<p class=text>
Но сейчас нас интересует лишь небольшие отличия, а именно соглашения, которыми пользуются программисты при описании имен переменных в Java и C++. Известно, что для понимания значений переменных часто используют английские слова или даже целые предложения, описывающие суть переменных, содержащих те или иные значения. Приведем ниже правила описания переменных, которыми руководствуются программисты, реализующие программы на Java и C++.
</p>
<p class=text>
В языке Java принято первое слово, входящее в название переменной записывать с маленькой английской буквы, следующее слово идет с большой буквы (только первая буква слова большая), слова не имеют разделителей и состоят только из английских букв. Например, правильные записи переменных в Java могут выглядеть следующим образом: javaIdentifier, longAndMnemonicIdentifier, name, nEERC.
</p>
<p class=text>
В языке C++ для описания переменных используются только маленькие английские символы и символ «_», который отделяет непустые слова друг от друга. Примеры: java_identifier, long_and_mnemonic_identifier, name, n_e_e_r_c.
</p>
<p class=text>
Вам требуется написать программу, которая преобразует переменную, записанную на одном языке в формат другого языка.
</p>
<h2>Формат ввода</h2>
<p class=text>
Во входном файле INPUT.TXT задано наименование переменной длиной от 1 до 100 символов, в котором могут встречаться только заглавные и строчные буквы английского алфавита, а также символ подчёркивания.
</p>
<h2>Формат вывода</h2>
<p class=text>
В выходной файл OUTPUT.TXT требуется вывести аналог имени переменной в другом языке. Т.е. если переменная представлена в формате Java, то следует перевести в формат C++ и наоборот. В том случае, когда имя переменной не соответствует ни одному из вышеописанных языков, следует вывести «Error!»
</p>
<h3>Примеры</h3>
<table class="sample-tests">
  <thead>
     <tr>
        <th>Ввод</th>
        <th>Вывод</th>
     </tr>
  </thead>
  <tbody>
     <tr>
        <td>long_and_mnemonic_identifier</td>
        <td>longAndMnemonicIdentifier</td>
     </tr>
     <tr>
         <td>anotherExample</td>
         <td>another_example</td>
      </tr>
      <tr>
          <td>i</td>
          <td>i</td>
       </tr>
       <tr>
           <td>bad_Style</td>
           <td>Error!</td>
       </tr>
  </tbody>
</table>