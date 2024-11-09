<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <title>Dropdown Buttons</title>
   <style>
     * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f3f3f3;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container {
    width: 90%;
    max-width: 400px;
    background: #fff;
    border: 2px solid #f3c040;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    text-align: center;
}

h2 {
    color: #ff3e72;
    margin-bottom: 20px;
    font-size: 24px;
    font-weight: bold;
}

.box {
    border: 1px solid #f3c040;
    border-radius: 8px;
    padding: 10px;
    margin-bottom: 10px;
    position: relative;
}

.header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    cursor: pointer;
}

.header label {
    font-weight: bold;
    margin-right: auto;
}

.discount {
    background: #ff3e72;
    color: white;
    padding: 2px 8px;
    font-size: 12px;
    border-radius: 4px;
    margin-left: 5px;
}

.price {
    font-weight: bold;
}

.old-price {
    text-decoration: line-through;
    color: #999;
    font-size: 12px;
    margin-left: 5px;
}

.most-popular {
    position: absolute;
    top: -10px;
    right: 15px;
    background: #ff3e72;
    color: white;
    font-size: 10px;
    padding: 4px 6px;
    border-radius: 4px;
}

.description {
    font-size: 12px;
    color: #666;
}

.details {
    display: none;
    margin-top: 10px;
    text-align: left;
}

.option {
    display: flex;
    align-items: center;
    margin-top: 8px;
}

.option label {
    margin-right: 5px;
    font-size: 14px;
}

.option select {
    margin-right: 10px;
    padding: 5px;
    font-size: 14px;
}

.footer {
    margin-top: 20px;
    font-size: 14px;
    color: #ff3e72;
}

button {
    background-color: #ff3e72;
    color: white;
    padding: 10px;
    width: 100%;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
    margin-top: 10px;
}

button:hover {
    background-color: #e63263;
}

   </style>
  </head>
  <body>
    
        <div class="container">
        <h2>YAY! It's BOGO</h2>
        
        <!-- Box 1 -->
             <div class="box expandable">
            <div class="header">
                <input type="radio" name="unit" id="unit1">
                <label for="unit1">1 Unit</label>
                <span class="discount">10% Off</span>
                <span class="price">$10.00 USD</span>
                <span class="old-price">$24.00 USD</span>
            </div>
            <div class="details">
                <div class="option">
                    <label>#1</label>
                    <select>
                        <option>Size</option>
                        <option>S</option>
                        <option>M</option>
                        <option>L</option>
                    </select>
                    <select>
                        <option>Colour</option>
                        <option>Black</option>
                        <option>White</option>
                        <option>Red</option>
                    </select>
                </div>
            </div>
        </div>

        <!-- Box 2 (Expandable) -->
        <div class="box expandable">
            <div class="header">
                <input type="radio" name="unit" id="unit2">
                <label for="unit2">2 Unit</label>
                <span class="discount">20% Off</span>
                <span class="price">$18.00 USD</span>
                <span class="old-price">$24.00 USD</span>
                <span class="most-popular">MOST POPULAR</span>
            </div>
            <div class="details">
                <div class="option">
                    <label>#1</label>
                    <select>
                        <option>Size</option>
                        <option>S</option>
                        <option>M</option>
                        <option>L</option>
                    </select>
                    <select>
                        <option>Colour</option>
                        <option>Black</option>
                        <option>White</option>
                        <option>Red</option>
                    </select>
                </div>
                <div class="option">
                    <label>#2</label>
                    <select>
                        <option>Size</option>
                        <option>S</option>
                        <option>M</option>
                        <option>L</option>
                    </select>
                    <select>
                        <option>Colour</option>
                        <option>Black</option>
                        <option>White</option>
                        <option>Red</option>
                    </select>
                </div>
            </div>
        </div>

        <!-- Box 3 (Expandable) -->
        <div class="box expandable">
            <div class="header">
                <input type="radio" name="unit" id="unit3">
                <label for="unit3">3 Unit</label>
                <span class="discount">30% Off</span>
                <span class="price">$24.00 USD</span>
                <span class="old-price">$24.00 USD</span>
            </div>
            <div class="details">
                <div class="option">
                    <label>#1</label>
                    <select>
                        <option>Size</option>
                        <option>S</option>
                        <option>M</option>
                        <option>L</option>
                    </select>
                    <select>
                        <option>Colour</option>
                        <option>Black</option>
                        <option>White</option>
                        <option>Red</option>
                    </select>
                </div>
                <div class="option">
                    <label>#2</label>
                    <select>
                        <option>Size</option>
                        <option>S</option>
                        <option>M</option>
                        <option>L</option>
                    </select>
                    <select>
                        <option>Colour</option>
                        <option>Black</option>
                        <option>White</option>
                        <option>Red</option>
                    </select>
                </div>
            </div>
        </div>


        <div class="footer">
            <p>Free Delivery</p>
            <p>Total: $18.00 USD</p>
            <button>Add to Cart</button>
        </div>
    </div>
    

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"></script>
 <script>
   document.querySelectorAll('.box.expandable .header').forEach(header => {
    header.addEventListener('click', () => {
        // Close all other boxes
        document.querySelectorAll('.box.expandable .details').forEach(detail => {
            detail.style.display = 'none';
        });
        
        // Toggle the clicked box
        const details = header.nextElementSibling;
        details.style.display = details.style.display === 'none' || details.style.display === '' ? 'block' : 'none';
    });
});

 </script>
  </body>
</html>
