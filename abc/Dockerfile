# Dockerfile

FROM python:3.10

# Skopiuj pliki aplikacji
COPY . /abc

# Ustaw katalog roboczy
WORKDIR /abc

# Zainstaluj zależności
RUN pip install -r requirements.txt

# Uruchom aplikację
CMD ["abcpython", "main.py"]

