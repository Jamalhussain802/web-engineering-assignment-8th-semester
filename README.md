# Todo and Blog Application

In this assignemnt-based project, I have implemented a session based Todo and Blog application using PDO's approch.

## Salient Features

- Session based Todo App implemention.
- Blog App using PDO.
- Session based authentication mechanism.
- Only logged in users can post new blogs.
- Read blog page is set public.

Using given below credentials, one can post blog using local server, email me at <faisalkhanwaso1122@gmail.com> to get list of users of live server.

```php
    $users = array(
        array("user" => "mubeen@gmail.com", "pass" => "pswd1", "name" => "Mubeen"),
        array("user" => "junaid@gmail.com", "pass" => "pswd2", "name" => "Junaid"),
        array("user" => "rehman@gmail.com", "pass" => "pswd3", "name" => "Rehman"),
    );
```



- Some logical fixes are still pending to do...will fix soon.

## Screenshots

Navbar when there is a guest user.
![Logged-out Navbar](imgs/login into todo.png)
Navbar when there is a logged-in user.
![Logged-in Navbar](imgs/login.png)
On home page there display components of Todo and Read blog are imported from [components.php](components.php) and these same components are used in [todo.php](todo.php) and [blog.php](blog.php), respectively.
![Home Page](imgs/to do list.png)
On [Todo Page](todo.php) there is a add task component with display Todo component.
![Todo Page](imgs/task add in blog.png)
