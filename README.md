# Spell Checker

## Welcome to my app!! 👋

The SpellChecker is an app used as An orthographic corrector that detects a word is wrong in the dictionary.



## Technologies

The application uses the Model-View-Controller system architecture to solve the problem. Also uses the ideas of the Object Oriented Programming paradigm of Java.

The text is introduced in a panel. Everytime 0.5secs pass from the last time a key was pressed a concurrency thread checks whether the words in the panel are in the provided dicctionary or not. If a word in the panel is wrong, it is underlined with red.
When a wrong word in clicked, new possible words are provided. This words are selected by using the Levenshtein algorithm which uses dynamic programming to search to find the minimum number of differences between two words.

## Access Locally
The project can be imported as any other Java application. Since the app is not deployed the Java Develpment Kit (JDK) is required.

```
git clone https://github.com/AndresOverflow/SpellChecker.git
cd Levenshtein/out/production/Levenshtein/levenshtein
Execute the levenshtein main function
```
