<!-- TODOS: -->

### users can sign up with email/password
POST /auth/signup (body: email, password)
POST /auth/signin (body: email, password)

USERS CONTROLLER, USERS SERVICE, USERS REPOSITORY

<!-- break -->

### users get an estimate for how much their car is worth based on the make/model/year/mileage
GET /reports (QS: make, model, year, mileage, longitude, latitude)

### users can report what they sold their vehicles for
POST /reports (body: make, model, year, mileage, longitude, latitude, price)

### Admins have to approve reported sale
PATCH /reports/:id (body: approved)

REPORTS CONTROLLER, REPORTS SERVICE, REPORTS REPOSITORY# nest-carprice-app-learning
