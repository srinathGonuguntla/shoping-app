In this project, the main objective is to display products based on their categories. The products are stored in an array, and each product has properties like id, title, price, compare-at-price, vendor, image, and badge-text.
The categories are also stored in an array, and each category has a category-name and category-products.

The showProducts function filters the products based on the selected category and adds the relevant products to the category container. This function loops through the products array and finds the products that belong to the selected category.
Then, it loops through these products and creates a product card for each one using the createProductCard function. Finally, it appends these product cards to the category container.

The onCategorySelect function is called when the user selects a category from the dropdown. This function gets the selected category and calls the showProducts function with the selected category as the argument.

The createCategoryDropdown function creates the dropdown menu with the categories as options. It adds an event listener to the dropdown so that the onCategorySelect function is called when the user selects a category.

The initialize function sets up the dropdown and calls the showProducts function with the default category as the argument. It appends the dropdown to the body of the HTML document and then calls the showProducts function with the default category.

The product cards are created using a template literal in the createProductCard function. The template literal includes placeholders for the product properties, and these placeholders are replaced with the actual product properties when the product card is created.
