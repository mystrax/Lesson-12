# Lesson-12
Array marks and average

    #include <iostream>
    #include<string>
    using namespace std;
    int main()
    {
       int grades[5];
       int sum=0;
       int average = 0;
       for (int i = 0;i < 5;i++) {
           cout << "Enter 5 marks\n";
           cin >> grades[i];
        }
       for (int n = 0; n < 5; ++n)
       {
           cout << "The marks are " << grades[n] << endl;
           sum += grades[n];
       }
       {
         average = sum / 5;
           cout << "The average is: "<<average << endl;
       }
       return 0;
    }
months- array

    #include <iostream>
    #include<string>
    using namespace std;
    int main()
    {
        string months[11] = { "january", "february", "march", "april", "may", "june", "july", "august", "september", "october", "november", "december" };
        for (int i = 0;i < 11;i++) {
            cout << months[i] << endl;
        }

    }
