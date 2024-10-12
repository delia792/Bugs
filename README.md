# Bugs 

Below are some Bug samples that I wrote from my experience. 

----------------- 
## Product store doesn’t have a quantity field for products 

**Priority & Severity**

P1 – High 

**Description** 
When adding multiple units of the same product to the cart, there is no quantity field available. This results in a long list of individual items instead of grouping them under a single product entry with a specified quantity. 

**Steps to reproduce**
1. Go to https://www.demoblaze.com/index.html;   
2. Log in to the site; 
3. Select any product to view its details; 
4. Check if there is an option to input the quantity of the product before adding it to the cart; 
5. Add the same product several times; 
6. Press the ,,Cart” button; 
7. Look at the cart.

**Expected result**

A quantity field should be available on the product page to allow users to specify how many units of a product they want to purchase. 

**Actual result**

No quantity field is present on the product page. Users can only add a single unit multiple times and result is a long list of individual items. 

### Bug Image 

![bug sample] (https://github.com/delia792/images/blob/main/Screenshot%202024-10-12%20192540.png) 
