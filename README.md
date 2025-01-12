# **sTock-seisMo**
*A custom stock market watchlist application designed to keep you informed and updated with the latest stock data and market news!*

---

## **Contact Information**
For any help, suggestions, or support, feel free to reach out to me !!

---

## **Technologies Used**

### **Backend Frameworks & Libraries**
- **Flask**: A lightweight web framework for building and serving the web application.
- **Flask-SQLAlchemy**: An ORM tool for managing the database with SQLite, enabling efficient data storage and retrieval.

### **Stock Market Data**
- **Yahoo Finance (yfinance)**: A powerful library for fetching real-time stock market data, including prices, charts, and historical data.

### **Notifications**
- **Twilio**: API integration for sending SMS notifications to users about important stock updates and news.

### **Web Scraping & Parsing**
- **Selenium**: For scraping dynamic web content from news websites, ensuring up-to-date stock market insights.
- **BeautifulSoup**: For parsing HTML pages and extracting relevant news data for users.

### **Utilities & Enhancements**
- **FuzzyWuzzy**: A string matching library to accurately identify and search for stock tickers.
- **Threading**: Enables background tasks for periodically checking and updating news without interrupting the user experience.
- **Requests**: For seamless HTTP requests to APIs and web pages.
- **WebDriverWait**: From Selenium, ensuring smooth handling of asynchronous loading of web content.
- **JSON**: Utilized for efficient data interchange and storing stock ticker information.

---

## **Features**

### 1. **Real-Time Stock Monitoring**
- Monitor stock prices and access current market data for your favorite stocks.
- Get real-time updates to make informed investment decisions.

### 2. **SMS Notifications**
- Stay ahead with instant SMS notifications about the latest stock market news.
- Never miss out on crucial updates.

### 3. **User-Friendly Web Interface**
- A clean and intuitive web interface for users to manage their custom stock watchlists.
- Easily search, add, and monitor stocks from a single dashboard.

### 4. **News Updates**
- Automatically fetch and display relevant stock market news, ensuring you stay informed about market trends and events.

### 5. **Background Updates**
- Efficient use of threading to periodically check for updates without disrupting the user experience.

---

## **How to Get Started?**

### 1. **Clone the Repository**
```bash
git clone https://github.com/your-repo/sTock-seisMo.git
cd sTock-seisMo

```

### 2. **Set Up the Environment**
- Install Python (3.7 or higher).
- Install dependencies using `pip`:
```bash
pip install -r requirements.txt
```
### 3. **Configure Twilio**
- Sign up on [Twilio](https://www.twilio.com/) to get your API keys.
- Add your Twilio credentials to the `.env` file. Example `.env` structure:
```bash
TWILIO_ACCOUNT_SID=your_account_sid
TWILIO_AUTH_TOKEN=your_auth_token
TWILIO_PHONE_NUMBER=your_twilio_phone_number
```
### 4. **Run the Application**
- Start the Flask server:
```bash
flask run
```
- Open your browser and navigate to:  
`http://127.0.0.1:5000`
- Enjoy Real-Time Stock Updates :)

  ![image](https://github.com/user-attachments/assets/4bd0cc85-a3de-4e30-b06c-8a1894c03613)

