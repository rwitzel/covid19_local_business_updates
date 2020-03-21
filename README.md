# covid19_local_business_updates_map

This HTML5 component shows COVID-19-related information in an 
(OpenStreetMap)[https://www.openstreetmap.org].

In detail the component
* shows all local businesses that entered COVID-19-related updates into OpenStreetMap,
* highlights businesses that require immediate financial support (via coupons, microcredits, donations),
* allows filtering by 
   * special access for high risk persons, 
   * safe pick up option (timeslot), 
   * alternative online buying and delivery option
   * infection prevention policy. 
* allows embedding in other mobile apps and HTML5 webpages.

TODO screenshot with link here

(Click here for the map)[https://rwitzel.github.io/covid19_local_business_updates_map/].

## How to show the component locally in a browser?

A local webserver can be started via [docker-compose](https://docs.docker.com/compose/install/):

    docker-compose up
    open http://127.0.0.1:8081
    open http://127.0.0.1:8081/experiments/exp_embed_openstreetmap/index.html
