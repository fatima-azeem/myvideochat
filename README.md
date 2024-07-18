# Video Calling App with Django and Agora Web SDK
This project is a video calling application built using Django as the backend framework and the Agora Web SDK for real-time video communication. The app enables users to make one-on-one video calls and engage in real-time communication.


##Features
- One-on-one video calling
- Real-time video and audio communication
- User authentication and authorization using Django's built-in auth system
- Token-based authentication for video calls
- Integration with Agora Web SDK for video calling functionality

  
##Technical Requirements
- Django 4.1+
- Python 3.8+
- Agora Web SDK 4.3+
- WebRTC compatible browser (Google Chrome, Mozilla Firefox, etc.)

  
##Setup and Installation
1. Clone the repository:
 ```python
git clone https://github.com/fatima-azeem/myvideochat
```
2. Install dependencies:
 ```python
 pip install -r requirements.txt
 ```
3. Configure Agora Web SDK credentials in `views.py` and `streams.js`.
4. Run the application:
 ```python
 python manage.py runserver
```


##Agora Web SDK Integration

The Agora Web SDK is integrated into the Django app using the following steps:

1. Import the Agora Web SDK JavaScript library in the HTML template
2. Initialize the Agora client with the App ID and Token
3. Use the Agora API to join and leave video calls


##Django Backend

The Django backend handles user authentication, authorization, and token generation for video calls. The backend also provides RESTful APIs for:

- User registration and login
- Token generation for video calls
- Video call setup and teardown


