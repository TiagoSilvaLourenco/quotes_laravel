# Quotes System with Laravel 11

The motivation behind this project is to obtain the best prices from suppliers and to better manage the products that are requested by stores.

## Technologies

<div align="center" style="margin-top: 50px">
    <a href="https://www.php.net">
        <img            
            src="https://www.php.net/images/logos/new-php-logo.svg"
            alt="PHP Logo"
            width="200">
    </a>
</div>

<div align="center"  style="margin-top: 50px"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></div>

<div align="center"  style="margin-top: 50px"><a href="https://alpinejs.dev/" target="_blank"><img src="https://alpinejs.dev/alpine_long.svg" width="300" alt="AlpineJS Logo"></a></div>

<div align="center"  style="margin-top: 50px"><a href="https://dev.mysql.com/doc/" target="_blank"><img src="https://www.mysql.com/common/logos/logo-mysql-170x115.png" width="175" alt="MySQL Logo"></a></div>

<div align="center"  style="margin-top: 50px"><a href="https://tailwindcss.com/docs/installation" target="_blank"><img src="https://tailwindcss.com/_next/static/media/tailwindcss-mark.3c5441fc7a190fb1800d4a5c7f07ba4b1345a9c8.svg" width="200" alt="Tailwind CSS Logo">
<p style="margin-top: 5px; font-size: 28px; color: white;">tailwind</p>
</a></div>

## Description

This project generates quotations for products that are needed by stores; for example: a buyer needs to buy products for certain stores in the company, so quotations are needed for products from many suppliers. The quotation system then obtains all the prices updated by the suppliers and lists the product with the best price.

That's basically it.

### How work

To make a stock request, the store needs to read the product's barcode. The system searches for the barcode in the EAN standard and brings up the product data. After that, the stock clerk simply enters the desired quantity and, at the end of the verification, makes a stock replenishment request.

The system has a login system controlled by access level according to the type of user. Each type of user has their own screens that show only the features that are appropriate for them.

For the company's stores, they only enter the quantity of products they need.

For suppliers, they only update the prices of the products they need.

For buyers and administrators, they can register users of the system and define the type of user of the system, for example: buyers, suppliers and stores.

Buyers and administrators can also register products and link this product to the type of user, who supplies and who distributes.

Features that are still missing:

- Create the algorithm that makes the quotation
- Send the products requested by the stores to the purchasing department
- Assemble the order made by the buyer and send it to the supplier

**If you want to know more about the project or talk about it, please send me an email.**
