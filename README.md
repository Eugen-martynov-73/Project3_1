#include <iostream>

int main ()

{

int one {0};

int check {1};

int number {0};

std::cout <<"Enter number\n";

std::cin >> one;

one = std::abs(one);

do {

check=check*10;

}while (one>check);

std::cout<< check <<"\n" ;

while (check!=1) {

check=check/10;

number = number + (one/check);

one = one%check;

}

std::cout<< "Summ = \t" << number;

}
