# Lecture-10-
Countdown For Loop

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        for (int x = 10; x >= 0; x--)
        {
            if (x != 0)
                cout << "X is " << x << "\n";
            else
                cout << "We have lift off" << endl;
        }

    }
Odd Even For Loop

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        for (int x = 20; x <= 24; x++)
        {
            if (x % 2 == 0)
                cout << x << " - even" << "\n";
            else
                cout << x << " - odd" << "\n";
        }

    }
Seven stars rows and columns

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        for (int i = 0; i < 7; i++)
        {  
            for (int j = 0; j < 7; j++)
            {
                cout << "*"; 
            }
            cout << endl; 
        }


    }
Some counting

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        cout << " A program that counts up from 0 to 50 in increments of 1\n";
        for (int x = 0; x < 51; x++)
        {
            cout << x << endl;
        }
        cout << endl;
        cout << " A program that counts down from 50 to 0 in decrements of 1\n";
        for (int x = 50; x >= 0; x--)
        {
            cout << x << endl;
        }
        cout << endl;
        cout << " A program that counts up from 30 to 50 in increments of 1\n";
        for (int x = 30; x < 51; x++)
        {
            cout << x << endl;
        }

        cout << " A program that counts down from 50 to 10 in decrements of 2\n";
        for (int x = 50; x > 11; x = x - 2)
        {
            cout << x << endl;
        }

        cout << " A program that counts up from 100 to 200 in increments of 5\n";
        for (int x = 100; x < 201; x = x + 5)
        {
            cout << x << endl;
        }
    }
Iterate through a word

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        for (int x = 0; x < 4; x++)
        {
            string myWord = "ARSH";
            cout << myWord.at(x) << endl;
        }

    }
