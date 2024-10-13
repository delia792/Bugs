# Bugs 

Below are some Bug samples that I wrote from my experience. 

----------------- 
## Product store doesn’t have a quantity field for products 

**Priority & Severity**

P1 – High 

**Description:** 
When adding multiple units of the same product to the cart, there is no quantity field available. This results in a long list of individual items instead of grouping them under a single product entry with a specified quantity. 

**Steps to reproduce:**
1. Go to https://www.demoblaze.com/index.html;   
2. Log in to the site; 
3. Select any product to view its details; 
4. Check if there is an option to input the quantity of the product before adding it to the cart; 
5. Add the same product several times; 
6. Press the ,,Cart” button; 
7. Look at the cart.

**Expected result:**

A quantity field should be available on the product page to allow users to specify how many units of a product they want to purchase. 

**Actual result:**

No quantity field is present on the product page. Users can only add a single unit multiple times and result is a long list of individual items. 

### Bug Image 

![bug sample](htt![Screenshot 2024-10-12 192540](https://github.com/user-attachments/assets/3f1734f3-0054-453a-93a7-6f775a974b53)
ps://imgur.com/a/fDKZjyI) 

----------------- 

## Incorrect Video in "About Us" Section on Demoblaze Store  

**Priority & Severity**

P4 – Low  

**Description:** 
The video displayed in the "About Us" section does not provide information about the store. Instead, it features content related to an IT course.  

**Steps to reproduce:**
1. Go to https://www.demoblaze.com/index.html;   
2. Navigate to the "About Us" section; 
3. Play the video. 

**Expected result:**

The video should introduce or describe the store and its offerings. 

**Actual result:** 

The video shows content about an IT course, unrelated to the store. 

----------------- 

## 404 page not found on https://www.primariatechirghiol.ro/ 

**Priority & Severity**

P3 – Low  

**Description:** 
When you press on link https://www.primariatechirghiol.ro/formulare/arhitect-ef an 404 error occurs, a new page opens with message Error 404 - Not Found. 

**Steps to reproduce:**
1. Go to https://www.primariatechirghiol.ro/formulare 
2. From drop down choose “Arhitect șef”  

**Expected result:**

When you press on “Arhitect șef” from https://www.primariatechirghiol.ro/formulare (https://www.primariatechirghiol.ro/formulare/arhitect-ef) a new page should open with more information.  

**Actual result:** 

When you press on “Arhitect șef” from https://www.primariatechirghiol.ro/formulare (https://www.primariatechirghiol.ro/formulare/arhitect-ef)  a new page opens with message Error 404 - Not Found. 

----------------- 
## Image is not loading 

**Priority & Severity**

P5 – Low  

**Description:** 
When you open the page, first picture located in the upper right corner is not loading. 

**Steps to reproduce:**
1. Go to https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/  
2. Picture located in the upper right corner is not loading.  

**Expected result:**

On you go on  https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/ one photo must be displayed in the upper right corner. 

**Actual result:** 

On you go on  https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/ the photo in the upper right corner is not displayed. 


### Bug Image 

![bug sample](https://github.com/delia792/images/blob/main/Screenshot%202024-10-12%20201452.png?raw=true) 

----------------- 
## "Forgot password" option doesn't exist 

**Priority & Severity**

P1 – High   

**Description:** 
When you try to login in user account and you forgot your username and/or your password, you don’t have the option to reset it using Forgot password link.  

**Steps to reproduce:**
1. Go to https://www.demoblaze.com; 
2. Press on “Log in” button;
3. Try to login with wrong username and/or password;
4. User doesn’t have the option to change username and/or password in order to login. 

**Expected result:**

On the login page there should be a link with “Forgot password”.  

**Actual result:** 

On the login page is not a link with “Forgot password”. 

**Test data:** 

username - deliamarinapavel@yahoo.com

password - parola 

### Bug Image 

![bug sample](https://github.com/delia792/images/blob/main/Screenshot%202024-10-12%20203705.png?raw=true)

![bug sample](https://github.com/delia792/images/blob/main/Screenshot%202024-10-12%20203729.png?raw=true) 

