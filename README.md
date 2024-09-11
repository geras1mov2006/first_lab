
	#include <iostream>;
	#include <windows.h>;

	using namespace std;

	int main()
	{
		SetConsoleOutputCP(1251);
		
		/*
		cout << "ЧАСТЬ 1" << endl;
		cout << " " << endl;
	
		//номер в журнале: 6
	
		int a = 0;
		int b = -3000;
		double c = 4.77;
	
		//a
		cout << "Результат выражения int - int занимает: " << sizeof(a - b) << " байт(а)" << endl;
		//- выражение int – int очевидно тоже типа int – занимает 4 байта (ожидаемо)
	
		//б
		cout << "Тип double занимает: " << sizeof(c) << " байт(а)" << endl;
		//- как и следовало ожидать – 8 байт (ожидаемо)
	
		//в
		cout << "Результат выражения int * double занимает: " << sizeof(a * c) << " байт(а)" << endl;
		//- результат занимает столько же, сколько и наибольший по объему тип – 8 байт
	
		//г
		cout << "Тип short занимает: " << sizeof(short) << " байт(а)" << endl;
		//- как и следовало ожидать – 2 байта (ожидаемо)
	
		//д
		cout << "Тип char занимает: " << sizeof(char) << " байт(а)" << endl;
		//- как и следовало ожидать – 1 байт (ожидаемо)
	
		//е
		cout << "Тип unsigned char занимает: " << sizeof(unsigned char) << " байт(а)" << endl;
		//- 1 байт (не записал на лекции данный тип)
	
	
		
		cout << " " << endl;
		cout << "ЧАСТЬ 2" << endl;
		cout << " " << endl;
	
		char ch; // имя "с" уже занято. переназначить тип переменной не удалось
		int i;
		float f, rez;
		double d;
	
		cout << "Введите переменные ch (char), i (int), f (float), d (double): " << endl;
		cin >> ch >> i >> f >> d;
	
		// s 10 3.5 8.119
	
	
		//1
		cout << "Размер выражения ch + i: " << sizeof(ch + i) << "		"; //int
		rez = ch + i;
		cout << "Размер выражения rez: " << sizeof(rez) << endl; //остался float => занимает столько же места
	
		//2
		cout << "Размер выражения ch + i + d: " << sizeof(ch + i + d) << "		"; //double
		rez = ch + i + d;
		cout << "Размер выражения rez: " << sizeof(rez) << endl; // остался float => занимает меньше места
	
		//3
		cout << "размер выражения i * 3: " << sizeof(i * 3) << endl;
	
		//4
		cout << "размер выражения i * 2147483647: " << sizeof(i * 2147483647) << endl;
	
		//5
		cout << "размер выражения i * 2147483648: " << sizeof(i * 2147483648) << endl; // 8байт тип | __int64 |
	
		//6
		cout << "размер выражения i * f: " << sizeof(i * f) << endl; // 4байта float
	
		//7
		cout << "размер выражения i * 4.5: " << sizeof(i * 4.5) << endl; // 8байт double
	
		//8
		cout << "размер выражения ch: " << sizeof(ch) << endl; // 1байт char
	
		//9
		cout << "размер выражения ch + ch: " << sizeof(ch + ch) << endl; // 4байта int
	
		 
		 
		cout << " " << endl;
		cout << "ЧАСТЬ 3" << endl;
		cout << " " << endl;
	
		int x, y;
		float a, b, c, d;
	
		cout << "Введите x (int), y (int): " << endl;
		cin >> x >> y;
	
		// 6 7
	
		a = x / y;			cout << "a = " << a << endl; // 0
		b = float(x) / y;	cout << "b = " << b << endl; // 0.857143
		c = (float)x / y;	cout << "c = " << c << endl; // 0.857143
		d = float(x / y);   cout << "d = " << d << endl; // 0
	
		
		cout << " " << endl;
		cout << "ЧАСТЬ 4" << endl;
		cout << " " << endl;
	
		int x = 32767, y = 13, z = 13;
		int a = 0;
		int b = -3000;
		double c = 4.77;
	
		cout << "a :" << (a == b) << endl;
		cout << "б :" << (b < x) << endl;
		cout << "в :" << (a != 13) << endl;
		cout << "г :" << (x >= c) << endl;
		cout << "д :" << (!x) << endl;
		cout << "е :" << ((x == a) && (c < x)) << endl;
		cout << "ж :" << ((x >= a) && (b < x)) << endl;
		cout << "з :" << ((x == a) && (c < x)) << endl;
		cout << "и :" << ((x >= a) + (b < x)) << endl;
		cout << "к :" << ((x >= a) + (b < x)) << endl;
		cout << "л :" << (x || 0) << endl;
		cout << "м :" << (!x || 0) << endl;
		cout << "н :" << (y++) << endl;
		cout << "о :" << (++z) << endl;
		cout << "п :" << (y) << endl;
		cout << "р :" << (z) << endl;
		cout << "с :" << (z % 5) << endl;
		cout << "т :" << (5 % z) << endl;
		*/
	return 0;
	}
