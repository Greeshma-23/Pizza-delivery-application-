# Pizza-delivery-application-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Pizza Delivery</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <h1>Order Pizza</h1>
  <form id="orderForm">
    <input type="text" id="name" placeholder="Your Name" required />
    <input type="text" id="address" placeholder="Delivery Address" required />
    <select id="pizzaType">
      <option value="Margherita">Margherita</option>
      <option value="Pepperoni">Pepperoni</option>
      <option value="Veggie">Veggie</option>
    </select>
    <input type="number" id="quantity" placeholder="Quantity" required />
    <button type="submit">Order Now</button>
  </form>
  <script src="script.js"></script>
</body>
</html>
