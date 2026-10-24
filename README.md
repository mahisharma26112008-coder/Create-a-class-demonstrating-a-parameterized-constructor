# Create-a-class-demonstrating-a-parameterized-constructor

#include<iostream>
using namespace std;
class student{
    public:
    int marks;
    int roll_number;

    student(int m,int r){
        marks=m;
        roll_number=r;
    }
    void display(){
        cout<<"marks :"<<marks<<"\n";
        cout<<"roll number : "<<roll_number<<"\n";
    }
};
int main(){
    student s1(500,101);
    s1.display();

    return 0;
}
