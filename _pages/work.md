---
layout: page
permalink: /work/
title: work
nav: true 
---
<html lang="en">
<style>
@font-face {
    font-family: 'Spectral';
    src: url('fonts/Spectral/Spectral-Regular.ttf') format('Spectral-Regular');
  }
  @font-face {
    font-family: 'Spectral';
    src: url('fonts/Spectral/Spectral-Light.ttf') format('Spectral-Light'),
  }
  body {
    margin: 0;
  }
  body, /*h2*/, h3, p, /*ul*/, /*li*/ {
    font-family: 'Spectral', serif;
    font-size: 1.5rem;
    font-weight: 300;
    line-height: 1.3;
    color: #181818;
    background: #F7F6F6;
  }
  h2 {
    color: #D21258;
  }
  .intro, .links-nav, .cv, .education, .footer {
    width: 100%;
    max-width: 60rem;
    /* margin-left: auto; */
    margin-left: 0px;
    /* margin-right: auto; */
    margin-right: 20px;
    margin-bottom: 20px;
  }
  .portfolio {
    width: 90%;
    /* margin-left: auto; */
    margin-left: 0px;
    margin-right: 20px; 
    margin-top: 150px;
  }
  .header {
    font-family: 'Spectral', serif;
    width: 62%;
    margin: auto;
    /* margin-left: 470px; */
    /* margin-top: 100px; */
    height: 40vh;
  }
  a {
    text-decoration: none;   
    color: #D21258;
    /* background: -webkit-linear-gradient(left,#D21258,#D21258 100%);
    background: linear-gradient(left,#D21258,#D21258 100%);
      background-position: 0 90%;
      background-size: 10px 1px;
      background-repeat: repeat-x; */
  }
  /* .small-text a {
    text-decoration: none;   
    color: #181818;
    background: -webkit-linear-gradient(left,#181818,#181818 100%);
    background: linear-gradient(left,#181818,#181818 100%);
      background-position: 0 90%;
      background-size: 10px 1px;
      background-repeat: repeat-x;
  } */
  a:hover {
    text-decoration: none;
    color: #D21258;
    /* background: -webkit-linear-gradient(left,#D21258,#D21258 100%);
    background: linear-gradient(left,#D21258,#D21258 100%);
      background-position: 0 90%;
      background-size: 10px 1px;
      background-repeat: repeat-x; */
  }
  /* a:active {
    text-decoration: none;
    color:#181818;
    background: none;
  } */
  ::selection {
    color: #D21258;
    background: #ffc5ce; 
    text-shadow: none;
  }
  .header h1{
    /* color: #D21258 */
  }
  .portfolio-item {
    margin-bottom: 100px;
    padding: 5px;
    color: #D21258;
  }
  .portfolio-item img {
    width: 100%;
  }
  .description {
    display: grid;
    grid-template-columns: 1fr 40rem 1fr;
    column-gap: 20px;
  }
  .links-nav ol, ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
  }
  .links-nav li {
  display: inline;
  padding-right: 20px;  
  }
  .cv p{
    margin-bottom: 0;
  }
  .small-text {
    font-family: 'Spectral', serif;
    font-size: 1rem;
    font-weight: 300;
    line-height: inherit;
    margin-top: 4px;
  }
  .small-heading {
    text-transform: uppercase;
    margin-bottom: 4px;
  }
  .footer{ 
    margin-top: 200px;
    margin-bottom: 50px;
    color:  #616a6b;
  }
  /* viewport sizing  */
  .main {
    max-width: 1600px;
  }
  @media screen and (max-width: 1024px) {
   .description {
     display: grid;
     grid-template-columns: 1fr 3fr;
    }
  }
  @media screen and (max-width: 800px) {
    .header, .intro, .links-nav, .cv, .education, .footer, .portfolio-item {
      max-width: none;
      margin-bottom: 75px;
     }
     .portfolio, .footer {
       margin-top: 100px;
     }
     .description {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
     }
     .description p {
       margin-top: 0;
     }
   }
</style>
<head>
	<title>strategyxdesign</title>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="main.css" type="text/css" charset="utf-8" />
	<link rel="preconnect" href="https://fonts.googleapis.com"> 
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin> 
<link href="https://fonts.googleapis.com/css2?family=Spectral&display=swap" rel="stylesheet">
</head>

<body>
	<!-- <div class="header">
		<h1>Tom Eldridge</h1>
	</div> -->
	<div class="main">		
		<div class="intro">
			<p>I am Tom Eldridge, a strategic designer building products and services that are sustainable and people orientated. ​ Currently designing at <a href="https://www.gov.uk/universal-credit">Univeral Credit</a>, to help citizens into work.</p>
			<p>I help organisations find the right opportunities to future-proof their business by helping them design for the people and environments they operate in. <a href="mailto:tom.eldridge@gmail.com">Get in touch</a> if you’d like to work together.</p>
		</div>
<!-- Links -->
	<!-- <div class="links-nav">
		<h2 class="small-text small-heading">Links</h2>
		<ul>
			<li><a href="https://buttondown.email/tomxedridge">Newsletter</a></li>
			<li><a href="https://www.instagram.com/tomxeldridge/">Instagram</a></li>
			<li><a href="https://twitter.com/MajorTomLDN">Twitter</a></li>
			<li><a href="https://github.com/TeldridgeLDN">Github</a></li>
		</ul>			
	</div> -->
<!-- Portfolio posts -->
		<div class="portfolio">
			<div class="portfolio-item">
				<div class="description">
					<h2><a href="https://www.gov.uk/government/collections/kickstart-scheme">Kickstart Scheme</a></h2>
					<p>
					Lead Service Designer, responsible for creating a consistent and reliable service at the height of the pandemic to help young people into work.
					</p>
				</div>
				<img src="/assets/img/UC_Kickstart.png" alt="Screenshots of the Kickstart Scheme Job page and summary of the scheme">
			</div>
			<div class="portfolio-item">
				<div class="description">
					<h2><a href="https://www.bsigroup.com/en-GB/">British Standards Institute</a></h2>
					<p>Strategic Designer, tasked with refreshing the digital service and shaping organizational change.</p>
				</div>
				<img src="/assets/img/BSI_v3.jpg" alt="Screenshots of BSI website desktop view of a home page and the customer's collection page">
			</div>
			<div class="portfolio-item">
				<div class="description">
				<h2><a href="https://www.yunojuno.com/">YunoJuno</a> 
				</h2>
				<p>Research and strategic design work for a freelancer jobs platform under going change.</p></div>
				<img src="/assets/img/YunoJuno.png" alt="Gif of payment link creation flow">
			</div>
            <div class="portfolio-item">
				<div class="description">
				<h2><a href="https://www.ustwo.com/work/three-alpha-ing-a-service/">Three</a> 
				</h2>
				<p>Strategic Designer, with responsibility for creating a coherent strategic vision and customer service offering.</p></div>
				<img src="/assets/img/Three_UsTwo_v2.jpg" alt="Screenshots of CMS showing the tagging interface and a new post page">
			</div>
			<!-- <div class="portfolio-item">
				<div class="description">
					<h2><a href="https://www.ustwo.com/work/three-alpha-ing-a-service/">Three</a></h2>
					<p>Strategic Designer, with responsibility for creating a coherent strategic vision and customer service offering.</p>
				</div>
				<img src="/assets/img/Portfolio_2020_Three.jpg" alt="Screenshots of CMS showing the tagging interface and a new post page"> -->
				<!-- <p class="small-text">with <a href="https://www.linkedin.com/in/lbyron/">Leila Byron, <a href="https://www.linkedin.com/in/jasondaponte/">Jason DaPonte, <a href="https://www.linkedin.com/in/aaronmctavish/"> and Aaron McTavish</p> -->
			</div>
			<div class="portfolio-item">
				<div class="description">
				<h2>Art of Work</h2>
				<p>
				Strategic design lead on a pop-up exhibition from Microsoft and SAP to showcase how machine learning can transform business, expressed through the power of art.  
				</p></div>
				<img src="/assets/img/art_of_work.jpg" alt="Image exhibition">
				<!-- <p class="small-text">with <a href="https://www.linkedin.com/in/paul-gascoigne-10174816/">Paul Gascoigne</p>  -->
			</div>
			<div class="portfolio-item">
				<div class="description">
				<h2>Barclays Retail Bank</h2>
				<p>Strategic Design work with the senior Barclays team to simplify their product and services towards a more holistic customer offering with the focus on their lifestage.</p></div>
				<img src="/assets/img/Barclays_v2.jpg" alt="Barclays Current Account and Personal Account services">
			</div>
			<div class="portfolio-item">
				<div class="description">
				<h2>Virgin Atlantic</h2>
				<p>Discovery work for Virgin Atlantic, exploring the airport lounge of the future against the backdrop of sustainable travel and increased competition.</p></div>
				<img src="/assets/img/virgin_atlantic.jpg" alt="Image of Virgin Atlantic Lounge and app">
			</div>
			<div class="portfolio-item">
				<div class="description">
				<h2>NatWest</h2>
				<p>Service Design lead responsibile for a savings app to help young people save for the things that matter most to them. </p></div>
				<img src="/assets/img//Natwest.jpg" alt="Mobile app where customers can save money, and advertising campaign">
			</div>
		<div class="cv">
			<h2 class="small-text small-heading">Previously</h2>
			<p>
				oct 2016–feb 2019<br />
				Service Design Lead, Momentum
			</p>
			<p>
				jan 2014- oct 2016<br />
				Freelance Strategic Designer
			</p>
			<p class="thick">
				may 2013 -jun 2014<br /></p>
				Strategist, LinkedIn
			<!-- </p> -->
			<p>
				mar 2011-mar 2013<br />
				Freelance Strategist
			</p>
			<p>
				july 2007-nov 2011<br />
				Digital Strategist, Sony Pictures
			</p>
			<p>2006–2007<br />
				Strategist, Digital start-up 
			</p>
			<p>
				2002–2006<br />
				Graduate, Singer & Friedlander Bank
			</p>
		</div>
		<div class="education">
			<h2 class="small-text small-heading">Education</h2>
			<p>
				1999–2000<br />
				Political Theory MSc (2:1)<br />
				London School of Economics
			</p>
			<p>
				1996-1999<br />
				Politics & Government BA (2:1)<br />
				University of Kent
			</p>
		</div>
<!-- Links -->	
<!-- <div class="links-nav">
	<h2 class="small-text small-heading">Links</h2>
	<ul>
		<li><a href="https://buttondown.email/tomxedridge">Newsletter</a></li>
		<li><a href="https://www.instagram.com/tomxeldridge/">Instagram</a></li>
		<li><a href="https://twitter.com/MajorTomLDN">Twitter</a></li>
		<li><a href="https://github.com/TeldridgeLDN">Github</a></li>
	</ul>			
</div>
	</div> -->
<!-- <div class="footer">
		<p class="small-text">Handcoded in HTML / CSS with font-family Spectral used.</p>
	</div> -->
<!-- </body> -->
<!-- </html> -->