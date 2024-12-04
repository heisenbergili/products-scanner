$${\color{orange}Heisenberg \space \space \color{Red}Product \space \space Scanner \space \space project}$$

##

### $\textsf{\color{#5bc0de}{• Decription:}}$
The application is for searching the details of a product (calories, categories, Nutri-Score, etc.) using its barcode or its name.

<p align="center">
    <img src="https://github.com/user-attachments/assets/c140ab74-cddc-41d1-bf06-67e824bdbf70" alt="Main Screen" width="150" height="300">
<p>

•	The user can see the recent products they searched for. They can click to view the details on the detail screen, search for a product, add a product to favorites, or navigate to the favorites screen.

##

### $\textsf{\color{#5bc0de}{• Detail screen:}}$
After searching or clicking on a recent product, the user can view the product's details.

<p align="center">
    <img src="https://github.com/user-attachments/assets/b9e3d5dc-42b6-436b-8241-4d128453c9db" alt="Detail Screen" width="150" height="300">
<p>

•	The user can go back to the main screen, add a product to favorites, or navigate to the favorites screen.

##

### $\textsf{\color{#5bc0de}{• Favorite screen:}}$
When the user clicks to navigate to the favorites screen, they see all the products they have added to their favorites.

<p align="center">
    <img src="https://github.com/user-attachments/assets/184f851c-7f36-49cf-b5ee-5d5569ef5b9e" alt="Favorite Screen" width="150" height="300">
<p>

•	The user can go back to the main screen, or click on product to see it details.

##
> [!IMPORTANT]
> To add a product to the favorites screen or navigate to it, the user must be authenticated. 
> All the data of favorite screen will be stored in the firebase database  
##

### $\textsf{\color{#5bc0de}{• Login screen:}}$

<p align="center">
    <img src="https://github.com/user-attachments/assets/1d7c5186-e229-422e-b1d2-d0f6e395bab2" alt="Login Screen" width="150" height="300">
<p>

•	The user can be authorized to perform all actions within the application.


# Service REST

For product details, calls to the following REST service are made : https://world.openfoodfacts.org/api

To search for a product by its name, the following API can be used: https://world.openfoodfacts.org/cgi/search.pl?search_terms=[product name]&json=1


## Auteur

**Heisenbergili** filalii2002@gmail.com