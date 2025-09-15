# 🚀 .NET Learning Phase

Welcome to your journey into the world of **C#** and **.NET**! This repository contains beginner-friendly examples and projects to help you master the fundamentals of C# programming and the .NET ecosystem.

## 🎯 What You'll Learn

### 📚 C# Fundamentals
- **Variables & Data Types** 📊
- **Control Structures** (if/else, loops) 🔄
- **Methods & Functions** ⚡
- **Object-Oriented Programming** 🏗️
- **Exception Handling** 🛡️
- **Collections & LINQ** 📋

### 🌐 .NET Core Concepts
- **Console Applications** 💻
- **Web APIs** 🌍
- **Entity Framework** 🗃️
- **Dependency Injection** 🔧
- **Configuration Management** ⚙️

## 🛠️ Prerequisites

Before you start, make sure you have:

- ✅ [.NET SDK](https://dotnet.microsoft.com/download) (Latest LTS version)
- ✅ A code editor ([Visual Studio Code](https://code.visualstudio.com/) recommended)
- ✅ Basic understanding of programming concepts

## 🏃‍♂️ Quick Start

### 1. Clone this repository
```bash
git clone https://github.com/KeenIsHere/DotNet-Learning-Phase.git
cd DotNet-Learning-Phase
```

### 2. Verify .NET installation
```bash
dotnet --version
```

### 3. Create your first C# application
```bash
dotnet new console -n HelloWorld
cd HelloWorld
dotnet run
```

## 📖 C# Syntax Basics

### 🔤 Variables and Data Types
```csharp
// Basic data types
int age = 25;                    // Integer
string name = "Krishna";         // String
double salary = 75000.50;        // Double
bool isStudent = true;           // Boolean
char grade = 'A';               // Character

// Nullable types
int? nullableInt = null;
```

### 🔧 Methods
```csharp
// Method with parameters and return type
public static int AddNumbers(int a, int b)
{
    return a + b;
}

// Method without return type (void)
public static void DisplayMessage(string message)
{
    Console.WriteLine($"Message: {message}");
}
```

### 🏗️ Classes and Objects
```csharp
// Class definition
public class Student
{
    // Properties
    public string Name { get; set; }
    public int Age { get; set; }
    
    // Constructor
    public Student(string name, int age)
    {
        Name = name;
        Age = age;
    }
    
    // Method
    public void DisplayInfo()
    {
        Console.WriteLine($"Name: {Name}, Age: {Age}");
    }
}

// Creating and using objects
Student student = new Student("Alice", 20);
student.DisplayInfo();
```

### 🔄 Control Structures
```csharp
// If-else statement
if (age >= 18)
{
    Console.WriteLine("Adult");
}
else
{
    Console.WriteLine("Minor");
}

// For loop
for (int i = 0; i < 5; i++)
{
    Console.WriteLine($"Iteration: {i}");
}

// Foreach loop
string[] names = {"Alice", "Bob", "Charlie"};
foreach (string name in names)
{
    Console.WriteLine(name);
}
```

### 📋 Collections
```csharp
// List
List<string> fruits = new List<string> {"Apple", "Banana", "Orange"};
fruits.Add("Grape");

// Dictionary
Dictionary<string, int> scores = new Dictionary<string, int>
{
    {"Alice", 95},
    {"Bob", 87},
    {"Charlie", 92}
};
```

## 🎨 Project Structure

```
DotNet-Learning-Phase/
├── 📁 01-Basics/
│   ├── Variables/
│   ├── DataTypes/
│   └── Operators/
├── 📁 02-Control-Flow/
│   ├── Conditionals/
│   └── Loops/
├── 📁 03-OOP/
│   ├── Classes/
│   ├── Inheritance/
│   └── Polymorphism/
├── 📁 04-Advanced/
│   ├── LINQ/
│   ├── Async-Await/
│   └── File-IO/
└── 📁 Projects/
    ├── Calculator/
    ├── ToDoApp/
    └── WeatherApp/
```

## 🎯 Learning Path

### 🌱 Beginner (Weeks 1-2)
- [ ] Variables and Data Types
- [ ] Basic Input/Output
- [ ] Conditional Statements
- [ ] Loops
- [ ] Methods

### 🌿 Intermediate (Weeks 3-4)
- [ ] Object-Oriented Programming
- [ ] Collections
- [ ] Exception Handling
- [ ] File I/O
- [ ] LINQ Basics

### 🌳 Advanced (Weeks 5-6)
- [ ] Async/Await
- [ ] Web API Development
- [ ] Entity Framework
- [ ] Unit Testing
- [ ] Design Patterns

## 📚 Useful Resources

### 📖 Documentation
- [Microsoft C# Documentation](https://docs.microsoft.com/en-us/dotnet/csharp/)
- [.NET Documentation](https://docs.microsoft.com/en-us/dotnet/)

### 🎥 Video Tutorials
- [C# Tutorial for Beginners](https://www.youtube.com/watch?v=GhQdlIFylQ8)
- [.NET Core Tutorial](https://www.youtube.com/watch?v=C5cnZ-gZy2I)

### 📝 Practice Platforms
- [LeetCode](https://leetcode.com/)
- [HackerRank](https://www.hackerrank.com/domains/tutorials/30-days-of-code)
- [Codewars](https://www.codewars.com/)

## 🤝 Contributing

Feel free to contribute to this learning repository by:

1. 🍴 Forking the repository
2. 🌿 Creating a feature branch
3. 💾 Committing your changes
4. 📤 Pushing to the branch
5. 🔄 Creating a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

If you have any questions or suggestions, feel free to reach out!

- GitHub: [@KeenIsHere](https://github.com/KeenIsHere)
- Email: your.email@example.com

---

### 🌟 Happy Coding! Keep Learning and Building Amazing Things! 🚀

**Remember:** The best way to learn programming is by doing. Start with small projects and gradually take on more complex challenges. Every expert was once a beginner! 💪

---

*Last updated: September 2025* 📅
