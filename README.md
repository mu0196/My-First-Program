# My-First-Program
Program to show GPA, Average and Grades

#include<stdio.h>
#include<conio.h>
int main()
{    
     float a,b,c,x,y;
     char grade;
     float avg, GPA, Sgpa1, Sgpa2, Sgpa3, Sgpa4, Sgpa5;
     float grade_point1, grade_point2, grade_point3, grade_point4, grade_point5, Total_grade_points;
	 float  Cr_h1, Cr_h2, Cr_h3, Cr_h4, Cr_h5, Total_credit_hours;
	 printf("Enter your marks of Programming Fundamental:");
     scanf("%f",&a);
     Cr_h1=4;
	 if(a>=84.50){
		printf("\nGrade is:A+ \nSgpa1 is 4.00 \tDiscription: Expectional");
    }
	else if(a<=84.49&&a>=79.50){
		printf("\nGrade is:A \nSgpa1 is 3.70 \tDiscription: Outstanding");
		Sgpa1=4.0;
	}
	else if(a<=79.49&&a>=74.50){
		printf("\nGrade is:B+ \nSgpa1 is 3.40 \tDiscription: Excelent");
		Sgpa1=3.40;
	}
	else if(a<=74.49&&a>=69.50){
		printf("\nyour Grade is:B \nSgpa1 is 3.00 \tDiscription: Very Good");
		Sgpa1=3.00;
    }
    else if(a<=69.49&&a>=64.50){
   	   printf("\nyour Grade is:B- \nSgpa1 is 2.50 \tDiscription: Good");
   	   Sgpa1=2.50;
    }
     else if(a<=64.49&&a>59.50){
     	printf("\nyour Grade is:C+ \nSgpa1 is 2.00 \tDiscription: Average");
     	Sgpa1=2.00;
   }
     else if(a<=59.49&&a>54.50){
     	printf("\nyour Grade is:C \nSgpa1 is 1.50 \tDiscription: Satesfactory");
     	Sgpa1=1.50;
     }
     else if(a<=54.49&&a>49.50){
     	printf("\nyour Grade is:D \nSgpa1 is 1.00 \tDiscription: Pass");
     	Sgpa1=1.00;
     }
      else if(a<=49.49&&a>34.50){
     	printf("\nyour Grade is:F \nSgpa1 is 0.00 \tDiscription: Fail");
     	Sgpa1=0.0;
     }
     else{
     	printf("Invalid Entery");
     }
     
	   printf("\n\nEnter your marks of Basic Electronics:");
     scanf("%f",&b);
     Cr_h2=3;
     if(b>=84.50){
		printf("\nGrade is:A+ \nSgpa2 is 4.00 \tDiscription: Expectional");
		Sgpa2=4.00;
    }
	else if(b<=84.49&&b>=79.50){
		printf("\nGrade is:A \nSgpa2 is 3.70 \tDiscription: Outstanding");
		Sgpa2=3.70;
	}
	else if(b<=79.49&&b>=74.50){
		printf("\nGrade is:B+ \nSgpa2 is 3.40 \tDiscription: Excelent");
		Sgpa2=3.40;
	}
	else if(b<=74.49&&b>=69.50){
		printf("\nyour Grade is:B \nSgpa2 is 3.00 \tDiscription: Very Good");
		Sgpa2=3.00;
    }
    else if(b<=69.49&&b>=64.50){
   	   printf("\nyour Grade is:B- \nSgpa2 is 2.50 \tDiscription: Good");
   	   Sgpa2=2.50;
    }
     else if(b<=64.49&&b>59.50){
     	printf("\nyour Grade is:C+ \nSgpa2 is 2.00 \tDiscription: Average");
     	Sgpa2=2.00;
   }
     else if(b<=59.49&&b>54.50){
     	printf("\nyour Grade is:C \nSgpa2 is 1.50 \tDiscription: Satesfactory");
     	Sgpa2=1.50;
     }
     else if(b<=54.49&&b>49.50){
     	printf("\nyour Grade is:D \nSgpa2 is 1.00 \tDiscription: Pass");
     	Sgpa2=1.00;
     }
      else if(b<=49.49&&b>34.50){
     	printf("\nyour Grade is:F \nSgpa2 is 0.00 \tDiscription: Fail");
     	Sgpa2=0.00;
     }
     else{
     	printf("Invalid Entery");
     }
      printf("\n\nEnter your marks of English:");
     scanf("%f",&c);
     Cr_h3=3;
     if(c>=84.50){
		printf("\nGrade is:A+ \nSgpa3 is 4.00 \tDiscription: Expectional");
		Sgpa3=4.00;
    }
	else if(c<=84.49&&c>=79.50){
		printf("\nGrade is:A \nSgpa3 is 3.70 \tDiscription: Outstanding");
		Sgpa3=3.70;
	}
	else if(c<=79.49&&c>=74.50){
		printf("\nGrade is:B+ \nSgpa3 is 3.40 \tDiscription: Excelent");
		Sgpa3=3.40;
	}
	else if(c<=74.49&&c>=69.50){
		printf("\nyour Grade is:B \nSgpa3 is 3.00 \tDiscription: Very Good");
		Sgpa3=3.00;
    }
    else if(c<=69.49&&c>=64.50){
   	   printf("\nyour Grade is:B- \nSgpa3 is 2.50 \tDiscription: Good");
   	   Sgpa3=2.50;
    }
     else if(c<=64.49&&c>59.50){
     	printf("\nyour Grade is:C+ \nSgpa3 is 2.00 \tDiscription: Average");
     	Sgpa3=2.00;
   }
     else if(c<=59.49&&c>54.50){
     	printf("\nyour Grade is:C \nSgpa3 is 1.50 \tDiscription: Satesfactory");
     	Sgpa3=1.50;
     }
     else if(c<=54.49&&c>49.50){
     	printf("\nyour Grade is:D \nSgpa3 is 1.00 \tDiscription: Pass");
     	Sgpa3=1.00;
     }
      else if(c<=49.49&&c>34.50){
     	printf("\nyour Grade is:F \nSgpa3 is 0.00 \tDiscription: Fail");
     	Sgpa3=0.00;
     }
     else{
     	printf("Invalid Entery");
     }
      printf("\n\nEnter your marks of Calculus:");
     scanf("%f",&x);
     Cr_h4=3;
     if(x>=84.50){
		printf("\nGrade is:A+ \nSgpa4 is 4.00 \tDiscription: Expectional");
		Sgpa4=4.00;
    }
	else if(x<=84.49&&x>=79.50){
		printf("\nGrade is:A \nSgpa4 is 3.70 \tDiscription: Outstanding");
		Sgpa4=3.70;
	}
	else if(x<=79.49&&x>=74.50){
		printf("\nGrade is:B+ \nSgpa4 is 3.40 \tDiscription: Excelent");
		Sgpa4=3.40;
	}
	else if(x<=74.49&&x>=69.50){
		printf("\nyour Grade is:B \nSgpa4 is 3.00 \tDiscription: Very Good");
		Sgpa4=3.00;
    }
    else if(x<=69.49&&x>=64.50){
   	   printf("\nyour Grade is:B- \nSgpa4 is 2.50 \tDiscription: Good");
   	   Sgpa4=2.50;
    }
     else if(x<=64.49&&x>59.50){
     	printf("\nyour Grade is:C+ \nSgpa4 is 2.00 \tDiscription: Average");
     	Sgpa4=2.00;
   }
     else if(x<=59.49&&x>54.50){
     	printf("\nyour Grade is:C \nSgpa4 is 1.50 \tDiscription: Satesfactory");
     	Sgpa4==1.50;
     }
     else if(x<=54.49&&x>49.50){
     	printf("\nyour Grade is:D \nSgpa4 is 1.00 \tDiscription: Pass");
     	Sgpa4=1.00;
     }
      else if(x<=49.49&&x>34.50){
     	printf("\nyour Grade is:F \nSgpa4 is 0.00 \tDiscription: Fail");
     	Sgpa4=0.00;
     }
     else{
     	printf("Invalid Entery");
     }
      printf("\n\nEnter your marks of Introduction to Communication & Technology:");
     scanf("%f",&y);
     Cr_h5=3;
     if(y>=84.50){
		printf("\nGrade is:A+ \nSgpa5 is 4.00 \tDiscription: Expectional");
		Sgpa5=4.00;
    }
	else if(y<=84.49&&y>=79.50){
		printf("\nGrade is:A \nSgpa5 is 3.70 \tDiscription: Outstanding");
		Sgpa5=3.70;
	}
	else if(y<=79.49&&y>=74.50){
		printf("\nGrade is:B+ \nSgpa5 is 3.40 \tDiscription: Excelent");
		Sgpa5=3.40;
	}
	else if(y<=74.49&&y>=69.50){
		printf("\nyour Grade is:B \nSgpa5 is 3.00 \tDiscription: Very Good");
		Sgpa5=3.00;
    }
    else if(y<=69.49&&y>=64.50){
   	   printf("\nyour Grade is:B- \nSgpa5 is 2.50 \tDiscription: Good");
   	   Sgpa5=2.50;
    }
     else if(y<=64.49&&y>59.50){
     	printf("\nyour Grade is:C+ \nSgpa5 is 2.00 \tDiscription: Average");
     	Sgpa5=2.00;
   }
     else if(y<=59.49&&y>54.50){
     	printf("\nyour Grade is:C \nSgpa5 is 1.50 \tDiscription: Satesfactory");
     	Sgpa5=1.50;
     }
     else if(y<=54.49&&y>49.50){
     	printf("\nyour Grade is:D \nSgpa5 is 1.00 \tDiscription: Pass");
     	Sgpa5=1.00;
     }
      else if(y<=49.49&&y>34.50){
     	printf("\nyour Grade is:F \nSgpa5 is 0.00 \tDiscription: Fail");
     	Sgpa5=0.00;
     }
     else{
     	printf("Invalid Entery");
     }
     avg=(a+b+c+x+y)/5.0;
     printf("\n\nTotal Avg is %f",avg);
     Total_credit_hours=Cr_h1+Cr_h2+Cr_h3+Cr_h4+Cr_h5;
     grade_point1=Sgpa1*Cr_h1;
     grade_point2=Sgpa2*Cr_h2;
     grade_point3=Sgpa3*Cr_h3;
     grade_point4=Sgpa4*Cr_h4;
     grade_point5=Sgpa5*Cr_h5;
     Total_grade_points=grade_point1+grade_point2+grade_point3+grade_point4+grade_point5;
     GPA= Total_grade_points/Total_credit_hours;
     printf("\n\n GPA is %f",GPA);
     getch();
}
