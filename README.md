# LEC-7-EXERCISES

Theme Park

    #include <iostream>
    using namespace std;
    int main()
    {

        cout << "Enter your height in meters: \n";
        double height ;
        cin >> height;

        cout << "Enter your age: \n";
        int age;
        cin >> age;

        if (( height > 0.5) && (age > 4))
        {
            cout << "You can enter" << endl;
        }
        else {
            cout << "Sorry, you can't" << endl;
        }
        
        return 0;
    }

//EXERCISES

 France (Primitive Quiz)

    #include <iostream>
    using namespace std;
    int main()
    {
        string paris;
        cout << "What is the Capital of France? " << endl;
        cin >> paris; 

        if (paris == "Paris" || paris == "paris")
            cout << "you are right!" << endl;

        else if (paris != "Paris" && paris != "paris") {
            cout << "error" << endl;
        }
    }


Letter Checker Vowels Consonant

    #include <iostream>
    using namespace std;

    int main()
    {
        char l;
        cout << "Please enter a letter to psecify if it's a consonant or vowel: ";
        cin >> l;

        if (l == 'a' || l == 'e' || l == 'i' || l == 'o' || l == 'u' || l == 'A' || l == 'E' || l == 'I' || l == 'O' || l == 'U')
        {
            cout << "\nIt's a vowel" << endl;
        }

        else
        {
            cout << "\nIt's a consonant" << endl;
        }
    }



Extension Problem (Optional)

    #include <iostream>
    using namespace std;

    int main()
    {
        char l;
        cout << "Please enter a letter to psecify if it's a consonant or vowel: ";
        cin >> l;
        if (!isalpha(l))
        {
            cout << "\nInvalid Input" << endl;
        }
        else if (l == 'a' || l == 'e' || l == 'i' || l == 'o' || l == 'u' || l == 'A' || l == 'E' || l == 'I' || l == 'O' || l == 'U')
        {
            cout << "\nIt's a vowel" << endl;
        }

        else
        {
            cout << "\nIt's a consonant" << endl;
        }
    }


Mark my Words Grades

      #include <iostream>
      using namespace std;
      int main()
      {
          cout << "Write your Grade: " << endl;
          double grade;
          cin >> grade;

          if (grade > 70) {
              cout << "Your grade is A " << endl;
          }
          else if (grade >= 60 && grade < 70) {
              cout << "Your grade is B " << endl;
          }
          else if (grade >= 50 && grade < 60) {
              cout << "Your grade is C " << endl;
          }
          else if (grade >= 40 && grade < 50) {
              cout << "Your grade is D " << endl;
          }
          else if (grade <= 40) {
              cout << "Your grade is F " << endl;
          }
          else {
              cout << "Invalid Output" << endl;
          }

      }



Starting a Band

            #include<iostream>
            #include<string>
            using namespace std;
            int main()
            {
                  bool musician;
                  string answer;
                  string instrument;

                  cout << "Do you play any instrument? " << endl;;
                  cout << "Y for yes " << endl;
                  cout << "N for no " << endl;
                  cin >> answer;

                  if (answer == "y" || answer == "Y")
                  {
                        musician = true;
                        if (musician == true)
                        {
                              cout << "What kind of insturment you can play?" << endl;
                              cout << "D for drummer " << endl;
                              cout << "G for guitar " << endl;
                              cout << "O for others " << endl;
                              cin >> instrument;

                              if (instrument == "d" || instrument == "D")
                              {
                                    cout << "You're in the group drummer!" << endl;
                              }
                              else if (instrument == "g" || instrument == "G")
                              {
                                    cout << "You're in the group guitarist!" << endl;
                              }
                              else if (instrument == "o" || instrument == "O")
                              {
                                    cout << "I'm actually looking for a guitarist or drummer at the moment." << endl;
                                    cout << "Please contact me if you know someone." << endl;
                                    cout << "Thanks!" << endl;
                              }
                              else
                              {
                                    cout << "What? Please try again." << endl;
                              }
                        }
                  }
                  else if (answer == "N" || answer == "n")
                  {
                        musician = false;
                        cout << "I'm looking for a person who can used instruments specifically a guitar or drum." << endl;
                        cout << "Please contact me if you know someone." << endl;
                        cout << "Thanks!" << endl;
                  }
                  else
                  {
                        cout << "What? Please try again." << endl;
                  }

                  return 0;
            }

    
    
Time Killing
  
      #include<iostream>
      using namespace std;
      int main()
      {
            cout << "I'm in Dubai Mall waiting for a friend." << endl;
            cout << "My friend is late." << endl;

            int time; 
            int minutes;
            int money;
            cout << "How many more minutes do I have to wait for my friend? " << endl;
            cin >> time;
            if (time >= 15)
            {
                  cout << "Do you have money? How much?" << endl;
                  cin >> money;
                  if (money > 5)
                  {
                        cout << "You have money. Let's go buy a drink and wait for him" << endl;
                  }
                  else
                  {
                        cout << "Let's just walk around the mall" << endl;
                  }
            }
            else
            {
                  cout << "Just wait for them." << endl;
            }
            return 0;
      }
      
      
   
Earthquakes

    #include <iostream>
    using namespace std;
    int main()
    {
        double magnitude;
        cout << "Write the Magnitude of the Earthquake: \n" << endl;
        cin >> magnitude;

        if (!(magnitude > 2.0)) {
            cout << magnitude << " is a Micro Earthquake" << endl;
        }
        else if (!(magnitude > 3.0)) {
            cout << magnitude << " is a Very Minor Earthquake" << endl;
        }
        else if (!(magnitude > 4.0)) {
            cout << magnitude << " is a Minor Earthquake" << endl;
        }
        else if (!(magnitude > 5.0)) {
            cout << magnitude << " is a Light Earthquake" << endl;
        }
        else if (!(magnitude > 6.0)) {
            cout << magnitude << " is a Moderate Earthquake" << endl;
        }
        else if (!(magnitude > 7.0)) {
            cout << magnitude << " is a Strong Earthquake" << endl;
        }
        else if (!(magnitude > 8.0)) {
            cout << magnitude << " is a Major Earthquake" << endl;
        }
        else if (!(magnitude > 10.0)) {
            cout << magnitude << " is a Great Earthquake" << endl;
        }
        else {
            cout << "is a Meteoric Earthquake" << endl;
        }
        cin.get();
        return 0;
    }



 
