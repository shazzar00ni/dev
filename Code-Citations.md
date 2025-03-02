# Code Citations

## Purpose
This document provides guidelines on how to properly cite code in your projects.

## Guidelines

1. **Direct Code Citation**:
    - When directly quoting code from another source, enclose the code in quotation marks and provide a reference to the original source.
    - Example:
      ```python
      # As cited from "Python Cookbook" by David Beazley and Brian K. Jones
      def flatten(nested_list):
          for item in nested_list:
              if isinstance(item, list):
                  yield from flatten(item)
              else:
                  yield item
      ```

2. **Modified Code Citation**:
    - If you modify code from another source, indicate the original source and describe the modifications.
    - Example:
      ```javascript
      // Modified from "JavaScript: The Good Parts" by Douglas Crockford
      function isEven(num) {
          return num % 2 === 0;
      }
      ```

3. **Attribution in Comments**:
    - Always include comments in your code to attribute the original author and source.
    - Example:
      ```java
      // Original code by John Doe from "Effective Java"
      public class Singleton {
          private static final Singleton INSTANCE = new Singleton();
          private Singleton() {}
          public static Singleton getInstance() {
              return INSTANCE;
          }
      }
      ```

4. **Bibliography**:
    - Include a bibliography section at the end of your document or project to list all sources.
    - Example:
      ```
      ## Bibliography
      - Beazley, David, and Brian K. Jones. "Python Cookbook." O'Reilly Media, 2013.
      - Crockford, Douglas. "JavaScript: The Good Parts." O'Reilly Media, 2008.
      - Bloch, Joshua. "Effective Java." Addison-Wesley, 2008.
      ```

## Conclusion
Proper citation of code is crucial for maintaining academic integrity and respecting the intellectual property of others. Always ensure to give credit where it is due.
