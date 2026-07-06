## Hi there 👋

<!--
**mchokhna/mchokhna** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fac: ...
-->
 calculator():
    p("Simple Calculator")
    print("1. Add")
    print("2. Subtract")
    prin("3. Multiply")
    print("4. Divide")

    choice = input("Choose (1-4): ")

    num1 = float(input("First number: "))
    num2 = float(input("Second number: "))

    if choice == "1":
        print("Result:", num1 + num2)
    elif choice == "2":
        print("Result:", num1 - num2)
    elif choice == "3":
        print("Result:", num1 * num2)
    elif choice == "4":
        if num2 != 0:
        List the advantages and disadvantages.
            print("Result:", num1 / num2)
        else:
            print("Cannot divide by zero.")
    else:
        print("Invalid choice.")

if __name__ == "__main__":
    calculator()
