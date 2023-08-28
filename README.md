
# Real Estate Mock API (Using JSON Server)

This repository contains a mock API for real estate listings created using JSON Server. You can use this mock API to simulate real estate listing data for development purposes.

## Getting Started

### Prerequisites

Node.js and npm should be installed on your system. If not, you can download and install them from the official [Node.js website](https://nodejs.org/).

### Clone the Repository

```bash
git clone https://github.com/anshumansinha1/real-estate-mock-api.git

cd real-estate-mock-api
```


## Running the Mock Server

### Install JSON Server:
Open your terminal or command prompt and install JSON Server globally by running the following command:

```
npm install -g json-server
```

### Start the JSON Server:

In your terminal, navigate to the directory containing the db.json file. Start JSON Server by running the following command:

```
json-server --watch db.json --port 5000
```

This will start your JSON Server at 5000 port.

### GET the Data

In order to access the json data, use the following enpoint in your browser or postman: 

```
localhost:5000/real-estate-data
```

