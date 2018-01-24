# Start Project

With wordpress using boilerplate


## Steps


1. Create folder

under var/www/<project name>

2. Copy boilerplate

Copy wp-boilerplate to folder, leave .git!

3. Create entry in hosts file

4. Create database

5. change .env file
```
cd /var/www/<project name>/private/.env
```

6. Install npm

```
npm install
```

7. Update composer

```
composer update
```

8. Install theme

```
grunt prompt
```

9. If errors with yaml

```
copy yaml from private to web
```

10. change grunt file

Change grunt theme name to <project-name>





# Install Plugins

## Yoast SEO

1. go to folder

Go to folder in terminal

```
cd /var/www/<folder-name>
```

2. install Yoast

```
composer require wpackagist-plugin/wordpress-seo
```

3. Update composer
```
composer update
```
