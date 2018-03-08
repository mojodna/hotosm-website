---
Summary Text: Today we are launching OSM Analytics, a platform for exploring and analyzing
  OpenStreetMap data. With the current database growing to almost 50 gigabytes, and
  thousands of features added every day, OSM is officially entering the big data league.
Person: Cristiano Giovando
date: '2016-04-28 11:56:16 Z'
Working Group: []
Projects:
- OpenStreetMap Analytics
permalink: updates/2016-04-28_explore_how_the_world_is_mapped_with_osm_analytics
title: Explore How the World is Mapped with OSM Analytics
created: 1461844576
---
<p>Today we are launching <a href="http://osm-analytics.org/" target="_blank">OSM Analytics</a>, a platform for exploring and analyzing OpenStreetMap data. With the current database growing to almost 50 gigabytes, and thousands of features added every day, OSM is officially entering the big data league. Making sense of this much data, globally, locally, and temporally, presents significant challenges.</p><p><img src="/sites/default/files/Screen%20Shot%202016-04-28%20at%2014.05.34.png" alt="" width="640" height="353"></p><p>&nbsp;Through a small <a href="http://www.knightfoundation.org/grants/201551652/" target="_blank">prototype grant</a> by the Knight Foundation, the Humanitarian OpenStreetMap Team and key partners created OSM Analytics, an online platform for real time analysis and visualization of the OpenStreetMap database. This application allows anyone to display quantity and distribution of common map features such as roads and buildings. Data is visualized on a map where users can define custom areas of interest and dynamically obtain summary statistics. A time graph also allows to display when selected map data was added or last edited in OSM and to filter the results by specified date ranges.</p><p>This tool finally enables anyone to explore the entire OSM map, from global to local scale and understand how it was created. For example, <a href="http://osm-analytics.org/#/show/polygon:lwmnM~zbKei%7D%40uslAo%60k%40syzBi%7Bd%40fcB%7CtG%7DqrAvbfAk%7BmAcu%60Ae~%40zifBkcb%40%60naBufgAryv%40%60rf%40vrvDctb%40tu_%40uwsAvd_B%7DeSn%60Vwsl%40jndByfs%40rmnC%7DwDnhwBx%7C%7DAjesEvtcLfpO%60%7DpLksyEduF%7DkLdpsAnyv%40nrXza%40%60dwA%7Bvs%40ey%5BidjA%60~d%40ad%60%40%7B%7DHia%60Ab~~Aa_q%40zoNyghA%7DgvAej%7C%40akfF_oe%40%7C%60Mom%7B%40gjvAu%7B~EiulA/highways/recency" target="_blank">the impact of HOT activations can be easily visualized</a>, both spatially and temporally, and measured in terms of map objects created. Journalists now have an easy-to-use application to tell data-rich stories of how OpenStreetMap is changing our world, one map at a time. Humanitarian organizations who rely on OSM data for navigation and reference during disaster response, can now better understand map coverage and quality. Donors and governments who are funding community mapping projects are now given an intuitive way to visualize and measure the impact of their investments.</p><p>In order to make the application highly responsive and interactive, much of the data is being precomputed through daily backend routines that create global vector tiles caches of data aggregated at different zoom levels. Information is currently updated daily, but it should be feasible to increase frequency depending on demand and performance optimization. The entire application code is open source, making it easy to extend, add new functions, and interact with other OSM data analysis tools. As this is currently still a prototype, please keep in mind that things may not always function as expected. If you experience any problem or want to help us out by proposing new features, please <a href="https://github.com/hotosm/osm-analytics/issues" target="_blank">file an issue on Github</a>.</p><p>A big thanks goes to <a href="https://github.com/tyrasd" target="_blank">Martin Raifer</a>, who was hired by HOT to develop this project, and in only 6 weeks made the OSM Analytics idea into reality. Since our <a href="https://hotosm.org/updates/2016-03-10_osm_data_analysis_tool_development_kicks_off" target="_blank">kick off meeting in early March</a>, we have also been getting invaluable help by our friends at Development Seed who guided us to effective UI/UX design, and by the Mapbox team who helped with backend tools and data processing.</p><p>OSM Analytics was built for and by the OSM community (thank you to <a href="http://www.openstreetmap.org/user/dekstop/diary/35620" target="_blank">Martin Dittus</a> and many others who participated in the initial brainstorming), please try it out, let us know what you think. If you are a developer we would love you to join us as we build more functionalities and provide deeper insights into our beautifully growing map!</p><p><img src="/sites/default/files/Screen%20Shot%202016-04-28%20at%2013.48.33.png" alt="" width="640" height="354"></p><p>&nbsp;</p><p>&nbsp;</p>