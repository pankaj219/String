# String
The String class in Java is a widely used class that represents a sequence of characters. It is part of the java.lang package and provides a rich set of methods for working with strings. Here are some of the most commonly used methods of the String class:

Length-related methods:
=======================

1.int length(): Returns the number of characters in the string.
2.boolean isEmpty(): Checks if the string is empty (length is 0).

Substring methods:
==================

1.String substring(int beginIndex): Returns a new string that is a substring of the original, starting from the specified beginIndex.
2.String substring(int beginIndex, int endIndex): Returns a new string that is a substring of the original, starting from beginIndex and ending at endIndex - 1.

Concatenation methods:
======================
1.String concat(String str): Concatenates the specified string (str) to the end of the original string.

Character extraction methods:
=============================
1.char charAt(int index): Returns the character at the specified index.
2.int codePointAt(int index): Returns the Unicode code point of the character at the specified index.

Search methods:
===============
1.int indexOf(String str): Returns the index of the first occurrence of the specified substring (str) in the string.
2.int indexOf(String str, int fromIndex): Returns the index of the first occurrence of the specified substring (str) in the string, starting from the specified fromIndex.
3.int lastIndexOf(String str): Returns the index of the last occurrence of the specified substring (str) in the string.
4.int lastIndexOf(String str, int fromIndex): Returns the index of the last occurrence of the specified substring (str) in the string, searching backward from the specified fromIndex.

Comparison methods:
===================
1.boolean equals(Object anObject): Checks if the string is equal to the specified object.
2.boolean equalsIgnoreCase(String anotherString): Checks if the string is equal to another string, ignoring case.
3.int compareTo(String anotherString): Compares the string lexicographically with another string.
4.int compareToIgnoreCase(String str): Compares the string lexicographically with another string, ignoring case.

Whitespace trimming methods:
===========================
1.String trim(): Returns a new string with leading and trailing whitespaces removed.

Case conversion methods:
========================
1.String toLowerCase(): Returns a new string with all characters converted to lowercase.
2.String toUpperCase(): Returns a new string with all characters converted to uppercase.

String formatting methods:
==========================
1.static String format(String format, Object... args): Returns a formatted string using the specified format string and arguments.

String splitting methods:
========================
1.String[] split(String regex): Splits the string around matches of the given regular expression.
2.String[] split(String regex, int limit): Splits the string around matches of the given regular expression, up to the specified limit.

These are some of the commonly used methods of the String class in Java. There are many more methods available for handling and manipulating strings in various ways.
