# kepler-grafana-dashboard

Grafana dashboard showing the following information:

1. Total Daily Dynamic CO2e emisisons (mg) per Namespace
2. Dynamic CO2e emissions (mg) per Namespace per minute
3. Dynamic CO2e emissions (mg) per Pod per minute
4. Total Daily Dynamic Power Consumption (kWh) per Namespace
2. Dynamic power consumption (W) per Namespace per minute
3. Dynamic power consumption (W) per Pod per minute

Able to filter on namespace and pod. Emission Factor and PUE (Power Usage Effectiveness) taken from `https://www.eea.europa.eu/data-and-maps/daviz/co2-emission-intensity-14/#tab-googlechartid_chart_41` and `https://www.cloudcarbonfootprint.org/docs/methodology/#power-usage-effectiveness` respectivaly for AWS eu-west-1 region (Ireland).