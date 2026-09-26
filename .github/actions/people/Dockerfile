FROM python:3.9@sha256:da5aee29682d12a6649f51c8d6f15b87deb3e6c524b923c41d0cb3304d07c913

RUN pip install httpx PyGithub "pydantic==2.0.2" pydantic-settings "pyyaml>=5.3.1,<6.0.0"

COPY ./app /app

CMD ["python", "/app/main.py"]
