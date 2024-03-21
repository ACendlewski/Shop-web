# Użyj oficjalnego obrazu Pythona 3.9
FROM python:3.9

# Ustaw katalog roboczy na /app
WORKDIR /app

# Skopiuj katalogi API_SALE-BLOG, webshop_app i webshop_project do kontenera
COPY API_SALE-BLOG/ ./API_SALE-BLOG
COPY webshop_app/ ./webshop_app
COPY webshop_project/ ./webshop_project

# Skopiuj plik requirements.txt do kontenera
COPY requirements.txt .

# Zainstaluj zależności
RUN pip install --no-cache-dir -r requirements.txt
