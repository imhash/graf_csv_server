Installation Guide.

Pre-Requisites:
1.  Node JS
2.  Grafana Simple JSON Datasource 


Step 1: Install Node Js
Visit https://nodejs.org/en/download/

Step 2: Download graf_csv_server
git clone https://github.com/imhash/graf_csv_server.git

Step 3: Start CSVServer
cd graf_csv_server

node CSVServer.js

step 4: Install the Data Source
Use the grafana-cli tool to install SimpleJson from the commandline:
"grafana-cli plugins install grafana-simple-json-datasource"
The plugin will be installed into your grafana plugins directory; the default is /var/lib/grafana/plugins
Visit https://grafana.com/grafana/plugins/grafana-simple-json-datasource/installation

step 5: Configure DataSource
Accessed from the Grafana main menu, newly installed data sources can be added immediately within the Data Sources section.
Next, click the  Add data source button in the upper right. The data source will be available for selection in the Type select box.


