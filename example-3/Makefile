# Усложненный make-file. Введены переменные для параметров компиляции и исполняемых файлов

.ФАЛЬШИВЫЙ: все отладочные версии чистые

ВЫПУСК_ФЛАГОВ = -O2 -Wall -DNDEBUG
DEBUG_FLAGS = -g -O0 -Стена
ВЫПУСК_EXEC = Казинороял
DEBUG_EXEC = Kazino-Royal-dbg
ИСТОЧНИК = Kazino-Royal.cpp

все: отладочный релиз

отладка: $(DEBUG_EXEC)

Казинороял-dbg: Kazino-Royal.cpp
 g++ $(DEBUG_FLAGS) Kazino-Royal.cpp -о $(DEBUG_EXEC)  

релиз: $(RELEASE_EXEC)

Казинороял: Kazino-Royal.cpp
 g++ $(RELEASE_FLAGS) Kazino-Royal.cpp -o $(RELEASE_EXEC)
очистить:
 rm -f $(RELEASE_EXEC)  $(DEBUG_EXEC)
