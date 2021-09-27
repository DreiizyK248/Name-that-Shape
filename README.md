int main()
{
    int number;

    printf("Enter number of sides to know the name of the shape");

    scanf_s("%d", &number);

    if (number  == 0)


        printf("A circle");


    else if (number  == 3)


        printf("A triangle");


    else if (number  == 4)


        printf("A Quadrilateral (sqare, rectangle, paralleogram) ");


    else if (number  == 5)


        printf("A pentagon");


    else if (number  == 6)


        printf("A hexagon");


    else if (number  == 7)


        printf("A heptagon");


    else if (number  == 8)


        printf("A octagon");


    else if (number  == 9)


        printf("A nonagon");


    else if (number  == 10)


        printf("A star");


    else


        printf("no shape exist of this sides");
}
