# Mash
Императивный язык программирования с динамической типизацией и приведением типов. 
Поддерживает ООП и многопоточность.
Может быть встроен в ваш проект через простое API.

- Сайт проекта: http://mash-lang.tech
- Форум: http://forum.mash-lang.tech

# Проект разделен на несколько частей:
- /runtime/ - стековая ВМ и библиотеки к ней.
- /lang/ - транслятор.
- bin*/inc/ - языковая база Mash'а.

# Где скачать последнюю версию Mash?
На данный момент Mash находится на pre-release версии.
Разработка и отладка идет на Win64 сборке проекта.
Если вам необходима версия для другой разрядности или ОС - вы можете собрать её сами (FPC 2.6.4+).

# TODO/BUGS:
- (Windows - SVM): Отладка SEH.
- (IDE): Access Violation баг.
- (SVM+IDE): Разработка отладчика.
- (SDK): MCL.
- (SDK): TCP & UDP обертка для Mash.
- (SDK): Разработка минимальной необходимой кодовой базы.

# Лицензия
Проект лицензирован на основе BSD-2 текста лицензии.
Проект опенсорсный, вы можете использовать его бесплатно в любых своих начинаниях, но...
Если вы захотите опубликовать ваше ПО, которое использует Mash или часть его кодовой базы,
то указание копирайта, названия проекта и автора (@RoPi0n) - обязательные условия.
