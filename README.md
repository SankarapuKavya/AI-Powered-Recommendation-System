# AI-Powered Restaurant Recommendation System

A Django-based web application that provides personalized restaurant and dish recommendations using AI, complete with search, cart, and checkout functionality.

---

## 🌟 Features

- **Search Restaurants & Dishes**: Search by restaurant name, cuisine, location, or dish name.  
- **AI Recommendations**: Personalized dish and restaurant recommendations based on user preferences using a hybrid recommendation algorithm.  
- **Cart & Checkout**: Add dishes to the cart, adjust quantity, and checkout using UPI (GPay, Paytm, PhonePe) or Cash on Delivery.  
- **Order History**: Users can view past orders and order details.  
- **Offers & Discounts**: Display active restaurant and dish offers.  
- **Responsive UI**: Cards and images aligned nicely on all screen sizes.  
- **Authentication**: Login/logout functionality and session management.  

---

## 🛠️ Technologies Used

- **Backend**: Django, Python  
- **Frontend**: HTML, CSS   
- **Database**: SQLite   
- **AI**: Hybrid recommendation algorithm for personalized suggestions  
- **Payment Integration**: UPI (GPay, Paytm, PhonePe) & COD  

---

## 📁 Project Structure

---

``` text AI_Restaurant_Recommender/ ├── config/ │   ├── init.py │   ├── asgi.py │   ├── settings.py │   ├── urls.py │   └── wsgi.py ├── media/ │   ├── dish_images/ │   └── restaurant_images/ ├── restaurants/ │   ├── init.py │   ├── admin.py │   ├── api_views.py │   ├── apps.py │   ├── models.py │   ├── recommendation.py │   ├── serializers.py │   ├── tests.py │   ├── urls.py │   ├── utils.py │   └── views.py ├── static/ ├── templates/ │   ├── base.html │   ├── cart.html │   ├── checkout.html │   ├── dashboard.html │   ├── dish_detail.html │   ├── home.html │   ├── login.html │   ├── paytm_redirect.html │   ├── restaurant_detail.html │   └── upi_redirect.html ├── db.sqlite3 ├── manage.py ├── README.md └── requirements.txt ```               

## ⚙️ Setup Instructions

1. Clone the repo:
   ```bash
   git clone https://github.com/<SankarapuKavya>/AI-Powered-Recommendation-System.git
   cd ai_restaurant_recommender

2. Creating a virtual environment:
    ```bash
   python -m venv venv
   source venv/bin/activate

3. Install Dependencies:
    ```bash
    pip install -r requirements.txt
    
4. Apply migrations:
    ```bash
    python manage.py makemigrations
    
5. Run the development server:
    ```bash
    python manage.py runserver
6. Open http://127.0.0.1:8000/ in your browser.
  
