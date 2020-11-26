# Hello-World
/*Try to create a repository

I'm going to learn and review C++.
So I start it here and plan to record my steps.

Let's go for it!*/


#include <iostream>             //头文件
  using namespace std;       //引用库
  
  int main(){
  str persName;
  cin>>persName;
  cout<<persName;
  
  cout<<"Hello World!";    //输出文字，cout是namespace库里的内容，如果不引用库，可以在前面加上std::
  cout<<"I'm learning C++! \n\n";      //换行符的用法
  cout<<"I'm hardworking!"<<endl;       //endl同样起到换行的作用
  
  float ptnum = 0.5;
  int myAge = 35;
  cout << "I am " << myAge << " years old.";
  
  return 0;
  }
  
