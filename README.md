# fresh_mall_online
Vue+Django REST framework Project 

1. Vue - Frontend
  * **API Interface**
  * **Vue components**
  * **Structure**
2. **Django rest framework** **(Core)**
  * Restful API development
    * **ApiView - API**
    * **GenericView - API Interface**
    * **Viewset & Router - API & url configs**
    * **Django_filter, SearchFilter, OrderFilter, Paging**
    * **Mixins(General)**
  * Permissions & Authentication 
    * Authentication config for users
    * **Dynamic permission, Authentication**
    * **Validators** for Strings' validation
  * Serialization & Form Validation
    * Serializer
    * ModelSerializer
    * Dynamic serializer
  * Payment, Login, Register
    * json web token -- Login
    * Registeration via Mobile
    * Alipay 
    * Third-party Login
  * Advanced Developemnt
    * Django rest framework Core Souce Code Review
    * Documentation - Automatic management
    * Cache for Django rest framework
    * Throttling for limited speed for Users/IPs
3. xadmin - backend admin system

4. Common issues
  * Bugs which cannot be refound in localhost
  * Bugs in API Interface -- Hard to locate
  * API Documentation Management Issues
  * Large amount of urls -- Hard to maintain
  * Did not update the doc immediately -- Trouble for testing APIs
  * Anti-Crawler -- Limitation for API's visiting frequency: 1min/1h/1d
  * Cache for API speeding -- Categories for products(slight shift)
5. Solutions to common issues
  * PyCharm - debugging for remote server
    * Payment
    * Third-party login
    * Recur bugs in the remote server on local machine
  * Docker -- Build sentry for surveillance of error's logging 
    * Tech stack - Bugs
    * Email Notification -- Timely
  * Django rest framework -- automatic management
    * url - registeration management 
    * time-saving for documentation
    * Built-in testing interface in documentation
    * Auto-generated JS Interface Script
    * Shell Script for Testing
    * Python Script for Testing
  * Django rest framework -- Throttle 
    * Limitation for APIs' Visiting frequency
  * Third-party Framework 
    * Cache issues - Speed up
6. Advanced Django
  * Django migrations - Principles
  * Django Signal
  * Whole process -- **request - response**
  * Model for independent use
7. Vue Basics
  * Tech Stack Analysis
    * pros & cons
  * APIs' data to be filled in Vue components
  * Code review for Vue's Structure
  
## Arrangements
* **Chapter 1 & 2: Environemnts for dev**
* **Chapter 3: Database Design & Raw Data Insertion**
* **Chapter 4: restful API basics & Intro for Vue project**
* **Chapter 5: Products' forms**
* **Chapter 6: Products' categories' View**
* **Chapter 7: Mobile Register & Login**
* **Chapter 8: Product's detail' View & Favoriates' View**
* **Chapter 9: User center View**
* **Chapter 10: Shopping cart & Orders & Alipay Views**
* **Chapter 11: Home & Stock & Cache & Speed limitation**
* **Chapter 12: Third-party login: QQ, Weibo, WeChat**
* **Chapter 13: Sentry system for errors' surveillance**

## Requirements
* Django Basics
* Python 
* Vue Basics
* MySQL



  
  

  
