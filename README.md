# car-selling-price-prediction

## Docker Command

git clone https://github.com/sahil13kumar/CarSellingPricePrediction <br />
cd CarSellingPricePrediction
docker build -t carprice .
docker run -p 5000:5000 -d --name carpriceprediction carprice

you can check out running container :-

docker ps -a | grep carpriceprediction
