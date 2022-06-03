#### [Here](https://cdss-ml-portfolio.herokuapp.com/chatbot) is the model in production

##### How to use
This project was not trained in anything but the BERT. So, if you want to test it you first must make your own training data. 

The training data must follow the rules:

1.  Must be a JSON
2.  Should have props with the name of the intent to predict. 
3.  Each intent should have two arrays. "phrases" and "responses".

```json
{
  "welcome":{
    "phrases":[
        "Hello, how are you doing ?",
        "Hi"
      ],
    "responses":[
        "Hello I'm a intent based bot"
    ]
  },
  "departure":{
    "phrases":[
        "Bye",
        "see you later"
      ],
    "responses":[
        "bye bye"
    ]
  }
}
```
