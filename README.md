# Events RESTful API 
### The final project for the Udemy course "Go - The Complete Guide" (instructor Maximilian Schwarzmüller)

<ul>
<li>register as a user</li>
<li>login, authentication through JWT, token shared through authorization header</li>
<li>a user can create an event</li>
<li>anyone can view the events</li>
<li>a user can update or delete the events he created</li>
<li>as a user, register/cancel registration for an event</li>
</ul>

### Utilized libraries:

<ul>
<li>Gin - HTTP web framework <br/>
github.com/gin-gonic/gin</li>

<li>A go implementation of JSON Web Tokens <br/>
 github.com/golang-jwt/jwt/v5</li>
 
 <li> A sqlite3 driver that conforms to the built-in database/sql interface (an embedded database) <br/>
github.com/mattn/go-sqlite3 (a GCC is required to run it) <br/>
What is GCC? The GNU Compiler Collection, commonly known as GCC, is a set of compilers and development tools available for Linux, Windows, various BSDs, and a wide assortment of other operating systems. It includes support primarily for C and C++ and includes Objective-C, Ada, Go, Fortran, and D. <br/>
https://code.visualstudio.com/docs/cpp/config-mingw
</li>
<li>Hashing library: golang.org/x/crypto</li>


