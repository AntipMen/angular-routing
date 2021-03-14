# angular-routing

### Practical work with routing in Angular.

Our application dynamically renders multiple pages without reloading:

- Home;
- Posts - inside routing for each post;
- About -  inside routing to about-extra.

![route1](https://user-images.githubusercontent.com/58369971/111072454-55fcb700-84e3-11eb-819c-fbc488d74dbb.png)

If the user is not sign in, components (pages) are not loaded. This functionality was implement by using Guards in service AuthGuard. 
There is also protection for nested routes on the about page - about-extra pages.

Main page has a software navigation on the button 'Go to Posts' - which go to the posts page.

![route5](https://user-images.githubusercontent.com/58369971/111072452-55642080-84e3-11eb-995c-b38c8f5de4c3.png)

In the project, I practice registering routes, dynamically changing pages, and marking active links.

From the posts page, you can go to the page of each post separately. That was implement through the dynamic routes according to the ID of the required post.

![route2](https://user-images.githubusercontent.com/58369971/111072455-55fcb700-84e3-11eb-81aa-9d02035a8dad.png)

In addition, on the post page, we worked with the queryParams to determine whether to show the id in the list of posts or not.

![route3](https://user-images.githubusercontent.com/58369971/111072450-5432f380-84e3-11eb-8a81-142c0b0905a2.png)

![route4](https://user-images.githubusercontent.com/58369971/111072451-54cb8a00-84e3-11eb-90c6-71620a00db03.png)

The redirect sends the user to the main page. If the user is not sign in and there is also error handling in case of not correct url.

![routing5](https://user-images.githubusercontent.com/58369971/111072453-55642080-84e3-11eb-8321-b14b2b0978ee.png)

The used resolver is applying in practice with a delay of 1.5 seconds.
