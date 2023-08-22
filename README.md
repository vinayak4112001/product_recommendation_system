# Personalised Product Recommendation System
Personalised Product Recommendation System is a **Product Recommendation System** that shows the users **Recommended Products** based on the **User's personalised data**.
It is a web-based solution that takes user's input and shows recommended products based on the product ratings,specifications and similarities. The application is build by using Flask for the backend,NextJS for the frontend and ML model using countVectorizer and cosine similarity.

### Table of Contents
* [Features](#features)
* [Examples](#examples)
* [Tech Stack](#tech-stack)
* [Getting Started](#getting-started)
* [Contributors](#contributors)
* [License](#license)
  
## Features
* Searching for a desired product.
* Recommending products based on the searched product.
* Recommended products are shown to the user.
* Prodructs of the same brand can also be recommended using **same brand** filter.

## Examples

Link to Project:- 

1. Frontpage of Website:

![vlcsnap-2023-04-30-17h03m50s340](https://github.com/kuber2001/product_recommendation/blob/main/images/1.PNG)


2. Recommended Products being shown to the user:

![vlcsnap-2023-04-30-17h04m15s267](https://github.com/kuber2001/product_recommendation/blob/main/images/2.PNG)


3. Products of the same brand can also be shown to the user:

![vlcsnap-2023-04-30-17h04m24s875](https://github.com/kuber2001/product_recommendation/blob/main/images/3.PNG)


## Tech Stack
The application is built on the following tech stack:

* Flask - A micro web framework for building web applications in Python.
* NextJS - A popular React framework for building server-side rendered applications.

## Getting Started
To get started with the application, you will need to follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/kuber2001/product_recommendation.git
```

2. Install the dependencies:
node_modules

```bash
cd frontend

npm install
python model\train_model.py

```
run the model.py file 
you will get 2 files saved in your folder
similarity.pkl,transformed_eg_dataset.pkl
move both the .pkl files in the server folder 
```bash
python backend\run_server.py
```

3. Start the application:

```bash
npm run dev
```

4. Open your web browser and go to http://localhost:3000.


## Contributors:

1. [Kuber Vajpayee](https://github.com/kuber2001)
2. [Shivang Rajouria](https://github.com/Shivang-Rajouria)
3. [Vinayak Jaimini](https://github.com/vinayak4112001)

## License
This project is licensed under the MIT License. See the LICENSE file for more information.
