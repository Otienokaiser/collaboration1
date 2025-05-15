# collaboration1
loafer selling web application

Folder Structure
ecommerce/
├── config/
│   └── db.php              # DB connection
├── public/
│   ├── index.php           # Main landing page
│   ├── login.php
│   ├── register.php
│   └── assets/
│       ├── css/
│       ├── js/
│       └── images/
├── admin/
│   ├── dashboard.php
│   ├── add_product.php
│   ├── manage_orders.php
│   └── inventory.php
├── includes/
│   ├── header.php
│   ├── footer.php
│   └── auth.php            # Auth middleware
├── classes/
│   ├── Product.php
│   ├── User.php
│   ├── Order.php
│   └── Cart.php
├── client/
│   ├── shop.php
│   ├── cart.php
│   └── checkout.php
└── sql/
    └── schema.sql          # DB structure (see below)
