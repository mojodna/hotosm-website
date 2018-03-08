---
Person: Cristiano Giovando
date: '2015-07-24 07:31:00 Z'
Working Group: []
Projects:
- OpenAerialMap
permalink: updates/2015-07-24_oam_adds_dynamic_filtering_upload_tools_coming_soon
title: OAM Adds Dynamic Filtering, Upload Tools Coming Soon
created: 1437723060
---
<p>During the recent Nepal earthquakes, digital humanitarians were suddenly flooded with data, a lot of data, especially aerial imagery collected with satellites and small unmanned aerial systems (sUAS, also known as drones), and <a href="http://hotosm.org/updates/2015-07-14_nepal_earthquake_a_note_of_thanks_to_hot%E2%80%99s_aerial_imagery_providers" target="_blank">openly shared with anyone</a>.</p><p>Despite the unprecedented amount of imagery collected and shared in response to the earthquakes, still much effort was <a href="http://hotosm.org/updates/2015-04-28_processing_fresh_imagery_for_nepal_earthquake_response" target="_blank">required</a> to identify available images for high-priority areas and to process them into formats usable in OpenStreetMap mapping tools. What HOT didn't have -- and is now building -- is a common place to share and search free imagery, called OpenAerialMap (OAM). OAM was <a href="http://hotosm.org/updates/2015-02-25_updates_from_the_openaerialmap_project" target="_blank">introduced</a> in February, then the first beta version was <a href="http://hotosm.org/updates/2015-05-28_openaerialmap_beta_goes_live" target="_blank">presented</a> about two months ago.&nbsp;</p><p>Now, the OAM catalog has received additional exciting features including the ability to dynamically filter images based on resolution, acquisition date and source type. The team at Development Seed has done an excellent job at creating an <a href="https://developmentseed.org/blog/2015/06/05/designing-openaerialmap/" target="_blank">intuitive user interface</a> that provides easy access to hundreds of images already shared by government agencies, commercial satellite companies and individual drone mappers.</p><p><img title="The OAM catalog with recently added filtering options" src="/sites/default/files/Screen%20Shot%202015-07-24%20at%2000.13.20.png" alt="" width="730" height="409"></p><p>Volunteers with the Humanitarian OpenStreetMap Team (HOT) use this imagery through mapping tools to crowdsource the creation and updating of base maps in areas affected by disasters. By visually analyzing images, even novice volunteers are able to trace features such as roads, trails and buildings. Without aerial imagery, which allows thousands to participate from anywhere in the world, the mapping effort is limited to a small number of volunteers on the ground. Imagery is crucial to HOT. Being able to acquire and process it quickly, also means faster and more comprehensive maps and quicker delivery of data to responders trying to reach affected populations.</p><p>While the documentation for the OAM Catalog and API is being finalized, our friends at Azavea and Stamen are <a href="https://gitter.im/hotosm/oam-server" target="_blank">hard at work</a> to build another important component of OAM, the server. The OAM Server will allow automatic processing of images from OAM into “tile map services” ready for use in OSM tracing tools, such as JOSM and iD. Relying on scalable infrastructure in Amazon Web Services and cloud computing services such as Heroku, the HOT-hosted OAM will be able to ingest large amounts of imagery quickly during an emergency and make it available through reliable web services.</p><p>If you are a developer interested in the project we would love <a href="https://github.com/hotosm/OpenAerialMap/wiki/How-to-Contribute" target="_blank">your feedback</a>. If you are a Quality Assurance (QA) Engineer or in general an expert with cloud computing, Node.js and software testing, <a href="http://hotosm.org/job/openaerialmap_call_for_qa_engineer/2015" target="_blank">we want to hire you</a>!</p><p>But don’t worry. OpenAerialMap is not just boring code! More &nbsp;important, is what’s shared in it, such as beautiful images collected by our colleagues <a href="http://hotosm.org/updates/2015-07-17_ramani_huria_scale_up_dar_es_salaam_6th_july_2015">mapping in Dar es Salaam</a> and the dramatic views of devastated Nepal captured by Digital Globe's Worldview 3 satellite.&nbsp;</p><p>The exciting news is that anyone can now participate in OpenAerialMap and make it easy to share their open imagery with the rest of the world, whether for disaster response, community mapping, research studies or any application compatible with its open license. At the moment anyone can <a href="https://github.com/hotosm/OpenAerialMap/labels/new%20data" target="_blank">submit a request on Github</a> to have imagery posted.In addition, we are developing two tools that will make uploading to OAM easier. One of our interns from the Outreachy program <a href="http://www.openstreetmap.org/user/tassia/diary" target="_blank">is developing a plugin</a> for Quantum GIS, a popular open-source GIS software, that will allow its user to upload aerial images to the <a href="https://github.com/openimagerynetwork" target="_blank">Open Imagery Network</a> (OIN). OIN is a federated network of highly available online data stores, which are indexed and discoverable through OAM. With gracious support from the Humanitarian Innovation Fund, we are also funding the development of a web form, allowing anyone to upload imagery directly from the OAM web site with any standard web browser.</p><p>Join the open-imagery revolution and <a href="https://gitter.im/hotosm/OpenAerialMap" target="_blank">share your ideas</a> and questions about OpenAerialMap on Gitter. If you are a drone mapper and want to help when disaster strikes, learn how you can join a standby task force of trained “<a href="http://uaviators.org/" target="_blank">UAViators</a>” and have your images shared in OAM. If you do <a href="http://publiclab.org/wiki/balloon-mapping" target="_blank">balloon mapping</a> like our friends at Public Lab, keep “<a href="http://mapknitter.org/" target="_blank">knitting</a>” and <a href="http://opendronemap.github.io/odm/" target="_blank">automagically creating</a> beautiful mosaics which will soon be indexed in OAM.</p>