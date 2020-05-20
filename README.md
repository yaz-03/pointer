#include <iostream>
using namespace std;
int main() {
  int arr[5],i;
   for (i = 0; i < 5; i++) {
      cout << "Enter elements: " << i << " : ";
      cin >> arr[i];
   }
   int *ptr = &arr[0];
   cout<<"you entered: ";
   for(int i = 0; i < 5; i++) {  
      cout<< *ptr <<" ";
      ptr++;
   }
   return 0;
}
