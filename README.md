# turbo
<DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8" />
    <title>Cancer's Global Footprint | Interactive map of cancer</title>
    <meta name="description" content="Cancer is often considered a disease of affluence, but about 70% of cancer deaths occur in low- and middle-income countries. 
    Explore this interactive map to learn about some cancers that disproportionately affect poorer countries." />
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
    <meta property="og:image" content="http://globalcancermap.com/img/map-thumb.png"/>
    <link href='http://fonts.googleapis.com/css?family=Lato:400,700' rel='stylesheet' type='text/css'>
    <link rel="shortcut icon" href="img/favicon.ico" type="image/x-icon" />
    <link rel="stylesheet" href="fonts/fonts.css" type="text/css" />
    <link rel="stylesheet" href="css/map.css" type="text/css" />
    <link rel="stylesheet" href="css/style.css" type="text/css" />
    <!-- <link rel="shortcut icon" href="img/favicon.ico" type="image/x-icon" /> -->
    <link rel="stylesheet" href="css/narrow.css" media="screen and (max-width: 980px)" type="text/css" />
    <link rel="stylesheet" href="css/mobile.css" media="screen and (max-width: 605px)" type="text/css" />
    <script src="ext/respond.src.js"></script>
    
    <script type="text/javascript">
  		var _gaq = _gaq || [];
  		_gaq.push(
  		['_setAccount', 'UA-17518137-2'],
  		['_trackPageview'],
  		['b._setAccount', 'UA-313492-2'],
  		['b._trackPageview']
  		);
    </script>
     
	</head>


<body id="all_incidence">  
<div id="header">
   <h2 class="site-title"><a href="/">PRI | Cancer's Global Footprint</a></h2>
   <span class="overlay-links"><a class="overlay-link" href="#">Data Notes</a></span>
   <span class="credit">Produced by <strong><a target="#" href="http://pulitzercenter.org">Pulitzer Center</a></strong> / <strong><a target="#" href="http://www.theworld.org">PRI's The World</a></strong></span>
  </div>

    <a id="fullscreen" target="#" href="/">View fullscreen &raquo;</a>
    <a id="back" target="#" href="http://theworld.org/cancer/">&laquo; View series</a>

  <div id="content-wrapper">
    
    <a title="Hide layer descriptions" id="content-toggle" href="#">Hide</a>
    
    <div id="indicator" class="layers">
       <a id="incidence" class="active" href="#all_incidence">Incidence</a>
       <a id="mortality" href="#all_mortality">Mortality</a>
    </div>

    <div id="cancer" class="layers">
       <a id="all" data-control="layer" href="#all_incidence">All</a>
       <a id="breast" data-control="layer" href="#breast_incidence">Breast</a>
       <a id="cervix" data-control="layer" href="#cervix_incidence">Cervical</a>
       <a id="liver" data-control="layer" href="#liver_incidence">Liver</a>
       <a id="lung" data-control="layer" href="#lung_incidence">Lung</a>
       <a id="prostate" data-control="layer" href="#prostate_incidence">Prostate</a>
       <a id="stomach" data-control="layer" href="#stomach_incidence">Stomach</a>
    </div>
    
    <div id="content">
      <div id="intro">
      
      <div id="all_incidence_intro" class="layer-intro">
        <h1>Global Cancer Incidence</h1>
        <span class="layer-description">Cancer is often considered a disease of affluence, but about 70% of cancer deaths occur in low- and middle-income countries. 
        Explore this interactive map to learn about some cancers that disproportionately affect poorer countries. 
        And check out the series <a target="#" href="http://www.theworld.org/cancer">Cancer’s New Battleground</a> from PRI's The World.</span> 
        <a class="prev-layer" data-control="layer" href="#stomach_mortality">&laquo; Previous</a> <span class="divider">|</span> 
        <a class="next-layer" data-control="layer" href="#all_mortality">Next &raquo;</a>
      </div>
      <div id="all_mortality_intro" class="layer-intro">
        <h1>Global Cancer Mortality</h1>
        <span class="layer-description">Cancer is a leading cause of death in many wealthy countries, and its toll is rising in poorer regions. 
        A 2012 study in <a target="#" href="http://www.thelancet.com/journals/lanonc/article/PIIS1470-2045%2812%2970211-5/abstract">The Lancet Oncology</a> predicted that from 2008-2030, cancer incidence will rise 75 percent globally and will double in 
        the least developed countries.</span>
        <a class="prev-layer" data-control="layer" href="#all_incidence">&laquo; Previous</a> <span class="divider">|</span> 
        <a class="next-layer" data-control="layer" href="#breast_incidence">Next &raquo;</a>
      </div>
      
      <div id="breast_incidence_intro" class="layer-intro">
        <h1>Breast Cancer Incidence</h1>
        <span class="layer-description">Breast cancer is the world’s most common cancer in women. The illness is diagnosed most frequently in developed countries. 
        Good nutrition in childhood and a relatively late age at which women begin childbearing are likely factors. 
        The high rate of disease in wealthy nations may also reflect aggressive screening.</span>
        <a class="prev-layer" data-control="layer" href="#all_mortality">&laquo; Previous</a> <span class="divider">|</span> 
        <a class="next-layer" data-control="layer" href="#breast_mortality">Next &raquo;</a>
      </div>
       <div id="breast_mortality_intro" class="layer-intro">
        <h1>Breast Cancer Mortality</h1>
        <span class="layer-description">Although breast cancer is diagnosed more commonly in wealthy nations, some low-income countries – 
        in Africa, Latin America, and the Caribbean – suffer very high mortality rates. A lack of early detection programs in these countries may play a role. 
        Genetics may also be a factor; women of African descent tend to develop more aggressive tumors than women of European descent.</span>
        <a class="prev-layer" data-control="layer" href="#breast_incidence">&laquo; Previous</a> <span class="divider">|</span>
        <a class="next-layer" data-control="layer" href="#cervix_incidence">Next &raquo;</a>
      </div>
      
       <div id="cervix_incidence_intro" class="layer-intro">
        <h1>Cervical Cancer Incidence</h1>
        <span class="layer-description">Rates of cervical cancer – once the leading cause of cancer death for women in the United States – have plummeted in North America 
        and elsewhere in the developed world. A big reason is the Pap test, which can identify precancerous lesions. In low-income countries, 
        testing is rare and the disease remains common and deadly.</span>
        <a class="prev-layer" data-control="layer" href="#breast_mortality">&laquo; Previous</a> <span class="divider">|</span> 
        <a class="next-layer" data-control="layer" href="#cervix_mortality">Next &raquo;</a>
      </div>
       <div id="cervix_mortality_intro" class="layer-intro">
        <h1>Cervical Cancer Mortality</h1>
        <span class="layer-description">The primary cause of cervical cancer is the human papillomavirus (HPV), a common sexually transmitted infection. Vaccines against HPV, 
        as well as low-cost tests that detect precancerous lesions, could dramatically lower death rates in countries where the disease still kills large numbers of women.</span>
        <a class="prev-layer" data-control="layer" href="#cervix_incidence">&laquo; Previous</a> <span class="divider">|</span>
        <a class="next-layer" data-control="layer" href="#liver_incidence">Next &raquo;</a>
      </div>
      
      <div id="liver_incidence_intro" class="layer-intro">
        <h1>Liver Cancer Incidence</h1>
        <span class="layer-description">Almost 85% of liver cancer cases occur in developing nations. In Asian countries such as Mongolia, the burden of disease is blamed 
        on high rates of hepatitis B and C, as well as widespread alcohol use. In West Africa, a contributing factor is exposure to aflatoxins, carcinogenic 
        compounds that can contaminate peanuts and other crops.</span>
        <a class="prev-layer" data-control="layer" href="#cervix_mortality">&laquo; Previous</a> <span class="divider">|</span>
        <a class="next-layer" data-control="layer" href="#liver_mortality">Next &raquo;</a>
      </div>
       <div id="liver_mortality_intro" class="layer-intro">
        <h1>Liver Cancer Mortality</h1>
        <span class="layer-description">In nations with high rates of liver cancer, people tend to contract the disease – and die from it – at an especially young age. 
        In some high-risk countries, childhood immunization programs against hepatitis B have been implemented. Such a vaccination program in Taiwan, launched in 1984, 
        appears to have reduced liver cancer rates among young adults.</span>
        <a class="prev-layer" data-control="layer" href="#liver_incidence">&laquo; Previous</a> <span class="divider">|</span>
        <a class="next-layer" data-control="layer" href="#lung_incidence">Next &raquo;</a>
      </div>
      
       <div id="lung_incidence_intro" class="layer-intro">
        <h1>Lung Cancer Incidence</h1>
        <span class="layer-description">Lung cancer kills more people globally than any other cancer, and by far the biggest cause of the disease is cigarettes. 
        The lag time between when a person starts smoking and when cancer develops can be 30 years. High rates of lung cancer in countries such as the United States 
        reflect high rates of smoking several decades ago.</span>
        <a class="prev-layer" data-control="layer" href="#liver_mortality">&laquo; Previous</a> <span class="divider">|</span> 
        <a class="next-layer" data-control="layer" href="#lung_mortality">Next &raquo;</a>
      </div>
       <div id="lung_mortality_intro" class="layer-intro">
        <h1>Lung Cancer Mortality</h1>
        <span class="layer-description">Smoking has declined in many industrialized countries, but it is increasing in developing nations. 
        Today, China consumes more than a third of the world’s cigarettes, and an estimated two thirds of men in Indonesia smoke. Experts predict sharp increases in 
        lung cancer deaths in the developing world in the years ahead.</span>
        <a class="prev-layer" data-control="layer" href="#lung_incidence">&laquo; Previous</a> <span class="divider">|</span> 
        <a class="next-layer" data-control="layer" href="#prostate_incidence">Next &raquo;</a>
      </div>
      
      <div id="prostate_incidence_intro" class="layer-intro">
        <h1>Prostate Cancer Incidence</h1>
        <span class="layer-description">Prostate cancer is the second most common cancer of men worldwide. The disease is diagnosed most frequently in high-income countries. 
        One reason is aggressive screening with the prostate-specific antigen (PSA) test. Screening can find cancer early – when it is treatable – but may also detect tumors 
        that would never pose a risk to a man’s life.</span>
        <a class="prev-layer" data-control="layer" href="#lung_mortality">&laquo; Previous</a> <span class="divider">|</span>
        <a class="next-layer" data-control="layer" href="#prostate_mortality">Next &raquo;</a>
      </div>
       <div id="prostate_mortality_intro" class="layer-intro">
        <h1>Prostate Cancer Mortality</h1>
        <span class="layer-description">Some countries in sub-Saharan Africa and other nations with large black populations face high death rates from prostate cancer. 
        Men of African descent are especially susceptible to the disease. In the United States, 
        African American men are more than twice as likely to die from prostate cancer as white men.</span>
        <a class="prev-layer" data-control="layer" href="#prostate_incidence">&laquo; Previous</a> <span class="divider">|</span>
        <a class="next-layer" data-control="layer" href="#stomach_incidence">Next &raquo;</a>
      </div>
      
      <div id="stomach_incidence_intro" class="layer-intro">
        <h1>Stomach Cancer Incidence</h1>
        <span class="layer-description">Rates of stomach cancer – the fourth most common cancer globally – vary dramatically within countries and between them. 
        Incidence is especially high in East Asia, where diets rich in salty and pickled foods are a risk factor. Infection with the bacterium H. pylori, 
        especially common in developing countries, is also considered a major cause of stomach cancer.</span>
        <a class="prev-layer" data-control="layer" href="#prostate_mortality">&laquo; Previous</a> <span class="divider">|</span>
        <a class="next-layer" data-control="layer" href="#stomach_mortality">Next &raquo;</a>
      </div>
       <div id="stomach_mortality_intro" class="layer-intro">
        <h1>Stomach Cancer Mortality</h1>
         <span class="layer-description">Stomach cancer was once the leading cause of cancer death in the United States; today, it doesn’t make the top ten. 
         This decline may be due in part to the advent of refrigeration, which has reduced the use of salt as a food preservative. Japan, where stomach cancer is 
         extremely common, conducts mass screenings to catch the disease early.</span>
        <a class="prev-layer" data-control="layer" href="#stomach_incidence">&laquo; Previous</a> <span class="divider">|</span>
        <a class="next-layer" data-control="layer" href="#all_incidence">Next &raquo;</a>
      </div>
      
      </div><!-- /#intro -->
      
      <div id="legend"></div>
      
    </div><!-- /#content -->
  </div><!-- /#content-wrapper -->
    
    
    <div id="map" class="map"></div>
    
    <div id="stories">
     <ul id="story-list">
      <li class="first"><span class="story-intro">Related Stories:</span></li>
      <li class="story1"><a class="story" target"#" href="http://www.theworld.org/2012/12/cancers-lonely-soldier/">Cancer's Lonely Soldier</a></li>
      <li class="story2"><a class="story" target"#" href="http://www.theworld.org/2012/12/pink-ribbons-to-haiti/">Pink Ribbons to Haiti</a></li>
      <li class="story3"><a class="story" target"#" href="http://www.theworld.org/2012/12/an-ounce-of-prevention/">An Ounce of Prevention</a></li>
      <li class="story4"><a class="story" target"#" href="http://www.theworld.org/2012/12/the-infectious-connection/">The Infectious Connection</a></li>
      <li class="story5"><a class="story" target"#" href="http://www.theworld.org/2012/12/dispensing-comfort/">Dispensing Comfort</a></li>
      <li class="story6"><a class="story" target"#" href="http://www.theworld.org/2012/12/the-breast-club/">The Breast Club</a></li>
      <li class="last story7"><a class="story" target"#" href="http://www.theworld.org/2012/12/land-of-tobacco/">Land of Tobacco</a></li>
      </ul>
    </div>
    
    
    <div id="data-notes">
      <div>
        <a class="close" href="#">Close</a>
        <h1>Data notes</h1>

		<strong>Cancer Data</strong>

		<p>The cancer statistics provided here come from <a target="#" href="http://globocan.iarc.fr/">GLOBOCAN</a>, a project of the International Agency for Research on Cancer. 
		The figures are estimates (for 2008) based on available data, as in many parts of the world there is no comprehensive 
		recordkeeping of cancer diagnoses and deaths. Read <a target="#" href="http://globocan.iarc.fr/DataSource_and_methods.asp">here</a> how the estimates were derived.</p>

		<p>Ferlay J, Shin HR, Bray F, Forman D, Mathers C and Parkin DM.
		GLOBOCAN 2008 v2.0, Cancer Incidence and Mortality Worldwide: IARC CancerBase No. 10 [Internet].
		Lyon, France: International Agency for Research on Cancer; 2010. Available from: <a target="#" href="http://globocan.iarc.fr">http://globocan.iarc.fr</a>, accessed on Oct. 1, 2012.</p>

		<strong>Country Data</strong>

		<p><a target="#" href="http://www.undp.org/content/undp/en/home.html">UNDP</a> is the source for 
		<a target="#" href="http://hdr.undp.org/en/reports/global/hdr2007-2008/">HDI ranking (2007/2008)</a>.<br />
		<a target="#" href="http://www.worldbank.org/">The World Bank</a> is the source for <a target="#" href="http://data.worldbank.org/indicator/NY.GDP.PCAP.CD">GDP per capita</a>, 
		<a target="#" href="http://data.worldbank.org/indicator/SH.XPD.PCAP">health expenditure per capita</a>, and 
		<a target="#" href="http://data.worldbank.org/indicator/SP.DYN.LE00.IN">life expectancy (2008)</a>.</p>
    </div>
    

    <!-- External libraries and site script -->
    <script src="ext/jquery.min.js"></script>
    <script src="ext/modestmaps.min.js"></script>
    <script src="ext/wax/wax.mm.js"></script>
    <script src="ext/wax/wax.ext.js"></script>
    <script src="ext/easey.js"></script>
    <script src="ext/mmg.js"></script>
    <script src="script.js"></script>
    
    <!-- Site configuration -->
    <script type="text/javascript">
        
        // Set map variables
        var zoomLevel;
        var hash = window.location.hash;
        if (hash == '#embed') {
          level = 1;
          range = [1, 5];
          latitude = 20;
          longitude = 10;
        } else {
          level = 2;
          range = [1, 5];
          latitude = -10;
          longitude = 10;
        }
    
        // Make a new map in the #map element
        var main = Map('map', {
            // Specify the MapBox API url
            api: 'http://a.tiles.mapbox.com/v3/pulitzercenter.base.jsonp',
            // api: 'http://a.tiles.mapbox.com/v3/pulitzercenter.cancer-global-incidence-10312012-1950.jsonp',
            center: {
                lat: latitude,      // Intial center point and zoom level.
                lon: longitude,      // To find coordinates and zoom levels
                zoom: level                   // try: http://www.getlatlon.com
            },
            zoomRange: range,             // Limit zooming on the map to these levels
            features: [                     // Map features (see readme.md)
                'zoomwheel',
                'tooltips',
                'zoombox',
                'zoompan',
                'share',
                'legend'
            ]
            
        });
        
        // Make a new layer switch for the map named `main`. Each layer gets
        // a name and an object of settings. The layers are bound by name to
        // the href hash of an element with a `data-control='layer'`, ex:
        // <a data-control="layer" href="#building">Building Permits, 2011</a>
        main.layers({
            all_incidence: { api: 'http://a.tiles.mapbox.com/v3/pulitzercenter.cancer-world-incidence-11302012-1101.jsonp' },
            all_mortality: { api: 'http://a.tiles.mapbox.com/v3/pulitzercenter.cancer-world-mortality-11282012-1306.jsonp' },
            breast_incidence: { api: 'http://a.tiles.mapbox.com/v3/pulitzercenter.cancer-breast-incidence-11302012-1109.jsonp' },
            breast_mortality: { api: 'http://a.tiles.mapbox.com/v3/pulitzercenter.cancer-breast-mortality-11282012-1326.jsonp' },
            cervix_incidence: { api: 'http://a.tiles.mapbox.com/v3/pulitzercenter.cancer-cervical-incidence-11302012-1113.jsonp' },
            cervix_mortality: { api: 'http://a.tiles.mapbox.com/v3/pulitzercenter.cancer-cervical-mortality-11282012-1346.jsonp' },
            liver_incidence: { api: 'http://a.tiles.mapbox.com/v3/pulitzercenter.cancer-liver-incidence-11302012-1117.jsonp' },
            liver_mortality: { api: 'http://a.tiles.mapbox.com/v3/pulitzercenter.cancer-liver-mortality-11282012-1405.jsonp' },
            lung_incidence: { api: 'http://a.tiles.mapbox.com/v3/pulitzercenter.cancer-lung-incidence-11302012-1122.jsonp' },
            lung_mortality: { api: 'http://a.tiles.mapbox.com/v3/pulitzercenter.cancer-lung-mortality-11282012-1419.jsonp' },
            prostate_incidence: { api: 'http://a.tiles.mapbox.com/v3/pulitzercenter.cancer-prostate-incidence-11302012-1126.jsonp' },
            prostate_mortality: { api: 'http://a.tiles.mapbox.com/v3/pulitzercenter.cancer-prostate-mortality-11282012-1458.jsonp' },
            stomach_incidence: { api: 'http://a.tiles.mapbox.com/v3/pulitzercenter.cancer-stomach-incidence-11302012-1131.jsonp' },
            stomach_mortality: { api: 'http://a.tiles.mapbox.com/v3/pulitzercenter.cancer-stomach-mortality-11282012-1503.jsonp' }  
         });
                          
    </script>

	<script type="text/javascript"> (function() {
   			var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
   			ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
   			var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
  			})();
	</script>
</body>
</html>
-adventure
