# Sprint_App

**Shopping Mobile Application** built with **Flutter** and **Dart**, developed as part of the **Sprints Assessment Final Project**.  


## 📖 Project Overview

This project demonstrates the full lifecycle of mobile app development with Flutter — from Dart fundamentals to advanced UI, navigation, and localization.  

The app includes:
- beautiful splash screen with an animated transaction for next screen (welcome screen)
- **welcome screen** with local and online images, styled text, and navigation buttons.  
- **Sign Up / Sign In** forms with validation and success dialogs.  
- **Smooth animated transitions** between pages.  
- A **Shopping Home Screen** with featured products, a responsive product grid, and hot offers.  
- **SnackBar feedback** for cart actions.  

This project is designed to simulate real-world mobile development workflows, emphasising **clean code**, **reusability**, and **best practices**.

## 🛠 Packages Used

- **animated_splash_screen** → start of the app with animated transaction for next screen
- **lottie** → that give animated icons and beautiful icons 
- **email_validator** → Email validator doesn't only check for the presense of '@' in email string but also it makes sure that email is in the standard format: 'string@string.string'   
- **smooth_page_indicator** → Used it in home screen to apply page indicators just like sample UI provided.


## 📱 Features

### 1. splash Screen  
- that contains animated icon for the logo of the app 
- contains name of the app and the loading icons give a beautiful transaction for next screen after specific time.  
   
---

### 2. Welcome Screen  
- AppBar with custom font (**Suwannaphum-Regular**).  
- Two images: one **local** and one **online** (retrieved from picsum).  
- Styled, centred text with bold and colour.  
- Buttons: **Sign Up** and **Sign In**.  

---

### 3. User Authentication  
#### Sign-Up Form:  
- Fields: Full Name (each name must be capitalised), Email (validated by **email_validator**), Password (≥6 chars), Confirm Password (match required).  
- Success: CupertinoDialog → “Account created successfully”.  

#### Sign-In Form:  
- Fields: Email & Password validation.  
- Success: CupertinoDialog → “Account sign-in successfully”.  

---

### 4. Smooth Transitions  
- Fade animation between Sign-Up/Sign-In and Home screen.  

---

### 5. Shopping Home Screen  
- AppBar: **Our Products**.  
- Horizontal **PageView**: Featured products.  
- Responsive **GridView**: Product cards with:  
  - Image  
  - Title  
  - Add to Cart (SnackBar confirmation).  
- **Hot Offers** section:  
  - Vertical scroll with `ListView.builder`.  
  - Image + description in each item.  

---
