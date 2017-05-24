FROM mongo  

COPY init.json /init.json
CMD mongoimport -u steven -p admin --host db --db admin --collection test --type json --file /init.json --jsonArray
