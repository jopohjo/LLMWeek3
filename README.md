Technical Assignment: Sentiment Analysis System with Custom Fine-Tuned Model and Llama 3 Models

Code is based on Google Colad.

You need groq and ngronk token to run this code. 

FastAPI create API endpoint to test model and I use ngrok to publish my API endpointi. After that you can request API from public network. 

Once the API is running, you can test it with Postman, for example.

```
POST https://xxxxxxxx.ngrok-free.app/analyze/
{
    "text": "This movie was fantastic!",
    "model": "custom"
}

RETURN
{
    "sentiment": "LABEL_1",
    "confidence": 0.9962
}

```
