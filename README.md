<h1>C_img</h1>

<h2>Dockerfile</h2>
FROM gcc:latest
copy . .
run gcc -o myapp  hello.c
cmd ["./myapp"]      

<h2>hello.c</h2>
#include <stdio.h> 
  
int main() 
{ 
    printf("Welcome to Docker World!!!\n"); 
    return 0; 
}
