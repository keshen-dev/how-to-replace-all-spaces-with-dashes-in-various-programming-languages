# how-to-replace-all-spaces-with-dashes-in-various-programming-languages
Here are some examples of how to replace all spaces with dashes in various programming languages:

Python:

```
my_string = "Hello World"
my_string = my_string.replace(" ", "-")
print(my_string)
```
JavaScript:

```
let myString = "Hello World";
myString = myString.replace(/\s+/g, '-');
console.log(myString);
```

java

```
String myString = "Hello World";
myString = myString.replaceAll("\\s", "-");
System.out.println(myString);
```
C#:

```
string myString = "Hello World";
myString = myString.Replace(" ", "-");
Console.WriteLine(myString);
```

PHP:

```
$my_string = "Hello World";
$my_string = str_replace(" ", "-", $my_string);
echo $my_string;
```

Ruby:

```
string_with_spaces = "This is a string with spaces"
string_with_dashes = string_with_spaces.gsub(/\s+/, "-")
```

Kotlin:

```
val string = "this is a sample string"
val newString = string.replace(" ", "-")
println(newString)
Output: this-is-a-sample-string
```

Dart:
```
String string = "this is a sample string";
String newString = string.replaceAll(" ", "-");
print(newString);
Output: this-is-a-sample-string
```

C++:
```
#include <iostream>
#include <string>
using namespace std;

int main() {
  string myString = "this is a sample string";
  for (int i = 0; i < myString.length(); i++) {
    if (myString[i] == ' ') {
      myString[i] = '-';
    }
  }
  cout << myString;
  return 0;
}
Output: this-is-a-sample-string
```

Swift:

```
var string = "this is a sample string"
var newString = string.replacingOccurrences(of: " ", with: "-")
print(newString)
```

Bash:
```
string="this is a sample string"
newString=${string// /-}
echo $newString
```

Perl:
```
my $string = "this is a sample string";
$string =~ s/ /-/g;
print $string;
```

C:
```
#include <stdio.h>
#include <string.h>

int main() {
  char string[] = "this is a sample string";
  for (int i = 0; i < strlen(string); i++) {
    if (string[i] == ' ') {
      string[i] = '-';
    }
  }
  printf("%s", string);
  return 0;
}
```
