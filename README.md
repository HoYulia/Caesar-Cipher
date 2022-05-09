Шифр Цезаря (шифр сдвига) — один из самых простых и наиболее широко известных методов шифрования. 
Цезаря — это вид шифра подстановки, в котором каждый символ в открытом тексте заменяется символом, находящимся на некотором постоянном числе позиций левее или правее него в алфавите.

Например, шифрование с использованием ключа k=3 будет иметь вид:

Исходный алфавит: A B C D E F G H I J K L M N O P Q R S T U V W X Y Z

Шифрованный:      D E F G H I J K L M N O P Q R S T U V W X Y Z A B C

А что если каждое слово в строке будет иметь разный ключ к, равный количеству символов в слове (только буквы)?

Sample Input: Day, mice. "Year" is a mistake!

Sample Output: Gdb, qmgi. "Ciev" ku b tpzahrl!

Можете зашифровать любой текст на английском языке.

В файле "other" програмы для шифрования/дешиврования текста на английскои и русском языках с фиксированым ключом.

Пример: 

1. К = 10
Sample Input: Блажен, кто верует, тепло ему на свете!
Sample Output: Лхкрпч, фьш мпъэпь, ьпщхш пцэ чк ымпьп!

2. К = 17
Sample Input: To be, or not to be, that is the question!
Sample Output: Kf sv, fi efk kf sv, kyrk zj kyv hlvjkzfe!

3. К = 7
Sample Input: Шсъцхр щмчжмщ йшм, нмтзж йшм лхшщзщг.
Sample Output: Скупой теряет все, желая все достать.

4. К = 25
Sample Input: Sgd fqzrr hr zkvzxr fqddmdq nm sgd nsgdq rhcd ne sgd edmbd.
Sample Output: The grass is always greener on the other side of the fence.
