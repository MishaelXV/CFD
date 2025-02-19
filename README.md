# Численные методы для уравнений математической физики
Реализация методов конечных объемов, конечных разностей и конечных элементов для решения уравнений Пуассона, Навье-Стокса и прочих.

## Используемые методы

### 1. Метод конечных объемов (FVM)

Метод конечных объемов представляет собой численный метод решения дифференциальных уравнений в частных производных, основанный на интегральной форме уравнений сохранения.

### 2. Метод конечных разностей (FDM)

Метод конечных разностей аппроксимирует производные с помощью разностей значений функции в соседних точках дискретной сетки.

### 3. Метод конечных элементов (FEM)

Метод конечных элементов делит область решения на конечные элементы, где решение аппроксимируется с помощью базовых функций.

## Примеры уравнений



### 1. Уравнение Пуассона

Уравнение Пуассона представляет собой эллиптическое уравнение в частных производных, описывающее потенциал электрического поля при заданном распределении зарядов.

∇²u = f

### 2. Уравнения Навье-Стокса

Уравнения Навье-Стокса описывают движение вязких жидкостей.

ρ(∂v/∂t + (v·∇)v) = -∇p + μ∇²v + f

### 3. Уравнение теплопроводности

Уравнение теплопроводности описывает распространение тепла в среде.

∂u/∂t = α∇²u
