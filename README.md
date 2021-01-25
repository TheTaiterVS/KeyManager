1. Add KeyManager.h to your project
2. Include KeyManager.h
3. Create a keyManager class and call a method to validate global input
4. Use method  isKeyPressed(DWORD key, bool repeat = false)  for check input

EXAMPLE:

#include "KeyManager.h"

void main()
{
  keyManager manager;
  manager.switchGlobalInput();
  while(true)
  {
    if(manager.isKeyPressed(VK_INSERT, false)
    {
      cout << "INSERT PRESSED!" << endl;
    }
  }
  return 0;
}
