include<stdio.h>
Void main()
{
    //1.Display the menu
    printf("pick an a item:\n.pizza,Rs239\n2.burger,129\n3.pasta,Rs179\n4.french fries,Rs99\n5.sandwich,Rs149");
    //2.read their choice
    int choice=0;
    //3.display based on their choice
    switch(choice)
    {
        case 1:
        printf("you picked pizza");
        break;
        case 2:
        printf("you picked burger");
        break;
        case 3:
        printf("you picked pasta");
        break;
        case 4:
        printf("you picked fench fries");
        break;
        case 5:
        printf("you picked sandwich");
        break;
        default : printf("Invalid choice" );
    }
}
