# Project_Trofimova
Документация:

**diapasons** - словарь, содержащий средние диапазоны значений для каждого кодового значения подвида
**check_diapason** - функция для проверки принадлежности введенного числа к заданному диапазону значений выбранного подвида
Параметры:
  _**subspecies_code (str)**_ - кодовое значение подвида
  _**wing_length (float)**_ - числовое значение длины крыла
Возвращает:
**str** - сообщение о принадлежности или непринадлежности числа к заданному диапазону
Программа запрашивает у пользователя кодовое значение подвида и числовое значение длины крыла, затем проверяет принадлежность этого числа к заданному диапазону значений выбранного подвида и выводит соответствующее сообщение. Данная программа помогает оптимизировать проверку полученных порфометрических данных перед их занесением в базу данных.
_В работах, связанных с исследованиями географической изменчивости и подвидовой систематики, важна точность полученных данных. Для создания баз данных орнитологи производят определенные замеры, чаще сего с точностью до десятых мм, реже до сотых. Полученные данные нуждаются в повторной проверке для гарантии точности измерений, но для оптимизации процесса мы берем уже готовые базы данных и получаем из них средние диапазоны значений по каждому морфометрическому признаку. В процессе измерений мы сверяемся с бумажными табличками, что занимает пару десятков секунд, но это время в сумме за день работы может доходить до ощущаемых значений. Именно поэтому я придумала эту программу, на которую в процессе работы будет тратиться гораздо меньше времени._
