# C# || Operator Reference

## C# code - No need to download anything, this code works in your browser
AmieDD www.amiedd.com
Code, Cosplay, and Games


```C# runnable
// { autofold
bool SecondOperand()
{
    Console.WriteLine("Second operand is evaluated.");
    return true;
}

bool a = true || SecondOperand();
Console.WriteLine(a);
// Output:
// True

bool b = false || SecondOperand();
Console.WriteLine(b);
// Output:
// Second operand is evaluated.
// True

// { autofold
    }
}
// }
```

# About C# || Operators

The conditional logical OR operator || calculates the logical OR of its bool operands. The result of x || y is true if either x or y evaluates to true. If not the result is false. If the first operand evaluates to true, the second operand is not evaluated and the result of operation is true.
