# Kost In Lombok
Kost in Lombok is a website to provide boarding house (we usually call it kost in bahasa), bridging between the kost seeker and the kost provider. This website has been made for software Enggineering course project. This website implemented "Simple Reccomender System" for searching the kost based on the user's kost criteria.

# Features
1. Login, Logout and Register (You can register as a kost seeker or kost provider).
2. Authentication.
3. View All Kosts.
4. Search Kost.
5. View recommended kosts.
6. Add Kost to Favorite.
7. Contact the kost provider.
8. Edit profile.
9. Create, Update, Delete Kost (for the kost provider)

# Installation and Usage
At the beginning, you can clone this repository and you have to make sure that your machine has been installed with PHP (8.2.4), composer (2.5.8) and database (This project used XAMPP as a server). After that you can update this repository by using
```bash
composer update
```
Generate the env file for this project (Command bellow used in linux, in windows probably you can use .env-example file and copy it as .env file)

```bash
cp .env-example .env
```

in the project itself (.env file), you can then change the database connection based on yours. Mine used this
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=kost_in_lombok
DB_USERNAME=root
DB_PASSWORD=
```
And then you can make a migration and seed the database using this
```bash
php artisan migrate
php artisan db:seed
```

You can serve the laravel by using
```bash
php artisan serve
```

# Screenshots
## Kost Seeker
![image](https://github.com/ismarapw/kost-in-lombok/assets/76652264/fe682efb-4139-4126-bf51-90916fc5d4de)
![image](https://github.com/ismarapw/kost-in-lombok/assets/76652264/cb9354d2-c84d-4e39-b01d-b94f2680010b)
![image](https://github.com/ismarapw/kost-in-lombok/assets/76652264/9feae726-9de0-4c29-b81f-edc37c023487)
![image](https://github.com/ismarapw/kost-in-lombok/assets/76652264/d2507792-699d-47fa-81bf-4f685044d731)
![image](https://github.com/ismarapw/kost-in-lombok/assets/76652264/d6024996-fa9e-415c-8399-a67e9a497dde)
![image](https://github.com/ismarapw/kost-in-lombok/assets/76652264/9cfe628c-76ca-48d6-a745-04a19afa09ed)
![image](https://github.com/ismarapw/kost-in-lombok/assets/76652264/2eb1a671-a455-4fa2-9e0a-532bea7cf406)

## Kost Provider
![image](https://github.com/ismarapw/kost-in-lombok/assets/76652264/3302446b-282c-456f-8e7c-3a79b65bb58a)
![image](https://github.com/ismarapw/kost-in-lombok/assets/76652264/09a0c5c9-295a-4383-b763-7bf903d0eb1d)
![image](https://github.com/ismarapw/kost-in-lombok/assets/76652264/5800da62-6526-424c-8884-a49a0331216f)
![image](https://github.com/ismarapw/kost-in-lombok/assets/76652264/43702b3b-7b1f-4ca8-afdf-230d4c744643)



