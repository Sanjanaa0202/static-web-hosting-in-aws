# 📚 BookNest – Online Book Store (Frontend + AWS Deployment)

## 🚀 Project Overview

BookNest is a responsive web application designed for browsing and managing books. It provides users with an intuitive interface to explore books, manage cart and wishlist, and simulate an online bookstore experience.

This project is deployed using AWS services to ensure scalability, performance, and security.


## 🌐 Live Demo

🔗 https://d2w2gnbpk6a731.cloudfront.net


## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript

### Cloud & Deployment

* AWS S3 (Static Website Hosting)
* AWS CloudFront (Content Delivery Network)
* Origin Access Control (OAC) for secure access


## ✨ Features

* 📖 Browse books collection
* 🛒 Add to cart interface
* ❤️ Wishlist functionality
* 🔐 Sign In / Sign Up UI
* 📱 Fully responsive design


## 🔒 Security Implementation

* Configured **Origin Access Control (OAC)** to restrict direct access to S3
* Applied secure **bucket policy** allowing access only through CloudFront
* Prevented public exposure of static assets


## 🧩 Challenges Faced

* Encountered **Access Denied** error during deployment
* Resolved by:

  * Correctly configuring bucket policy
  * Attaching CloudFront OAC
  * Setting proper permissions and origin settings


## 📂 Project Structure

```
BookNest/
│── index.css
│── index.html
│── books.css
│── books.html
│── cart.css
│── cart.html
│── wishlist.css
│── wishlist.html
│── signin.css
│── signin.html
│── signup.css
│── signup.html
│── images/
```


## 🚀 Deployment Steps

1. Created an S3 bucket and uploaded static files
2. Configured CloudFront distribution
3. Attached Origin Access Control (OAC)
4. Updated bucket policy for secure access
5. Set default root object as `index.html`
6. Deployed and tested the application


## 🔮 Future Enhancements

* Backend integration (Node.js / Express)
* Database (MongoDB) for user & cart data
* Authentication system
* Payment gateway integration


## ⭐ Acknowledgment

This project was developed as part of hands-on learning in web development and cloud deployment using AWS.
