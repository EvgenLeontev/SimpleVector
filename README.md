# SimpleVector

SimpleVector - вариативная реализация контейнера std::vector.  
Класс SimpleVector упрощен за счет выделения кода, управляющего сырой памятью, в отдельный класс-обёртку RawMemory.
RawMemory отвечает за хранение буфера, который вмещает заданное количество элементов, и предоставлять доступ к элементам 
по индексу.

# Требования

* C++17 