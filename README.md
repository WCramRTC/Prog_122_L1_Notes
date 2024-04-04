# Programming 122 Notes

- What is wpf
- How do we upload
Certainly! Arrays in C# are used to store a fixed-size sequential collection of elements of the same type. They provide a convenient way to work with collections of data.

Here's a breakdown of C# arrays along with code snippets:

1. **Declaring Arrays:**
   You can declare an array by specifying the type of elements it will hold followed by square brackets `[]` and the name of the array. You can also initialize the array with specific values using curly braces `{}`.

   ```csharp
   // Declaration and initialization of an integer array
   int[] numbers = { 1, 2, 3, 4, 5 };

   // Declaration of an array without initialization
   int[] anotherArray;
   ```

2. **Accessing Elements:**
   You can access individual elements of an array using indexing. The index starts from 0 for the first element and goes up to `Length - 1`.

   ```csharp
   // Accessing elements of the array
   int firstElement = numbers[0]; // Accessing the first element
   int thirdElement = numbers[2]; // Accessing the third element
   ```

3. **Array Length:**
   You can get the length of the array using the `Length` property.

   ```csharp
   // Getting the length of the array
   int length = numbers.Length; // Length of the numbers array
   ```

4. **Iterating Through Arrays:**
   You can use loops like `for` or `foreach` to iterate through the elements of an array.

   ```csharp
   // Using a for loop to iterate through the array
   for (int i = 0; i < numbers.Length; i++)
   {
       Console.WriteLine(numbers[i]);
   }

   // Using a foreach loop to iterate through the array
   foreach (int num in numbers)
   {
       Console.WriteLine(num);
   }
   ```

5. **Modifying Elements:**
   You can modify elements of an array by assigning new values to them.

   ```csharp
   // Modifying elements of the array
   numbers[1] = 10; // Modifying the second element to 10
   ```

6. **Multidimensional Arrays:**
   C# also supports multidimensional arrays, allowing you to create arrays with more than one dimension.

   ```csharp
   // Declaration and initialization of a 2D array
   int[,] matrix = new int[2, 3] { { 1, 2, 3 }, { 4, 5, 6 } };

   // Accessing elements of a 2D array
   int element = matrix[0, 1]; // Accessing the element at row 0, column 1
   ```

7. **Jagged Arrays:**
   Jagged arrays are arrays of arrays. Each element of a jagged array can be an array itself.

   ```csharp
   // Declaration and initialization of a jagged array
   int[][] jaggedArray = new int[3][];
   jaggedArray[0] = new int[] { 1, 2, 3 };
   jaggedArray[1] = new int[] { 4, 5 };
   jaggedArray[2] = new int[] { 6, 7, 8, 9 };

   // Accessing elements of a jagged array
   int value = jaggedArray[1][0]; // Accessing the element at index 0 of the second array
   ```

Arrays in C# are powerful and versatile data structures that are extensively used in various programming scenarios. They provide efficient storage and retrieval of data elements.