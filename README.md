# conventions
Git, programming and Editor conventions to follow

### 1. Git
The whole point of using a version control system is to ideally work on different versions of
the same codebase or one may call them as different branches. While we collaborate code it is
important to properly follow some conventions.

#### 1.1 Mandatory Branches in Git
Always remember that while using a service like Github or an equivalent of it, it is generally
suggestible to have two compulsory branches that are part of your code base.

- `master`
- `production`

Using the above two branches must be a compulsion if you work as an Organization or as a Community,
So the idea here is `master` branch always contains the latest piece of code that will/would be 
residing in your codebase. The code that which resides here can be resultant of a direct push to 
this branch (or) can be a PR [Pull Request] made to this branch. Basically the whole point here is
to imply that `master` branch can be considered your parent branch of your project (or) repository.

Also it is important to have a branch named `production` which can be an equivalent of latest stable
piece of code that which resides in your codebase. Apart from considering this as a backup branch one
can push code to this branch after a succesfull production of the application.

### 2. Programming
Given the choice it is recommended to use text editor programs or text editor's that are light weight
for writing code. So in order to go ahead there are particular norms that one should take into
consideration.

#### 2.1 Javasript

Code conventions :

```javascript
        // bad
        var a = "string";
        var b = 23;
        var c = true;

        // good
        var a = "string",
            b = 23,
            c = true;

        // bad
        var arr = new Array();
        var str = new String();
        var num = new Number();
        var boo = new Boolean();
        var obj = new Object();
        var reg = new RegExp();
        var fun = new function();

        // good
        var arr = [],
            str = "",
            num = 0,
            boo = false,
            obj = {},
            reg = /()/,
            fun = function(){};
```

### 2.2 Python
Coming Soon
