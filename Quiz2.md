
1. Name and describe the two main operations of a stack (to add and remove data).

push     ( Add a collection of DOM elements onto the jQuery stack.
          An array of elements to push onto the stack and make into a new jQuery object.)

pop     ( method removes the last element of an array, and returns that element.
          This method changes the length of an array.)


2. Name and describe the two main operations of a queue (to add and remove data).

enqueve (adds new items to the end of an array, and returns the new length)

denqueve (removes the last element from an array and returns that element)




3. Draw the tree resulting from adding the following sequence of numbers to an empty tree: 30, 45, 15, 10, 50, 40, 20, 27

                                    30
                              15          45
                            10  20      40   50                      
                                  27


4. Is this tree balanced? If not, which rotation needs to be done? (Use the following rotation as an example: rightRotation(30), or leftRotation(10))

this tree is balanced



5. Now add 29. Is the tree balanced? If not, which rotation needs to be done? (Use the following rotation as an example: rightRotation(30), or leftRotation(10))

                   30
            15             45
        10     27       40    50
            20    29




6. Consider the following tree:
------5
---2-----8
-1--3



Now add 0 to the tree. Which one is the first node to go out of balance?

---5 node to go out of balance

7. How do you fix this node? (Use the following rotation as an example: rightRotation(30), or leftRotation(10))


      ------2
      --1------5
      0------3---8




8. What are the four main steps of mergesort?
--split array in 2
--mergesort  left half
--mergesort right half
--join the two arrays


9. Say you have a program which handles the login queue to a game server. The game server is able to log in one person every one second. Assume that one second must elapse after a person logs in with an empty queue before they are removed from the queue. Draw the state of the queue at 12:00:06, considering the following sequence of events:

At 12:00:00 Hades logs in
At 12:00:00 Ares logs in
At 12:00:00 Zeus logs in
At 12:00:00 Buzz Light Year logs in
At 12:00:02 Kanye West logs in
At 12:00:03 Taylor Swift logs in
At 12:00:03 Darkwing Duck logs in
At 12:00:04 Evil Mickey logs in.

-----12:00:06 that is de guy ---At 12:00:03 Darkwing Duck logs in
                             ---At 12:00:04 Evil Mickey logs in


 10. What is an angular directive?
----AngularJS directives are extended HTML attributes
..examples
The ng-app directive initializes an AngularJS application.
The ng-init directive initializes application data.
The ng-model directive binds the value of HTML controls
 (input, select, textarea) to application data.


11. When specifying an angular directive, you write a function which must return an object called:
a. Directive Constructor
b. Fidel y Chavez Object
c. Directive Definition object
d. Directive Object      

----Directive Definition object

12. What is the relationship between html, the $scope construct, and angular expressions? (Expressions are the ones that are written like so: {{quote}} ).

--- relationships between them, you construct will manage the data of your application as part of a variable it will define, $scope,HTML vocabulary Angular provides is the use of Angular expressions.




13. In order to send ajax requests in Angular, the most accepted programming convention is to create an angular:
a. Module
b. Service
c. Controller
d. $http

----$http




14. In order to create a service, you must use the following angular function:
a. angularApp.controller
b. angularApp.module
c. angularApp.directive
d. angularApp.factory

-------angularApp.factory

15. Do this exercise: https://github.com/Real-Skill/angular-exercises/tree/exercise1 You will need to run git checkout exercise1 in addition to the commands listed in that readme. You do not need to run grunt karma.
