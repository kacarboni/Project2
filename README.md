# Project2
  
// Author: Kaitlyn  Carboni
// Class: C++ Programming
// Professor Butkiewicz
// Due: 5/2/2021

#include<iostream>
using namespace std;

// Base (Parent) Class
class Mammal {
  public: 
  
  void Color ()
  {
    cout << "black";
  }
  
  void makeSound()
  {
    cout << "Grrrrr";
  }

};

//Derived (Child) Class
class Whale : public Mammal
{
  public:
  
  void makeSound()
  {
    cout << "Whistles";
  }
};

//Derived (child) Class
class Elephant : public Mammal
{
  public:
  
  void makeSound()
  {
    cout << "Trumpeting";
  };
  
  int main() {
    Animal myAnimal;
    myAnimal.makeSound();
    cout << myAnimal.Color + " " + myAnimal.makeSound;
    return 0;
   }
}

// Base (parent) Class
class Carnivore
{
  public:
  
  void color()
  {
    cout << "black";
  }
  
  void make Sound()
  {
    cout << "Grrrr";
  }
};

// Derived (child) Class
class Lion : public Carnivore
{
  public:
  
  void makeSound()
  {
    cout << "Roar";
  }
};

// Derived (child) Class
class Dog : public Carnivore
{
  public:
  
  void makeSound()
  {
    cout << "Woof";
  };
  
  int main() {
    Animal myAnimal;
    myAnimal.makeSound();
    cout << myAnimal.color + " " + myAnimal.makeSound;
    return 0;
   }
}
