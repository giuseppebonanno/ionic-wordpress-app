# ionic-wordpress-app

Ionic Wordpress app (iOS &amp; Android)

This is an updated version of [juliansava](https://github.com/julianvasa/ionic5-wordpress-app).

- The app shows the latest posts.
- The categories and browse posts by category
- Search through all posts
- Pagination

## Run

To try it out change the `mainUrl` variable in `src/app/services/wordpress.service.ts` and run

```console
> ionic serve
```

If you have a self-hosted Wordpress blog it should work fine also with rest-api endpoints of your instance.
https://developer.wordpress.org/rest-api/reference/<br>
If you have a self-hosted wordpress blog change variable wp_org = true<br>
`public wp_org: boolean = true;`<br>
in `src/app/services/wordpress.service.ts`

Please support this project by simply putting a Github star ⭐ <br>
Share this library with friends on Twitter and everywhere else you can. 🙏<br>
Check out also ionic6-wordpress-app based on React 🎉<br>
https://github.com/julianvasa/ionic6-wordpress-react-app

It looks something like this:

![Screenshot1](Screenshot1.png)
![Screenshot2](Screenshot2.png)
![Screenshot3](Screenshot3.png)
![Screenshot4](Screenshot4.png)
