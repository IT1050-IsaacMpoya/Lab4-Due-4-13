# Lab 4

Answers 

Qn 2.  "While" loop is an entry loop. It tests the loop at the time of entering into the loop. Well as a "For" loop is also an entry loop. In a "For loop", a loop continuation condition is checked at the time of entering the loop. Almost everything that can be done by a while can be done with the for loop. The While and For loops are known for looping statements in most of the programming languages. But the complexity of implementation may be different according to scenario. 
Qn 3.   While is an entry-controlled loop which first checks the condition, then executes the code. Do-while is an exit-controlled loop which first executes the code, then checks the condition. A while loop is normally used in a scenario where you don't know how many times a loop will actually execute at runtime. A do-while loop is used where your loop should execute at least one time.

Q4.     	 for (int i = 1; i <= 100; i++)
                {
                    Console.WriteLine(i);

                    if ((i % 2) == 0)

                    {
                        Console.WriteLine("Number is even");
                    }
                    else if ((i % 2) != 2)
                    {
                        Console.WriteLine("Number is odd");
                    }

Q5.    		 int tempurature;
                  
                Console.WriteLine("Please enter a tempeture");
                tempurature = int.Parse(Console.ReadLine());

               if (tempurature <10)
                Console.WriteLine("Polar Bear");
                else
                    if (tempurature < 20)
                    Console.WriteLine("Penguin");
                else
                    if (tempurature < 40)
                     Console.WriteLine("Moose");
                else
                    if (tempurature < 50)
                    Console.WriteLine("Reindeer");
                else
                    if (tempurature < 60)
                    Console.WriteLine("Deer");
                else
                    if (tempurature < 70)
                    Console.WriteLine("Turtle");
                else
                    if (tempurature <80)
                    Console.WriteLine("Lion");
                else
                    if (tempurature < 90)
                    Console.WriteLine("Fish");
                else
                    Console.WriteLine("Bug");

            }
Q6.		    int i = 10;
                while (i<21)
                {
                    Console.WriteLine( i);i++;
                }Console.ReadLine();


Q7.    for (int i=0; i<=101; i++)
               
                {
                    Console.WriteLine(i);
                    Console.WriteLine("********");
                }
                 Console.ReadLine();


