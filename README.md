#include <iostream>

int main (){

int one {0};

int summ {0};

do {

std::cout << "Enter number to continiy, enter 0 to stop\n";

std::cin>> one;

summ = summ + one;}

while ( one!=0);

std::cout<< "Summ is - "<< summ;

}
