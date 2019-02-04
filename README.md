## Politico
Its a platform that enables citizens to give their mandate to politicians running for different government offices while building trust in the process through transparency.

### Summary

#### Endpoints

| Task | Endpoint |
|---|---|
| Create a political party | `POST /parties`|
| Get specific political party | `GET /parties/<party-id>` |
| Get all political parties | `GET /parties/` |
| Update specific party | `PATCH /parties/<party-id>/name` |
| Delete a specific political party | `DELETE /parties/<party-id>` |
| Create a political office | `POST /offices` |
| Fetch all political offices records | `GET /offices` |
| Fetch a specific political office record | `GET /offices/<office-id>` |

### Testing
#### Manual
- `$ git clone https://github.com/Alphaomen/Politico.git`
- `$ cd Politico`
- `$ virtualenv env`
- `$ source .env`
- `$ flask run`

#### Pytest
- `$ git clone https://github.com/Alphaomen/Politico.git`
- `$ cd Politico`
- `$ virtualenv env`
- `$ source .env`
- `$ cd app/test/`
- `$ pytests`

### Author
Michael Nthiwa