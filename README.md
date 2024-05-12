#include <iostream>

int main() {
    int num;
    std::cout << "Введите число: ";
    std::cin >> num;

    int square = num * num;
    
    std::cout << "Квадрат числа " << num << " равен: " << square << std::endl;

    return 0;
}
