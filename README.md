# Jsk-and-React-Component
checkpoint


npx create-react-app product-app
cd product-app
npm install react-bootstrap bootstrap
npm start

import "bootstrap/dist/css/bootstrap.min.css";

const product = {
  name: "Nike Air Max",
  price: "$120",
  description: "Comfortable and stylish running shoes for everyday use.",
  image: "https://via.placeholder.com/200"
};

export default product;
import product from "./product";

function Name() {
  return <h3>{product.name}</h3>;
}

export default Name;
