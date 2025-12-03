FROM python:3.14@sha256:5b95b240f2db781f34a5da81e6e2301378495b3ab78d689df325c937be267e1c

RUN pip install httpx PyGithub "pydantic==2.0.2" pydantic-settings "pyyaml>=5.3.1,<6.0.0"

COPY ./app /app

CMD ["python", "/app/main.py"]
