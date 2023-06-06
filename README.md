# Binance BTC-USDT Data Visualization Dashboard

This project is a real-time data visualization dashboard for the BTC-USDT spot price from Binance. The dashboard is built with Python, using the Dash and Plotly libraries for the web interface and data visualization. 

The dashboard shows the following calculated metrics:

- 24hr volume
- 24hr price change (%)
- 24hr volatility
- Market cap

## Live Application

The live application is hosted on Google Cloud Platform and can be accessed at the following URL:

[https://console.cloud.google.com/apis/library/browse?authuser=1&project=dynamic-density-389023&supportedpurview=project](https://console.cloud.google.com/apis/library/browse?authuser=1&project=dynamic-density-389023&supportedpurview=project)

The application updates the price data every second and maintains a 24-hour history.

## Uptime Monitoring

Uptime monitoring for the application is provided by UptimeRobot. The status of the application can be viewed at the following URL:

[https://uptimerobot.com/dashboard#794508255](https://uptimerobot.com/dashboard#794508255)

UptimeRobot checks the status of the application every 5 minutes.

## Local Development

To run this project locally, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies using pip:

    ```
    pip install -r requirements.txt
    ```

3. Run the main.py script:

    ```
    python main.py
    ```

This will start a local server and the application can be accessed in a web browser.

## Deployment

The application is deployed to Google Cloud Platform's App Engine.



