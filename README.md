#include <iostream>

using namespace std;
class Box {
   public :
    int height;
    int widht;
    int depth;
    Box() {
      height = 1;
      widht = 1;
      depth = 1;
    }
    Box(int param1){
    height = param1;
    widht = param1;
    depth = param1;
    }
    Box(int par1,int param2,int param3){
    height = par1;
    widht = param2;
    depth = param3;
    }
};

int main() {
    Box boxobj;
    Box boxobj2(2);
    Box boxobj3(9,8,7);

  // Print values
  cout << boxobj.height << " height \t" << boxobj.widht << " width \t" << boxobj.depth << " depth \n";
    cout << boxobj2.height << " height \t" << boxobj2.widht << " width \t" << boxobj2.depth << " depth \n";
    cout << boxobj3.height << " height \t" << boxobj3.widht << " width \t" << boxobj3.depth << " depth \n";


  return 0;
}
