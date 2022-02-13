#include <stdio.h>
void sub_work(int force,float distance)
{
    float work;
    work=force*distance;
    printf("work : force * distance = %.3f",work);
}
void sub_intensity(float power,float sphericalsurfacearea)
{
    float intensity;
    intensity = power/sphericalsurfacearea;
    printf("intensity : power / sphericalsurfacearea = %.3f",intensity);
}
void sub_density(int mass,float volume)
{
    float density;
    density = mass/volume;
    printf("density : mass / volume = %.3f",density);
}
void sub_electricpower(float power,float Time)
{
    float electricpower;
    electricpower = power*Time;
    printf("electricpower : power * Time = %.3f",electricpower);
}
void sub_lambda(float volume,float frequency)
{
    float lambda;
    lambda = volume/frequency;
    printf("lambda : volume / frequency = %.3f",lambda);
}
void main(void)
{
    int mass=5,force=7,number;
    float volume=6.5,sphericalsurfacearea=7.7,power=5.5,frequency=12.2,Time=3.3,distance=4.6;
    
    printf("if input 1 to find work");
    printf("\nif input 2 to find intensity");
    printf("\nif input 3 to find density");
    printf("\nif input 4 to find electricpower");
    printf("\nif input 5 to find lambda");
    
    do{
        printf("\nplease input number : ");
        scanf("%d",&number);
    
        if(number==1)
        {
            sub_work(force,distance);
            printf("\n");
        }
        else if(number==2)
        {
            sub_intensity(power,sphericalsurfacearea);
            printf("\n");
        }
        else if(number==3)
        {
            sub_density(mass,volume);
            printf("\n");
        }
        else if(number==4)
        {
            sub_electricpower(power,Time);
            printf("\n");
        }
        else if(number==5)
        {
            sub_lambda(volume,frequency);
            printf("\n");
        }
        else
        {
            printf("\n\nEnd Program");
        }
        printf("\ninput any number back to program or input 9 to exit program : ");
        scanf("%d",&number);
    }while(number != 9);
}
