#include <iostream>

using namespace std;

float M2mm(float high){ //อันนี้เพื่อเปลี่ยนหน่วยจาก cm เป็น mm ครับ
    float x = high / 100;
    return x;
}

float calBMI(float kg,float M){ //อันนี้คิด BMI จากหน่วยที่แปลงแล้ว
    float BMI = kg / (M * M);
    return BMI;
}

float inputH(){ //อันนี้สำหรับ input ส่วนสูงเป็น cm
    float x;
    cout << "Enter you height [cm]" << endl;
    cin >> x;
    return x;
}

float inputW(){ //อันนี้ input น้ำหนักเป็น kg
    float x;
    cout << "Enter your weight [kg]" << endl;
    cin >> x;
    return x;
}

void printBMI(float BMI){ //อันนี้สำหรับ print output
    cout << "Your BMI = "<< BMI << endl;
}

int main()
{
    float h = inputH();
    float w = inputW();

    float M = M2mm(h);
    float BMI = calBMI(w,M);
    printBMI(BMI);



    return 0;
}
