# Шифрування та дешифрування чисел
Розроблена програма призначена для шифрування та дешифрування алгоритмів RSA з використанням чисел довільної довжини, яка задається в конструкторі.  
Основою розробленої програми є клас IHO, який містить в собі масив символів. Для класу визначені наступні методи:
1)	IHO() - конструктор
2)	void OLIA(unsigned char* ) –переводить символьне представлення числа в внутрішнє представлення у вигляді двійкового коду довільної довжини
3)	void HANA(unsigned char*) – переводить внутрішнє представлення масива числа у вигляді рядка символів
4)	void operator +=(IHO )- оператор, який додає до масива об’єкта інший масив іншого об’єкту  
5)	IHO operator +(IHO ) – оператор, який повертає об’єкт, масив якого  є сумою масивів двох інших об’єктів  
6)	int operator >(IHO) – повертає 1 або 2 взалежності від того, яке число серед двух об’єктів більше
7)	void operator -=(IHO ) – оператор віднімання, який віднімає масиви двух об’єктів
8)	IHO operator -(IHO )- оператор, який повертає об’єкт, масив якого є різницею масивів двох  інших об’єктів  IHO operator *(IHO);
9)	void operator >>(int) – оператор, який зсуває масив в бік старших бітів
10)	void operator <<(int) - оператор, який зсуває масив в бік молодших бітів
11)	void HANA_Dil(IHO, IHO*)- оператор, який ділить масиви двох об’єктів.
12)	IHO operator %(IHO )- опертор, який повертає об’єкт, масив якого є остачею ділення масивів двох обєктів
13)	IHO operator /(IHO )- оператор, який повертає об’єкт, масив якого є залишком ділення масивів двох об’єктів.

14)	int PER_10() – повертає 1 або 0, в залежності від того, чи число в об’єкті  більше за 10
15)	void HANA_10(unsigned char* ) - переводить символьне десяткове представлення числа в внутрішнє представлення у вигляді двійкового коду
16)	void HANECHKA(unsigned char*)- переводить внутрішнє представлення масива числа у вигляді рядка десяткового символьного представлення числа
17)	IHO EXPM(IHO B,IHO M)- повертає об’єкт, масив якого являє собою результат модулярного експонціювання 
18)	int SB ( unsigned int ) – повертає, старший біт числа
19)	void longA(unsigned long ) - переводить число в внутрішнє представлення у вигляді двійкового коду
20)	unsigned long BUBU() – повертає число, переведене з внутрішнього представлення числа у вигляді масива
