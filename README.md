# Java-basics-notes
My java learning journey and practice programs
1.identifiers_notes
-Rules for defining java identifiers
2. Reserved words
- keywords
- reserved literals
3.Datatypes
  -numeric datatypes
  - non-numeric datatypes
4.Literals
-Intergral literals
-Floating point literals
-Boolean literals
-char literals
-string literals
-Binary literals
5. Arrays
-arrays declaration
- arrays creation
- arrays initialisation
- one dimensional arrays
- two dimensional arrays
- multidimensional arrays
- length and length method
  6.Array variable assignment
  7. Variables
  - Primitive variables
  - Reference variables
    8. Based on the position of Decalartion and Behaviour, three types
    -Instance Variable
    -Static Variable
    -Local Variable
    ALL THESE CASES AND DIFFERENT SITUATION PRATICE ON VS CODE
    9.Local variable
    10. Variable number of argument methods
    -difference cases
    - equivalence between variable argument parameter and one dimensional array
11. Structure of java(main method)
   - enhancement in the latest version as compare to previous one
12. Command line argument
13. Java coding standards
    - coding standards for class name
    - coding standards for interface name
    - coding standards for method name
    - coding standards for variable name
    - coding standards for constant name
  14. Java Bean coding standards
    - Syntax for setter method
    - coding standards for listeners
  15. Operators and assignments
    - Increament and decreament operator
    - Arthematic operators
    - String concatenation operator
    - Relational operator
    - Equality operator
    - Difference between (==) and.equals method
    - instanceof operator
    - Bitwise operators
    - Bitwise complement operator
    - Boolean complement operator
    - short- Circuit operators (&&,||)
    - Type cast operator
    - implicit type casting
    - explicit type casting
    - Assignment operator
    - Conditional operator
    - new operator
    - [] operator
    - java operator precedence
    - evaluation order of java operands
  16. Flow control
    - Selection Statement
      #if-else statement: syntax, errors, method
      #switch statement: syntax, errors, nethod, default case
    - Iterative statement
      #while
      #do-while
      #for
      #for-each loop
      # difference between iterator and iterable
      
    - Transfer statement
      #break
      labeled break statement 
      #continue
      labeled continue statements 
      #return
      # try-catch-finally
      #assert
  17. Java source file structure
  18. Import statement
   -explicit class import
   -implicit class import
  -Static import
19.Package
- different conditions and cases related to packages.
  program of checking whether the number is prime or not
- java basic architecture
20. class level modifiers
  - public
  - final
  - native
  - private
  - abstract
  - strictfp
  - default
  - static
  - trasient
  - protected
  - synchronised
  - volatile
21. diff. between access modifier and access specifier
22. Interfaces
23. Adapter classes
24. Role of new keyword
------------------------------------------------------OOPS-------------------------------------------
DATA HIDING
ABSTRACTION
ENCAPSULATION
TIGHTLY ENCAPSULATED CLASSES
IS -A RELATIONSHIP
HAS A RELATIONSHIP
METHOD SIGNATURE
OVERLOADING
OVERRIDING
DIFFERENT CASES RELATED TO OVERRIDING
DIFFERENCE BETWEEN METHOD HIDING AND OVER RIDING
POLYMORPHISM
COUPLING
COHENSION
OBJECT TYPE CASTING
STATIC CONTROL FLOW
-RIWO
STATIC BLOCK
INSTANCE CONTROL FLOW
-----------------------------------OOPS CONCEPTS COMPLETED-------------------------------------------
=======================CONSTRUCTORS==========================
DIFFERENCE BETWEEN CONSTRUCTORS AND INSTANCE BLOCK
DEFAULT CONSTRUCTORS
OVERLOADED CONSTRUCORS
SINGLETON CLASSES
=============================================================
===============EXCEPTION HANDLING============================
RUNTIME STACK MECHANISM
DEFAULT EXCEPTION HANDLING IN JAVA
EXCEPTION HIERARCHY
THROWABLE
-EXCEPTION
-ERRORS
THROWS KEYWORD
CHECKED AND UNCHECKED EXCEPTION
CUSTOMISED EXCEPTION HANDLING USING TRY CATCH FINALLY
DIFFERENCE BETWEEN FINAL FINALLY AND FINALISE
THROW STATEMENT
TOP 10 EXCEPTIONS
-ArrayOutOfBoundException
-NullpointerException
-ClassCastException
-StackOverFlowException
-NoClassDefFoundError
-ExceptionInInitialiserError
-IllegalArgumentException
-NumberFormatException
-IllegalStateException
-AssertionError
TRY WITH RESOURCES
MULTI CATCH BLOCK
===============================================================
=========================MULTITHREADING========================
THREAD SCHEDULAR
OVERRINDING START METHOD
THREAD LIFE CYCLE
THREAD CLASS CONSTRUCTORS
THREAD PRIORITIES
DEFAULT PRIORITY
PREVENT A THREAD EXECUTION
-YEILD()
-JOIN()
-SLEEP()
SYNCHRONIZATION
CLASS LEVEL LOCK
THREAD COMMUNICATION
-WAIT()
-NOTIFY()
-NOTIFYALL()
DEAD LOCK
DAEMON THREAD
DEFAULT NATURE OF THREAD
MULTIPLE INHERITANCE ENHANCEMENTS
-THREAD GROUP
LOCK INTERFACE()
RENTERANT LOCK()
DIFFERENT METHODS ON RENTERANT LOCK()
THREAD POOL
THREADLOCAL
================================================================
==========================INNER CLASSES=========================
TYPES OF INNER CLASSES
- NORMAL OR REGULAR INNER CLASSES
- METHOD LOCAL INNER CLASSES
- ANONYMOUS INNER CLASSES
- STATIC METHOD INNER CLASSES
ACCESSING INNER CLASSES
- FROM STATIC AREA
- FROM INSTANCE AREA
DIFFERENT COMBINATIONS OF CLASSES WITHIN INTERFACE OR INTERFACE WITHIN CLASSES
=================================================================
====================JAVA.LANG.PACKAGE============================
-JAVA.LANG.OBJECT
--ALL 12 METHODS OF OBJECT 
  1.PUBLIC STRING TOSTRING()
  2.PUBLIC NATIVE INT HASHCODE()
  3.PUBLIC BOOLEAN EQUALS(OBJECT O)
  4.PROTECTED NATIVE OBJECT CLONE() THROWS CLONENOTSUPPORTEXCEPTION
  5.PROTECTED VOID FINALIZE() THROWS THROWABLE
  6. PUBLIC FINAL CLASS GETCLASS()
  7. PUBLIC FINAL VOID WAIT() THROWS INTERRUPTED EXCEPTION
  9. PUBLIC FINAL NATIVE VOID WAIT (LONG MS) THROWS INTERRUPTEDEXCEPTION
  10.PUBLIC FINAL NATIVE VOID WAIT(LONG MS, INT NS) THROWS INTERRUPTEDEXCEPTION
  11.PUBLIC NATIVE FINAL VOID NOTIFYALL()
--THERE IS ANOTHER METHOD BUT IT IS INTERNALLY REQUIRE FOR OBJECT CLASSES
  12.PRIVATE STATIC NATIVE VOID REGISTERNATIVES()
-JAVAA.LANG.STRING
--DIFFERENCE BETWEEN STRING AND STRINGBUFFER
--STRING CONSTRUCTORS(6 TYPES)
--STRING METHODS
--TO CREATE IMMUTABLE CLASS
--STRINGBUFFER
  -STRING CONTRUCTORS
  -IMPORTANT METHODS OF STRING STRINGBUFFER
--STRINGBUILDER
  -DIFFERENCE BETWEEM STRING BUILER AND STRING BUFFER
--WRAPPER CLASSES
  -CONSTRUCTORS
--UTILITY METHODS
  1.VALOF()
  2.XXXValue()
  -charValue()
  -booleanValue()
  3.pareXXX()
  4.toString()
  Patrial Hierarchy of java.lang.Package
  -void class
Autoboxing and Auto-Unboxing
Relation between (==) operator and .equals()
#Contract between .equals() and Hashcode()
