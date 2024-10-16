## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/kaushiktak19/productAPI
   cd productAPI

2. **Install dependencies**:
    ```bash
    npm install
    
    ```
3. **Run the application**:
    In the root directory, start both the backend and frontend:
    ```bash
    node server.js

    ```
    The server will start running on http://localhost:8000

## Testing via Postman

1. Send POST request for http://localhost:8000/api/products/value .

2. This endpoint accepts a JSON object containing an array of product objects. Each product object should include the following fields:

name (string): The name of the product
price (number): The price of the product
quality (number): The quality rating of the product

```bash 
{
    "products": [
        { "name": "Product A", "price": 10, "quality": 2 },
        { "name": "Product B", "price": 15, "quality": 1 },
        { "name": "Product C", "price": 5, "quality": 3 }
    ]
}

```
On successful request, response shall be - 

```bash 
{
    "totalValue": 65
}

```

