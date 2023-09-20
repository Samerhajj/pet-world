# Frontend Pet World

### Home

<img src="Img/Home Page.png" width="300"/>

### Login

<img src="Img/Login Page.png" width="300" />

### About Us

<img src="Img/About page.png" width="300" />

---

# Backend Pet World

#### Our Collection :

- users
- store_items
- receipt

---

### Create New Item Request

### [ Post ] http://localhost:8081/api/v1/item

```
{
  "id": "1234501",                  // A unique identifier for the item
  "itemName": "Sample Item",       // Name of the item
  "itemDescription": "Description of the item goes here.", // Description
  "feedback": 4.5,                // Feedback rating out of 5
  "imageLink": "https://picsum.photos/200/300" // Link to the item's image
}

```
