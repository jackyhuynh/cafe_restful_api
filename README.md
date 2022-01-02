# TEMPLATE for PYTHON Developer using PYCHARM

## Introduction
- RESTFUL API that store the coffees shop in London.

## All response will have the form
```json
      {
      "can_take_calls": false,
      "coffee_price": "£2.80",
      "has_sockets": true,
      "has_toilet": false,
      "has_wifi": true,
      "id": 20,
      "img_url": "https://lh3.googleusercontent.com/p/AF1QipNlBWFgXBiP9YjKARy4dgjHGePOmtsfuQPRwGvb=s0",
      "location": "Shoreditch",
      "map_url": "https://goo.gl/maps/gYX271NxyuawiMcK8",
      "name": "The Bike Shed",
      "seats": "10-20"
    }
```
### List all cafes:
`GET /all`
**Response**
- `200 OK` on success
```json
[
  {
      "can_take_calls": false,
      "coffee_price": "£2.80",
      "has_sockets": true,
      "has_toilet": false,
      "has_wifi": true,
      "id": 1,
      "img_url": "https://lh3.googleusercontent.com/p/AF1QipNlBWFgXBiP9YjKARy4dgjHGePOmtsfuQPRwGvb=s0",
      "location": "Shoreditch",
      "map_url": "https://goo.gl/maps/gYX271NxyuawiMcK8",
      "name": "The Bike Shed",
      "seats": "10-20"
    },
  {
      "can_take_calls": false,
      "coffee_price": "£2.80",
      "has_sockets": true,
      "has_toilet": false,
      "has_wifi": true,
      "id": 20,
      "img_url": "https://lh3.googleusercontent.com/p/AF1QipNlBWFgXBiP9YjKARy4dgjHGePOmtsfuQPRwGvb=s0",
      "location": "Shoreditch",
      "map_url": "https://goo.gl/maps/gYX271NxyuawiMcK8",
      "name": "The Bike Shed",
      "seats": "10-20"
    }
]
```
- Get all the coffee shops in the database

### Find a cafe bas on location:
`GET /search?loc=Shoreditch`
**Response**
- `200 OK` on success
- Get the coffee shop base on location
```json
  {
      "can_take_calls": false,
      "coffee_price": "£2.80",
      "has_sockets": true,
      "has_toilet": false,
      "has_wifi": true,
      "id": 20,
      "img_url": "https://lh3.googleusercontent.com/p/AF1QipNlBWFgXBiP9YjKARy4dgjHGePOmtsfuQPRwGvb=s0",
      "location": "Shoreditch",
      "map_url": "https://goo.gl/maps/gYX271NxyuawiMcK8",
      "name": "The Bike Shed",
      "seats": "10-20"
    }
```
### Add a new coffee shop:
`POST /add`
- Using postman and add 
## Technology
List of technology
- Python
- PyCharm IDE

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
What things you need to install the software and how to install them
- PyCharm Community IDE: Be More Productive: Save time while PyCharm takes care of the routine. Focus on the bigger things and embrace the keyboard-centric approach to get the most of PyCharm's many productivity features. Get Smart Assistance: PyCharm knows everything about your code. Rely on it for intelligent code completion, on-the-fly error checking and quick-fixes, easy project navigation, and much more.


### Installing
A step by step series of examples that tell you how to get a development enviroment running:
* Install [PyCharm](https://www.jetbrains.com/help/pycharm/installation-guide.html) Community Edition.


## Running the tests


## Deployment
All the notebook can be used for research and academic basic function for Python. 

## Built With
* [PyCharm Community IDE](https://www.jetbrains.com/pycharm/download/#section=windows) 

## Contributing
Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](). 

## Authors

* **Truc Huynh** - *Initial work* - [TrucDev](https://github.com/jackyhuynh)

## Format
my README.md format was retrieved from
* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments
* Any acknowledgments go here