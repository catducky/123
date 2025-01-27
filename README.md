#include<bits/stdc++.h>
using namespace std;
int main() {
    cout<<"猜猜我要做甚麼";
    cout<<" A:知道"<<"  B:不知道\n";
    char a;
    while (true){
        cin>>a;
        if(a=='A'||a=='B') break;
        else cout<<"誒不是我很認真打不要亂填";
    }
    switch (a){
    case 'A':
        cout<<"被發現了嗎\n";
        break;
    case 'B':
        cout<<"知道的話就換我害怕了\n";
    }
    cout<<"總之呢!!\n";
    cout<<"祝學長生日快樂~~\n";
    for(int j=0;j<3;j++){
        for(int q=0;q<3;q++){
            for(int i=0;i<5;i++) cout<<" ";
            for(int k=0;k<2;k++) cout<<"*";
        }
        
        cout<<endl;
    }
    for(int w=0;w<3;w++){
        for(int i=0;i<4;i++)cout<<" ";
        for(int j=0;j<18;j++)cout<<"*";
        cout<<endl;
    }
    for(int w=0;w<5;w++){
        cout<<" ";
        for(int j=0;j<24;j++)cout<<"*";
        cout<<endl;
    }
    cout<<"這邊附上一個大蛋糕";
    return 0;
}
