# Project
과제



#include <iostream>

using namespace std;

int main()
{
    double a[5];

    cout << "1 번째 학생 점수를 입력해주세요 : ";
    cin >> a[0];

    cout << "2 번째 학생 점수를 입력해주세요 : ";
    cin >> a[1];

    cout << "3 번째 학생 점수를 입력해주세요 : ";
    cin >> a[2];

    cout << "4 번째 학생 점수를 입력해주세요 : ";
    cin >> a[3];

    cout << "5 번째 학생 점수를 입력해주세요 : ";
    cin >> a[4];

    double tot = a[0] + a[1] + a[2] + a[3] + a[4];
    double avg = tot / 5;

    cout << "총점 : " << tot << endl;
    cout << "평균 : " << avg << endl;

    return 0;
}