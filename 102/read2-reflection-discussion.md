### Text Editor Explanation

1. <p>Text editor, as the name implies, is a software that enables the user to  write text. One good example of a text editor is notepad on Windows system.For our Mac users, its TextEdit. Another good example is Office Word. As you can see its a very broad term that encompasses all text writing and managing software. However, not all text editors are suited for programming languages.
2. There are few features I believe are important when it comes to choosing a text editor for programming languages. It should be able to complete the code are you type, highlight function to differentiate codes from different categories, dark mode theme, and  can support many languages and its add-on functions. 
3. Code completion is just another way of saying sentenc completion. Text editor of our choice should be able to suggest few codes based on the spelling. This will not only speed up the coding process, but also reduce human error such as typo or improper opening and closing brakets.
4. Code highlighting function is equivalent of using different colors of highglighter to categorize specific parts of a code line. Programming language is not too dissimilar from our everyday conversational language. It  nouns, pronounse, verbs, adverbs, past tense, future tense and etc. Highlighting with different color makes it easier for the reader(also the writer) to understand the purpose of certain line or word in that particular position
5. Dark mode reduces eye strain.
6. Add-ons, or extensions like on popular browsers, adds an extra layer of customization that will make it even more efficient and power depending on the programmers preference
7. These are the more popular text editors due to having features mentioned above: notepadd++, textwrangler/BB edit, Visual studio code, Atom, Brackets, Sublime text etc.
8. Once you start learning programming language of your choice you will come across the term IDE. It is short for integrated development environment. IDE is a compilation of text editor, manager, debugger, and compiler in one package. Debugger looks for errors in codes, and compiler will transform your code into an a format that can interact with other files.
  
### Command line spark note
1. Spotlight and type terminal
2. type echo $BASH to find out which shell I'm using
3. Single command line option ( -l ) which indicates we are going to do a long listing. A long listing has the following:
  1. First character indicates whether it is a normal file ( - ) or directory ( d )
  2. Next 9 characters are permissions for the file or directory (we'll learn more about them in section 6).
  3. The next field is the number of blocks (don't worry too much about this).
  4. The next field is the owner of the file or directory (ryan in this case).
  5. The next field is the group the file or directory belongs to (users in this case).
  6. Following this is the file size.
  7. Next up is the file modification time.
  8. Finally we have the actual name of the file or directory.
4. Root directory is denoted by single /. Absolute path wiill start with root directory. Rrelative path will start with name of directory inrelation to current location
  + ~ (tilde) - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents
  + . (dot) - This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).
  + .. (dotdot)- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.
5. **CD [location]** command is change directory
  + pwd
    + Print Working Directory - ie. Where are we currently.
  + ls
    + List the contents of a directory.
  + cd
    + Change Directories - ie. move to another directory.
### Files
1. **file [path]** will execute a file in the path
2. Two or more word named directory should be put in quotes
3. Backslash is escape character
4. If the file or directory's name begins with a . (full stop) then it is considered to be hidden
  
