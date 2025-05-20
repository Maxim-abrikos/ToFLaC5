# ToFLaC5
Пятая лабораторная по дисциплине Теория формальных языков и компиляторов 
Задание:  
1) Реализовать в текстовом редакторе поиск лексических и синтаксических ошибок для грамматики G[<E>]. Реализовать данную КС-граммматику методом рекурсивного спуска:  
1. E → TA 
2. A → ε | + TA | - TA  
3. T → ОВ  
4. В → ε | *ОВ | /ОВ  
5. О → id | (E)  
6. id → letter {letter}  
2) Реализовать алгоритм записи выражений в форме тетрад.


Примеры верных строк:
a = v + c/d - (r*t)
h = e*-n+s

Примеры работы программы:  
![Снимок экрана (1881)](https://github.com/user-attachments/assets/31be5e78-97b0-4135-b2cb-fb8116122717)  
![Снимок экрана (1882)](https://github.com/user-attachments/assets/ed123574-527a-4e4a-b78c-5682476be954)  
![Снимок экрана (1883)](https://github.com/user-attachments/assets/570bb78f-cfb5-4c84-b55b-ce7fb851fcce)  
![Снимок экрана (1885)](https://github.com/user-attachments/assets/9ed9a10e-48c0-4ee6-bd94-d2d569af5023)  
![Снимок экрана (1886)](https://github.com/user-attachments/assets/fb612406-26a6-456e-8360-cbc951380c13)  
