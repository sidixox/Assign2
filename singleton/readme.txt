
Modify all necessary files in this directory so that the Logger class can only
be instantiated once. That instance should be used across all classes which
access the Logger.

1. In the Logger class, make the constructor private to prevent external instantiation.
2. Add a static method `getInstance` in the Logger class to get the singleton instance.
3. In each class (SomeClass and SomeOtherClass) that uses the Logger, replace the direct instantiation with a call to `Logger.getInstance()`.

Follow any additional instructions present in comments.
