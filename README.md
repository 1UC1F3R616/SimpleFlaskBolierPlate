# SimpleFlaskBolierPlate
- This is minimal Flask BolierPlate that you can use for building RestAPIs
- No Relative Import Error
- No Circular Import Error
- You can add Sockets also
- Register your extra BluePrints with app
- You can host it on Heroku by following Below Steps

```bash
heroku create AppName1
git push heroku master
heroku addons:create heroku-postgresql:hobby-dev
heroku run python # setting up database
from app import * # app is folder inside which I have my models, routes, api, sockets in a systematic format :: Target is-to import db
db.create_all() # Don't worry that you haven't written any PostgreSQL code, it's all done | details in mind, lol
exit()
```

## Test App Hosted [Here](https://simpleflaskapp98.herokuapp.com/)
- Check DB by using below Endpoint
```txt
https://simpleflaskapp98.herokuapp.com/auth/user/registration
```
- with below json body
```json
{
	"username":"Kush",
	"password": "123456"
}
```

## Help Docs
- [Heroku Host](https://gist.github.com/1UC1F3R616/3bd89fb9f058c619e49e6ebfba41d83e)
- [Flask Tips](https://gist.github.com/1UC1F3R616/33c3d44536ff75ee2ad5974890b0f61e)
- [PostgreSQL](https://gist.github.com/1UC1F3R616/b669f1bd14f08588480f708a51396312)

## Other Availbale BoilerPlates
- Django based Layout for Flask
- Separate Model with BluePrints along with Static and Templates

````````````````````
- I hate python import (Pun Intended)
````````````````````
