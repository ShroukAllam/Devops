FROM python

ENV APP_MODE=production
ENV APP_REGION=canada-west

WORKDIR /app

COPY app.py .

RUN pip install flask 

EXPOSE 8080

CMD ["python", "app.py"]


