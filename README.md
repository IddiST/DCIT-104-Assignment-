# DCIT-104-Assignment-

// write a program to calculate the average of all even integers between 1 and 10000(ten thousand)
int averageEven(int 10000)
{
    if (n % 2 != 0) {
        printf("Invalid Input");
        return -1;
    }
  
    int sum = 0, count = 0;
    while (10000 >= 2) {
  
        count++;
  
        sum += 10000;
  
        n = 10000 - 2;
    }
    return sum / count;
}
  
int main()
{
    int 10000 = 16;
    printf("%d", averageEven(10000));
    return 0;
    ![image](https://user-images.githubusercontent.com/102989464/183461143-0e33ca29-7023-4918-a0b4-d959438b79cb.png)
    
    //write a program that produces the sum of all prime numbers less than a given number
    
    int primeSum(int l, int r)
{
int sum = 0;
for (int i = r; i >= l; i--) {

bool isPrime = checkPrime(i);
if (isPrime) {

sum = sum + i;
}
}
return sum;
}
![image](https://user-images.githubusercontent.com/102989464/183461417-121550d6-5cff-4969-aebb-0f8605bb0de4.png)



