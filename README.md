# Project2

class Mammal {
  public: 
  
  VOID NGNKG ()
  {
    COUT << "FGEEG";
  }
  
  void makeSound()
  {
    cout << "Grrrrr";
  }

};

class Whale : public Mammal
{
  public:
  
  void makeSound()
  {
    cout << "Whistles";
  }
};

class Elephant : public Mammal
{
  public:
  
  void makeSound()
  {
    cout << "Trumpeting";
  }
}

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

class Lion : public Carnivore
{
  public:
  
  void makeSound()
  {
    cout << "Roar";
  }
};

class Dog : public Carnivore
{
  public:
  
  void makeSound()
  {
    cout << "Woof";
  }
}
