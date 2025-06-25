
class Animal
{
    public void Animalsound()
    {
        Console.WriteLine("Animal makes a sound");
    }
}

class pig : Animal
{
    public void Animalsound()
    {
        Console.WriteLine("The pig says: wee wee");
    }
}
class dog : Animal
{
    public void Animalsound()
    {
        Console.WriteLine("The dog says: bow bow");
    }
}
class program
{
    static void Main(string[] args)
    {
        Animal myAnimal = new Animal();  // Create a Animal object
        pig myPig = new pig();            // Create a pig object
        dog myDog = new dog();            // Create a dog object
        myAnimal.Animalsound();  // Call the method on the Animal object
        myPig.Animalsound();      // Call the method on the pig object
        myDog.Animalsound();      // Call the method on the dog object
        Console.ReadLine();
    }
}
