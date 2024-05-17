#include <iostream>
#include <algorithm>
#include <vector>

int main() {
    // Bir vektör (dinamik dizi) oluştur
    std::vector<int> myVector = {34, 7, 23, 32, 5, 62};

    // Vektörü sıralamadan önce yazdır
    std::cout << "Sıralamadan önce: ";
    for(int num : myVector) {
        std::cout << num << " ";
    }
    std::cout << std::endl;

    // std::sort fonksiyonunu kullanarak vektörü sırala
    std::sort(myVector.begin(), myVector.end());

    // Vektörü sıraladıktan sonra yazdır
    std::cout << "Sıraladıktan sonra: ";
    for(int num : myVector) {
        std::cout << num << " ";
    }
# 
