The application wants to simulate a social app like Twitter.
The app is implemented in C++ with modern features:

    -the classes are under RAII principle
    -move semantics
    -lambda expressions
    -algorithms 
    -regex
    -lvalue & rvalue reference
    -dynamic & static library
    -template
    
The part of GUI features is implemented in QT

It is a multiclient application with TCPsockets. The communication is made with the help of an json class

To memorize the datas of aplication we are using a database from SQLite ( wich most of the code is implemented in C )

Functions of app: 

    -you can follow/unfollow a person ( a social graph )
    -see posts of your friends
    -you can comment on posts
    -you can search for a post that contains #
    -you can search for a user (the algorithm behind is levenshtein distance)
    -you can make a tweet and see referenced tweet 
