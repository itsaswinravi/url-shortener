py -m venv venv

.\venv\Scripts\activate

from url_shortener import create_app
app=create_app()