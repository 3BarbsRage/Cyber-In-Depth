These are the instructions for the AI Router Distruption Detector:
1) Run collectData.ipynb
2) Enter your IP Address when prompted
3) Collect data over long period of time (until you have ~5 outages or distruptions of your router)
4) Enter any times you had an outage via Interface.ipynb
5) kill collectData.ipynb
6) run CreateTensor.ipynb
7) run PredictRouterOutage.ipynb, this will provide you with a probability confidence of how confident we are that you have an outage or will soon
