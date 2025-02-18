git clone ...

python3 -m venv venv

source venv/bin/activate

<!-- pip -->
python3 -m pip install --upgrade pip

<!--Have access to docker with login credentials set-->
docker build . -t voice-chatapp-powered-by-openai

docker run -p 8000:8000 voice-chatapp-powered-by-openai
