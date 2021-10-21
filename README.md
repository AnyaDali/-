#include <iostream>
using namespace std;
//Дано натуральное число n. Определить кол-во и сумму цифр в заданном числе
int main() {
    int n, cn, sum, count; //n-исходное число; cn-копия n; sun-сумма цифр в числе n; count -количество цифр в числе n;
    scanf("%d", &n);
    sum = 0;
    count = 0;
    cn = n;
    while(cn > 0) {
        sum = sum + m % 10;
        count = count+1;
        cn = cn/10;
    }

    printf("%d\n, %d\n", sum, count);
    return 0;
}
