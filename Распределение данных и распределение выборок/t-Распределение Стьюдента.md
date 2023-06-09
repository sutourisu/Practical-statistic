*t-распределение* - это распределение [нормальной формы](https://github.com/sutourisu/Practical-statistic/blob/main/%D0%A0%D0%B0%D1%81%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85%20%D0%B8%20%D1%80%D0%B0%D1%81%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B2%D1%8B%D0%B1%D0%BE%D1%80%D0%BE%D0%BA/%D0%9D%D0%BE%D1%80%D0%BC%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D0%B5%20%D1%80%D0%B0%D1%81%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5.md), но немного толще и длиннее в хвостах. Оно широко используется для изображения распределений выборочных статистик. Распределения выборочных средних, как правило, имеют форму как у t-распределения, при этом существует целое семейство таких распределений, которые различаются в зависимости от того, насколько большой является выборка.

**Ключевые термины для t-распределения Стьюдента:**

* $n$ - размер выборки.
* **Степени свободы (degrees of freedom)** - параметр, которые позволяет t-распределению адаптироваться к разным размерам выборок, статистикам и числам групп.

Целый ряд разных статистик, после стандартизации, можно сопоставить с t-распределением с целью оценить доверительные интервалы в свете выборочной вариации. Рассмотрим выборку размера $n$, для которой было вычислено выборочное среднее $\bar x$. Если $s$ - это выборочное стандартное отклонение, то 90%-ный доверительный интервал вокруг выборочного среднего задается следующей формулой:
$$\bar x ~\pm ~t_{n-1}(0,05)*\frac{s}t$$
где $t_{n-1}(0,05)$ - это значение $t$-статистики с $(n-1)$ степенями свободы, которое отсекает 5% $t$-распределения с обоих концов.

Точность $t$-распределения в описании поведения выборочной статистики требует, чтобы распределение этой статистики для этой выборки имело форму как у нормального распределения. Как оказалось, выборочные статистики нередко *являются* нормально распределенными, даже когда данные опорной популяции таковыми не являются. Это возвращает нас назад к явлению, известому как [*центральная предельная теорема*](https://github.com/sutourisu/Practical-statistic/blob/main/%D0%A0%D0%B0%D1%81%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85%20%D0%B8%20%D1%80%D0%B0%D1%81%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B2%D1%8B%D0%B1%D0%BE%D1%80%D0%BE%D0%BA/%D0%92%D1%8B%D0%B1%D0%BE%D1%80%D0%BE%D1%87%D0%BD%D0%BE%D0%B5%20%D1%80%D0%B0%D1%81%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%81%D1%82%D0%B0%D1%82%D0%B8%D1%81%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B9%20%D0%B2%D0%B5%D0%BB%D0%B8%D1%87%D0%B8%D0%BD%D1%8B.md).

**Ключевые идеи для распределение Стьюдента**

* t-Распределение  - это на самом деле семейство распределений, напоминающих нормальное распределение, но с более толстыми хвостами.
* t-Распределение широко используется в качестве эталонного базиса для распределения выборочных средних, разниц между двумя выборочными средними, параметров регрессии и т.д.
