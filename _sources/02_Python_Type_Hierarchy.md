# Python Type Hierarchy

- Python Type Hierarchy generally represents the types that are actually present in python programming language. There are generally 4 types in python. Those are Numbers, Collections, Callables and Singletons 

  1. **Numbers** : Numbers are further divided into two types.

     - **Integrals** : Intgerals Contains `Integers` and `Booleans`.

     - **Non - Integrals** : It contains `Floats`, `Complex`, `Decimals`, and `Fractions`.

  2. **Collections** : Collections are further divided into three types

     - **Sequences** : Sequences are further divided into two types.  One is mutable sequences which are `Lists` and another one is immutable sequences which are `tuples`, `Strings` etc.

     - **Sets** : Sets are further divided into two types. One is mutable sets which are `Sets` and another one is immutable sets which are `Frozen Sets`.

     - **Mappings** : Mappings are simply hash maps and in python these are dictionaries

  3. **Callables** : Callables are one which we can invoke or which we can Call . Callables in python are `User Defined Functions`, `Generators`, `Classes`, `Instance Methods`, `Class Instances (__call__())`, `Built-in Functions (e.g len(), Open())`, `Built in Methods (e.g my_list.append(x))`

  4. **Singletons** : Singletons in python are `None`, `NotImplemented`, `Ellipsis(...)` etc.