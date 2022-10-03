#include<stdio.h>
#include<stdlib.h>
#include<time.h>
int main()
{
    int num,guess,numberofguesses;
    srand(time(0));
    num=rand()%100+1;//To generate randum numbers
    //Runing the code till user gets the right guess
    do
    {
       printf("Guess a number between 1 to 100: \n");
       scanf("%d",&guess);
       if(guess>num)
       {
        printf("Enter a lower number\n");
       } else if(guess<num)
       {
        printf("Enter a heigher number\n");
       } else 
       {
        printf("Hooray! you guessed the right number in %d attempets\n",numberofguesses);
       }
       numberofguesses++;
    } while (guess!=num);
    return 0;
}
