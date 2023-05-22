# cplusplus-pattern

// Q.1 Square Pattern
#include <iostream>
using namespace std;

int main() {
  int n;
  cin >> n;

  for (int row = 0; row < n; row++) {
    for (int col = 0; col < n; col++) {
      cout << "*";
    }
    cout << endl;
  }
}
  //Q.2 Hollow Rectangle
  #include <iostream>
using namespace std;

int main() {
  int n;
  cin >> n;

  for (int row = 0; row < n; row++) {
    for (int col = 0; col < n; col++) {
      // star print
      if(row == 0 || row == n-1 || col == 0 || col == n-1){
        cout << "*";
      }
        // inner space
      else{
        cout<<" ";
      }
      
    }
    cout << endl;
  }
}

  //Q.3 Half Pyramid
  #include <iostream>
using namespace std;

int main() {
  int n;
  cin >> n;

  for (int row = 0; row < n; row++) {
    for (int col = 0; col < row + 1; col++) {
      cout << "*";
    }
    cout << endl;
  }
 }
  //Q.4 Inverted Half Pyramid
  #include <iostream>
using namespace std;

int main() {
  int n;
  cin >> n;

  for (int row = 0; row < n; row++) {
    for (int col = 0; col < n - row; col++) {
      cout << "*";
    }
    cout << endl;
  }
}
 //Q.5 Numeric Half pyramid
#include <iostream>
using namespace std;

int main() {
  int n;
  cin >> n;

  for (int row = 0; row < n; row++) {
    for (int col = 0; col <row+1; col++) {
      cout <<col+1;
    }
    cout << endl;
  }
}
  
//Q.6 Inverted Half Pyramid
  #include <iostream>
using namespace std;

int main() {
  int n;
  cin >> n;

  for (int row = 0; row < n; row++) {
    for (int col = 0; col <n-row; col++) {
      cout <<col+1;
    }
    cout << endl;
  }
}
  
  //Q.7 Hollow Inverted Half Pyramid
  #include <iostream>
using namespace std;

int main() {
  int n;
  cin >> n;

  for (int row = 0; row < n; row++) {
    for (int col = 0; col < n - row; col++) {
      if (row == 0 || col == 0 || col == n-row-1){
        cout <<"*";
      }
  //space print
       else{
      cout<<" ";
    } 
    }
    
    cout << endl;
  }
}

//Q.8 Full Pyramid
#include <iostream>
using namespace std;
  int main() {
  int n;
  cin >> n;

  for(int row = 0; row<n; row++){
   for(int col = 0; col<n-row-1; col++){
     cout<<" ";
   }
   for(int col = 0; col<row+1; col++){
    
       cout<<"* ";
    
     }
    cout<<endl;
     }
  
//Q.9 Hollow Pyaramid Pattern

#include <iostream>
using namespace std;

int main() {
  int n;
  cin >> n;

  for(int row = 0; row<n; row++){
   for(int col = 0; col<n-row-1; col++){
     cout<<" ";
   }
   for(int col = 0; col<2*row+1; col++){
     if(col == 0 || col == 2*row || row == n-1){
       cout<<"*";
     }
     else{
       cout<<" ";
     }
     } 
   cout<<endl;
 }
}
              
//Q.10 inverted full Pyramid
#include <iostream>
using namespace std;

  int main() {
  int n;
  cin >> n;

  for(int row = 0; row<n; row++){
   for(int col = 0; col<row; col++){
     cout<<" ";
   }
   for(int col = 0; col<n-row; col++){
    
       cout<<"* ";
    
     }
    cout<<endl;
     }
    }
               
 //Q.11 Solid Diamond 
#include <iostream>
using namespace std;
  int main() {
  int n;
  cin >> n;

  for(int row = 0; row<n; row++){
   for(int col = 0; col<n-row-1; col++){
     cout<<" ";
   }
   for(int col = 0; col<row+1; col++){
    
       cout<<"* ";
     }
    cout<<endl;
     }
   //inverted Part
   for(int row = 0; row<n; row++){
   for(int col = 0; col<row; col++){
     cout<<" ";
   }
   for(int col = 0; col<n-row; col++){
     cout<<"* ";
     }
   cout<<endl;
 }
}
              
