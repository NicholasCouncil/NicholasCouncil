Date: 04/16/2023
class: CYCS1200
Assignment: Number Demonstrations

Results:

Problem 1
Expected: 3.6000000000
Result: 3.5999999046

Problem 2
Expected: 0.1000000000
Result: 0.1000000015

Problem 3a
Expected: 1/2
Result: 0.000000

Problem 3b
Expected: 1.0/2.0
Result: 0.500000

Problem 4a
Expected: 9999999.4499999999
Result: 9999999.450000

Problem 4b
Expected: 9999999.4499999999
Result: 9999999.000000

Problem 5a
Expected: 3000030000
Result: -1294937296

Problem 5b
Expected: 4000040000 
Result: -0294927296

Problem 5c
Expected: 5000050000 
Result: 0705082704

Problem 5d
Expected: 6000060000
Result: 1705092704

Problem 6a
Expected: 1e20
Result: 100000002004087734272.000000

Problem 6b
Expected: (1e20 + 3500000000)
Result: 100000002004087734272.000000

Problem 6c
Expected: (1e20 + (3500000000 * 1000000000)
Result: 103500002601996386304.000000

Problem 6d
Expected: 103500000000000000000
Result: 100000002004087734272.000000



## The following is the code used to achive my results stated above

int main()
{
     /*Problem 1*/
    float one = 3.6;
    printf("%.10f\n",one); 
    

     /*Problem 2*/
    float two = 1.0/10.0;
    printf("%.10f\n",two);


     /*Problem 3*/
    double three = 1/2;
    printf("%f\n",three); 

    double three = 1.0/2.0;
    printf("%f\n",three); 



    /*Problem 4*/
    double four = 9999999.4499999999;
    printf("%f\n",four);

    float four = 9999999.4499999999;
    printf("%f\n",four);

    
    
    /*Problem 5*/
    int five = 3000030000 ;
    printf("%d\n",five);

    int five = 4000040000;
    printf("%d\n",five);
    
    int five = 5000050000;
    printf("%d\n",five);
    
    int five = 6000060000;
    printf("%d\n",five);
    

    /*Problem 6*/
    float value;
        value =1e20;
    printf("%f\n", value);

        value =(1e20 + 3500000000);
    printf("%f\n", value);

        value =(1e20 + (3500000000 * 1000000000));
    printf("%f\n", value);
        value = 1e20;
            int i;

    for (i = 0; i < 1000000000 ; i++){
        value = value + 3500000000;}
    printf("%f\n", value);

    return 0;
}
