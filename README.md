# How-to-check-the-Age-of-a-user-is-eligible-for-voting-or-not-in-C-.
#include&lt;iostream> using namespace std;  int main() {      int age;     cout &lt;&lt; "Enter age of a user:";     cin>>age;      if (age >= 18) {         cout &lt;&lt; "You are eligible for voting";     } else {         cout &lt;&lt; "You are not eligible for voting";     }      return 0; }
