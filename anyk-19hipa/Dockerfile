FROM reisingeradam/anyk:latest
LABEL maintainer="Dezso Burjan"

# Download and install 19HIPA plugin for ANYK         
RUN wget https://www.nav.gov.hu/data/cms578457/NAV_19HIPA.jar -P ~ \
    # -s: silent (non-gui) install
    && java -jar ~/NAV_19HIPA.jar -s \
    && rm ~/NAV_19HIPA.jar