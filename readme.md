<h1 align='center'>
  Hi, Nice to Meet You! <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px">
</h1>

## About me

```c++
#!/usr/bin/cpp
#include <iostream>
#include <string>
#include <vector>

using namespace std;

class Student{
private:
  string name;
  string role;
  vector<string> languages_spoken;
  
public:
  Student() {
    name = "Theodor Costea";
    role = "Bachelor's in Computer Science";
    languages_spoken = {"en_US", "fr_FR", "ro_RO"};
  }

  void say_hello() {
    cout << "Hi there, thanks for dropping by, hope you find this profile interesting" << endl;
  }

  void show_profile() {
    cout << "/**== Profile ==**/" << endl;
    cout << "Name: " << name << endl;
    cout << "Role: "<< role << endl;

    cout << "Languages Spoken: "<< endl;
    for (const auto& lang : languages_spoken) {
      cout << lang << " ";
    }
    cout << endl;
  }
};

int main() {
  Student me;
  me.say_hello();
  me.show_profile();

  return 0;
}
```

## Github Stats
[![](https://github-readme-stats.vercel.app/api?username=teiyo-o)](https://github.com/anuraghazra/github-readme-stats)