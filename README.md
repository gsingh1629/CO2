# CO2 Emission Predictor

An online CO2 emission predictor based on the size of the engine

## LINK

```bash
https://co2pred.herokuapp.com/
```

## Usage

User enters the size of engine and predict the emission from that engine

## Deploying it on HEROKU

* First make a requirements.txt file in your project folder
* This can be done using pip freeze(but it will list out all the libraries installed in your environment
* So we can also user pipreqs(this will only list the libraries need for your current app) 
```bash
install pipreqs
pipreqs .
```
* Now we have a requirements.txt file of our project we need to add a Procfile(only need for heroku)
* After that we need make a github repository of our project with all these files
* Then, on heroku make a new app and link that with github and just deploy.
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
