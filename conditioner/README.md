<h1 class="title">Кондиционер (12%)</h1>
<p><b>Время: 1 сек.<br>Память: 16 Мб<br>Сложность: 12%</b></p>
<p>В офисе, где работает программист Петр, установили кондиционер нового типа. Этот кондиционер отличается особой простотой в управлении. У кондиционера есть всего лишь два управляемых параметра: желаемая температура и режим работы.</p>
<p>Кондиционер может работать в следующих четырех режимах:</p>
<ul>
    <li>«freeze» — охлаждение. В этом режиме кондиционер может только уменьшать температуру. Если температура в комнате и так не больше желаемой, то он выключается.</li>
    <li>«heat» — нагрев. В этом режиме кондиционер может только увеличивать температуру. Если температура в комнате и так не меньше желаемой, то он выключается.</li>
    <li>«auto» — автоматический режим. В этом режиме кондиционер может как увеличивать, так и уменьшать температуру в комнате до желаемой.</li>
    <li>«fan» — вентиляция. В этом режиме кондиционер осуществляет только вентиляцию воздуха и не изменяет температуру в комнате.</li>
</ul>
<p>Кондиционер достаточно мощный, поэтому при настройке на правильный режим работы он за час доводит температуру в комнате до желаемой.</p>
<p>Требуется написать программу, которая по заданной температуре в комнате t<sub>room</sub>, установленным на кондиционере желаемой температуре t<sub>cond</sub> и режиму работы определяет температуру, которая установится в комнате через час.</p>
<h2>Формат ввода</h2>
<p>Первая строка входного файла input.txt содержит два целых числа t<sub>room</sub> и t<sub>cond</sub>, разделенных ровно одним пробелом (–50 ≤ t<sub>room</sub> ≤ 50, –50 ≤ t<sub>cond</sub> ≤ 50).</p>
<p>Вторая строка содержит одно слово, записанное строчными буквами английского алфавита — режим работы кондиционера, как указано выше.</p>
<h2>Формат вывода</h2>
<p>Выходной файл output.txt должен содержать одно целое число — температуру, которая установится в комнате через час.</p>
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
        <td>10 20<br>
            heat</td>
        <td>20</td>
     </tr>
     <tr>
         <td>10 20<br>
             freeze</td>
         <td>10</td>
     </tr>
  </tbody>
</table>