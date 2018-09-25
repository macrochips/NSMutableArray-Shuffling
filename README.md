NSMutableArray+Shuffling
=============

A NSMutableArray Category for Shuffling Objects within.

## Features

- Category Based for existing compatibility
- Uses native functions and random algorithm for true shuffling results

## Usage

1. Add NSMutableArray+Shuffling Folder to Project (Preferred to 'Use Groups' and 'Copy Items if Needed').
2. Import Category and Use with NSMutableArray Objects.

## Example

**Code:**

```objc
#import "NSMutableArray+Shuffling.h"

NSMutableArray *mutableArr = [[NSMutableArray alloc] initWithObjects:@"string1", @"string2", @"string3", @"string4", @"string5", nil];
// Shuffling
[mutableArr shuffle];
NSLog(@"Shuffled Array:-\n%@", mutableArr);

/*
Shuffled Array:-
string4
string1
string5
string2
string3
*/
```