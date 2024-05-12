int main() {
    int num;
    std::cout << "Введите число: ";
    std::cin >> num;

    int square = num * num;
    int cube = num * num * num;
    
    std::cout << "Квадрат числа " << num << " равен: " << square << std::endl;
    std::cout << "Куб числа " << num << " равен: " << cube << std::endl;

    return 0;
}

