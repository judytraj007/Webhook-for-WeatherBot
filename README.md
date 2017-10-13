# Webhook for WeatherBot
A python webapp using Flask, that will receive POST request from one of Google's DialogFlow(api.ai) agents i.e chatbots for intent fulfillment, extract the parametrs passed in through the incoming JSON, query OpenWeatherMap API for weather forecast and returns the result back to the agent. 
Uses OpenWeatherMap API to find the weather forecast at a specified location for a specified date.
