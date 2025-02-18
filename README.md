git clone ...

<!--Have access to docker with lofin credentials set-->
docker build . -t voice-chatapp-powered-by-openai

docker run -p 8000:8000 voice-chatapp-powered-by-openai
