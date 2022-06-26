# Assignmenttt2
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace assignment3
{
    internal class Program
    {
        private static void main(string[] args)
        {

        }


        class GradeDemo
        {
            private static int grade;

            public static void Main()
            {
                int stud_mark;
                char con = 'y';



                while (con == 'y')
                {
                    Console.Write("Enter the student grade: ");



                    if (grade >= 93)
                    {
                        Console.WriteLine("Your letter grade is A+");
                    }
                    else if (grade >= 90)
                    {
                        Console.WriteLine("Your letter grade is A");
                    }
                    else if (grade >= 87)
                    {
                        Console.WriteLine("Your letter grade is B+");
                    }
                    else if (grade >= 85)
                    {
                        Console.WriteLine("Your letter grade is B-");
                    }
                    else if (grade >= 80)
                    {
                        Console.WriteLine("Your letter grade is C+");
                    }
                    else if (grade >= 75)
                    {
                        Console.WriteLine("Your letter grade is C-");
                    }
                    else if (grade >= 70)
                    {
                        Console.WriteLine("Your letter grade is D+");
                    }
                    else if (grade >= 60)
                    {
                        Console.WriteLine("Your letter grade is D-");
                    }
                    else
                    {
                        Console.WriteLine("Your letter grade is F");
                    }
                }
                Console.Write("Do you want to continue? If yes Write y otherwise enter any character: ");
                con = Convert.ToChar(Console.ReadLine());

            }
        }
    }
}

