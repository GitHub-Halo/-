#include<iostream>
  using namespace std;
  class Hello
  {
  public :
  string s;
  Hello()
  {
  s="Hello, world!";
  cout<<"第一个程序："<<s<<endl;
  }
  };
  int main()
  {
  new Hello();
  return 0;
  }
