FROM python:3.12-slim

WORKDIR /app

RUN useradd --create-home appuser

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY --chown=appuser:appuser . .

USER appuser

EXPOSE 5001

CMD ["flask", "--app", "app:create_app", "run", "--host", "0.0.0.0", "--port", "5001"]