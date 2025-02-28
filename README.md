

---

# 🛒 Product Gallery - React App  

This is a **React-based Product Gallery** application that allows users to **view, add, edit, and delete products** dynamically. The app features a **search bar, product cards, and an edit modal** for seamless interaction.

---

## 🚀 Features  

✅ **View Products** - Displays a grid of products with images, names, descriptions, and prices.  
✅ **Add New Product** - Users can add a product by clicking "Add Product," which opens input fields dynamically.  
✅ **Edit Product** - Modify product details using the edit modal.  
✅ **Delete Product** - Remove unwanted products from the list.  
✅ **Search Products** - Filter products based on name.  
✅ **Responsive UI** - Works on different screen sizes.  

---

## 🛠️ Tech Stack  

- **React.js** - Frontend framework  
- **CSS** - For styling  
- **useState Hook** - For managing component state  

---

## 📂 Project Structure & File Descriptions  

```
product-gallery/
│-- src/
│   │-- components/
│   │   │-- ProductGallery.js    # Main component managing product list
│   │   │-- ProductCard.js       # Displays individual product details
│   │   │-- EditModal.js         # Modal for editing product details
│   │-- assets/
│   │   │-- images/              # Folder containing product images
│   │-- styles/
│   │   │-- styles.css           # Styling for the app
│   │-- App.js                   # Main React component
│   │-- index.js                 # Entry point of the React app
│-- public/
│   │-- index.html               # Root HTML file of the app
│-- package.json                 # Dependencies and scripts
│-- README.md                    # Project documentation
```

---

### **1️⃣ ProductGallery.js (Main Component)**  
📍 **Location:** `src/components/ProductGallery.js`  
📌 **Purpose:** This is the core component that manages the entire product gallery. It maintains the product list and handles adding, editing, deleting, and searching products.  

#### 🔹 Key Functionalities:  
- ✅ Displays a **3×3 grid** layout of products.  
- ✅ Includes an **"Add Product"** button that reveals input fields dynamically.  
- ✅ Implements a **Search bar** to filter products by name.  
- ✅ Opens the **Edit Modal** when clicking on a product.  
- ✅ Deletes a product when the delete button is clicked.  

---

### **2️⃣ ProductCard.js (Product Display Component)**  
📍 **Location:** `src/components/ProductCard.js`  
📌 **Purpose:** Represents a single product in the gallery.  

#### 🔹 Key Functionalities:  
- ✅ Displays **product image, name, description, and price**.  
- ✅ Clicking the **image** opens the edit modal.  
- ✅ Clicking the **delete button** removes the product from the list.  

#### 🔹 Props Passed to This Component:  
- `product` → Contains product details (name, description, price, image).  
- `onEdit` → Function to trigger edit mode.  
- `onDelete` → Function to delete the product.  

---

### **3️⃣ EditModal.js (Edit Product Modal)**  
📍 **Location:** `src/components/EditModal.js`  
📌 **Purpose:** A pop-up modal that allows users to edit product details.  

#### 🔹 Key Functionalities:  
- ✅ Users can modify **name, description, price, and image URL**.  
- ✅ Clicking **Save** updates the product details in the main gallery.  
- ✅ Clicking **Cancel** closes the modal without saving.  

#### 🔹 Props Passed to This Component:  
- `product` → The product being edited.  
- `setProduct` → Function to update product details.  
- `updateProduct` → Function to save the updated product.  

---

### **4️⃣ styles.css (Styling File)**  
📍 **Location:** `src/styles/styles.css`  
📌 **Purpose:** Defines the styles for the entire application, ensuring a clean and responsive UI.  

#### 🔹 Key Styling Elements:  
- ✅ **Grid Layout:** Defines a `3×3` responsive grid for product display.  
- ✅ **Buttons & Input Fields:** Styled buttons for add, edit, delete, and search.  
- ✅ **Modal Styling:** Ensures the edit modal appears centered and properly formatted.  

---

### **5️⃣ App.js (Main Application Component)**  
📍 **Location:** `src/App.js`  
📌 **Purpose:** Serves as the root component that renders the **ProductGallery**.  

#### 🔹 Key Functionalities:  
- ✅ Imports and renders the **ProductGallery** component.  
- ✅ Wraps everything within a `div` for structure.  

---

### **6️⃣ index.js (Entry Point)**  
📍 **Location:** `src/index.js`  
📌 **Purpose:** The entry point of the React application, responsible for rendering `App.js` inside **root div** of `index.html`.  

#### 🔹 Key Functionalities:  
- ✅ Imports `React` and `ReactDOM` to render the app.  
- ✅ Renders `<App />` inside `<div id="root">`.  

---

### **7️⃣ public/index.html (Main HTML File)**  
📍 **Location:** `public/index.html`  
📌 **Purpose:** The HTML file where the React app is injected.  

#### 🔹 Key Elements:  
- ✅ **Root `<div id="root">`** - React components are rendered inside this div.  
- ✅ Standard HTML boilerplate with a `<title>` tag for the project name.  

---

### **8️⃣ package.json (Project Configuration)**  
📍 **Location:** `package.json`  
📌 **Purpose:** Lists dependencies and scripts required to run the project.  

#### 🔹 Key Dependencies:  
- ✅ **React** - Core framework for building UI components.  
- ✅ **React-DOM** - For rendering components in the browser.  

#### 🔹 Scripts:  
```sh
npm start    # Runs the project in development mode
npm install  # Installs dependencies
```

---

## 🔧 Installation & Setup  

Follow these steps to run the project locally:  

### 1️⃣ **Clone the Repository**  
```sh
git clone https://github.com/Jheel11/product-gallery.git
cd product-gallery
```

### 2️⃣ **Install Dependencies**  
```sh
npm install
```

### 3️⃣ **Start the Development Server**  
```sh
npm start
```
Then open **[http://localhost:3000/](http://localhost:3000/)** in your browser.  

---

## 🛠️ How to Use?  
1️⃣ **View Products** - Browse products in a **grid layout**.  
2️⃣ **Search Product** - Type the name in the search bar to filter products.  
3️⃣ **Add Product** - Click **"Add Product,"** enter details, and add a new product.  
4️⃣ **Edit Product** - Click on a **product image** to modify details.  
5️⃣ **Delete Product** - Click the **delete button** to remove a product.  

---

## 📜 License  
This project is **open-source** and available under the **MIT License**.  

---


---

## 👨‍💻 Developed by **Jheel11**  
🔗 **GitHub:** [https://github.com/Jheel11](https://github.com/Jheel11)  

---

