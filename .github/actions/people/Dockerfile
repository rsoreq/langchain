FROM python:3.9@sha256:10c3875a6435af5b2461c6f99c52bfa11716aae0ca8b27b77f81df9faab93b16

RUN pip install httpx PyGithub "pydantic==2.0.2" pydantic-settings "pyyaml>=5.3.1,<6.0.0"

COPY ./app /app

CMD ["python", "/app/main.py"]
