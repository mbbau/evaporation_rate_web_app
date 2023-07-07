# World Evaporation Rate Distributions

In this repository, you will be able to find all the code and details for a web app that tries to estimate evaporation rates distribution for concrete surfaces for diferents months and locations accross the world.

This web app will be based in the work done in this repository [Córdoba's climate analysis and Monte Carlo Simulation to calculate Evaporation Rate](https://github.com/mbbau/Cordoba-s-climate-analysis-and-Monte-Carlo-Simulation-to-calculate-Evaporation-Rate).

In the work previously mentioned, I obtained climate data from the Argentinean Climate Agencia, but the information was in the form of CSV files. In this work, I will make use of [Open Meteo API](https://open-meteo.com/en/docs/historical-weather-api) in order to be able to give the user the ability to select where it want to make this analysis. As this API uses coordinates, I will get location data (lat/lon) for the input location using [Openstreetmap's Nominatim](https://nominatim.openstreetmap.org/ui/search.html). I learnt about the Climate API usage and the Openstreetmap workaround from [Jan Kühn](https://yotka.org/) work, where he made a [web app](https://yotka.org/projects/meteo-hist) to 

