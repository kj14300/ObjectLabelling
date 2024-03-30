
sudo apt-get update

sudo apt install docker.io

sudo snap install docker

sudo chmod 666 /var/run/docker.sock

docker build -t streamlit .

docker run -d -p 8501:8501 streamlit

streamlit run app.py

