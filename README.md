# car-selling-price-prediction

## Docker Command

git clone https://github.com/sahil13kumar/CarSellingPricePrediction <br />
cd CarSellingPricePrediction  <br />
docker build -t carprice .  <br />
docker run -p 5000:5000 -d --name carpriceprediction carprice  <br />

you can check out running container :-

docker ps -a | grep carpriceprediction
