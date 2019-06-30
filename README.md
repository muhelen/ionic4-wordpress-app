# ionic4-wordpress-app
Ionic 4 Wordpress app (iOS &amp; Android)

A simple app build with Ionic v4. 

- The app shows the latest posts. 
- The categories and browse posts by category
- Search through all posts
- Pagination

Build instructions:

``` bash
$ git clone https://github.com/muhelen/ionic4-wordpress-app.git
$ cd ionic4-wordpress-app
$ ionic serve
```


change the `mainUrl` variable in `src/app/services/wordpress.service.ts`

If you have a self-hosted Wordpress blog it should work fine also with rest-api endpoints of your instance. 
https://developer.wordpress.org/rest-api/reference/<br>
If you have a self-hosted wordpress blog change variable wp_org = true<br>
`public wp_org: boolean = true;`<br>
in `src/app/services/wordpress.service.ts`

It looks something like this: 

![Screenshot1](Screenshot1.png)
![Screenshot2](Screenshot2.png)
![Screenshot3](Screenshot3.png)
![Screenshot4](Screenshot4.png)

