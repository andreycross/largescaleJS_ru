<!-- ### Что из себя представляет «большое» JavaScript приложение? -->

Перед тем как я начну, давайте постараемся определить, что именно мы имеем 
в виду, когда говорим о больших JavaScript приложениях. Этот вопрос
я считаю вызовом опытным разработчикам, и ответы на него, получаются
очень субъективными.

Ради эксперимента, я предложил нескольким среднестатистическим разработчикам
попытаться дать собственное определение этому термину. Один из разработчиков 
предложил определение «JavaScript приложение, состоящее из более чем 100.000 
LOC<sup>1</sup> <span class="sidenote"><span class="num">1.</span>Количество
строк кода (англ. Source Lines of Code — SLOC) <a href="https://ru.wikipedia.org/wiki/%D0%9A%D0%BE%D0%BB%D0%B8%D1%87%D0%B5%D1%81%D1%82%D0%B2%D0%BE_%D1%81%D1%82%D1%80%D0%BE%D0%BA_%D0%BA%D0%BE%D0%B4%D0%B0"></a></span>
кода», когда другой определил это как «приложение, содержащее больше, чем
1Mb JavaScript кода внутри». Я расстроил храбрецов — оба этих варианта
не правильные. Количество кода не всегда коррелируется со сложностью приложения. 
100,000 LOC легко могут оказаться простым, ничем не примечательным кодом.

Я не знаю, подойдет ли мое собственное определение к любому случаю, но я верю,
что оно подходит ближе всего к тому, что действительно представляет из себя
большое JavaScript приложение.

{:class="message"}
Я считаю, что большие JavaScript-приложения решают нетривиальные задачи,
а поддержка таких приложений требует от разработчика значительных усилий,
при этом большая часть работы по манипуляции данными и их отображению ложится
на браузер.

Последняя часть определения, вероятно, самая важная.