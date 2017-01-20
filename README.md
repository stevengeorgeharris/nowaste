#### NoWaste API

The NoWaste API is a microservice built in Go and containerised with Docker.

**To start we assume:**
- You have docker-cli installed
- You have cloned the project into your `$GOPATH`

**To run:**
- `docker-compose build`
- `docker-compose up -d` 
- Visit `http://localhost:3000/businesses`

**TODO::**

- [ ] Implement persistent data (Mongo/Redis)
- [ ] Add user/business type schema
- [ ] Add routes
- [ ] Authentication
