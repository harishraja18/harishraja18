#include <iostream>

using namespace std;

int main() {

    string name = "Harish Raja";
    int bugs = 0;

    cout << "Hello, I'm " << name << ".\n\n";

    cout << "I don't have everything figured out yet.\n";
    cout << "I'm just building, learning, and getting better.\n\n";

    while (true) {
        learn();
        build();
        fail();
        debug();
        repeat();
    }

    return 0;
}
