In the city of Pearl, six superheroes got split into six different sites of the city. As it is a very large city and the superheroes want to communicate for any kind of enemy attack at their site with the other sites, they have built six network zones indicating their special powers, like-fire, water, wind, mind control, speed and intelligence.  
Given below are the names of the power units where network zones had been made and the number of hosts that had been required in each of those network zones:
  Fire Protective Site(129)
  Water Protective Site (43)
  Wind Protective Site (512)
  Mind Control Protective Site(224)
  Speed Protective Site (378)
  Intelligence Protective Site (62)
While establishing the network infrastructure, there are specific rules that were followed by the superheroes:
  Consider the network zones or individual sites as an individual Router.

  The Fire Protective Site was the Primary Communication Site for the superheroes. It acted as the center zone for all other network zones.
  The Water Protective Site, the Mind Control Protective Site and the Fire Protective Site were interconnected, to ensure 24/7 connectivity between these network zones.
  The Wind Protective Site was directly connected to the Fire Protective Site. 
  The Wind Protective Site had been connected to the Speed Protective Site and Intelligence Protective Site individually.

  Choose an appropriate network address and create subnets to assign to each of the network zones so that the least amount of IP addresses is wasted.

  The network zones in the Water Protective Site and the Speed Protective Site used static IP addressing to ensure security while the other network zones had their IP addresses through a dedicated DHCP server. This DHCP server was present in the Water Protective Site.
  Email could also be exchanged between all the network zones. So, an Email server had been set up and it was located in the Intelligence Protective Site.
  Every network zone also required printers to print large numbers of site information from time-to-time every day.
  The Water Protective Site also had a web server and a DNS server. If anyone had typed the URL www.thepearlcity.com, they would have seen a webpage that says ‘Welcome to the Pearl City’.

  All servers were configured manually.
  
  Routing in the whole network had followed these rules:
  Configure at least two networks to be routed dynamically and two to be routed statically. The Water Protective Site was directly connected to the Fire Protective Site, and the Mind Control Protective Site would communicate with Fire Protective Site via Water Protective Site.
  The Mind Control Protective Site and Fire Protective Site were also connected, as mentioned earlier, but it was not the primary route. A backup route had been configured here.
  However, you have to remember that the default route couldn’t be used while exchanging packets. Data was delivered using static routes only.

  Showing 2 end devices (including printer) per network is good enough to represent the whole population.

  You need to be able to ping each network zone from another after all the configurations are complete.

Deliverables
  The network mentioned above should be implemented in Cisco Packet Tracer, with necessary devices and full configuration.
  After completion you should be able to test the conditions imposed.
  You will have to submit the followings:
  Network topology diagram with proper labels
  The configuration commands of all the routers that you have implemented.
  VLSM tree
  IP address table

