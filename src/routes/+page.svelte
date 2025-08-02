<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Barlow+Condensed:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">

<h1>Recreation</h1>

    <style>
        :global(body) {
            background-color: #fdf8f0;
            font-family: 'Open Sans', sans-serif;
        }
        .chart {
        display: flex;
        justify-content: center;
      }
      .titleArt {
        text-align: center;
        margin: 20px;
      }
      .sectionHeader {
        font-family: "Barlow Condensed";
        font-size: 48px;
        font-style: italic;
        font-variant: normal;
        font-weight: 900;
        letter-spacing: normal;
        line-height: 38.4px;
        text-decoration: rgb(40, 40, 40);
        text-align: center;
        text-indent: 0px;
        text-transform: uppercase;
        white-space: normal;
        word-spacing: 0px;
        
        color: rgb(40, 40, 40);
        height: 39.4px;
        width: 1425px;
        border-top: 0px rgb(40, 40, 40);	
        border-right: 0px rgb(40, 40, 40);	
        border-bottom: 1px solid rgb(40, 40, 40);	
        border-left: 0px rgb(40, 40, 40);	
        margin: 96px auto 8px;	
        padding: 0px 16px;	
        
        position: static;	
        top: auto;	bottom: auto;	right: auto;	left: auto;	float: none;}
    </style>


    <link rel="stylesheet" href="/src/routes/%2Bpage.svelte.css">
<body>
  <div class="titleArt">
			<div class="titlewords">
				<h1 id="typedtext" class="title"><span>When</span> <span>Women</span> <span>Make</span> <span>Headlines</span>
				</h1>
			</div>
			<div class="titleCredits">
				<h2 class="subTitleArt">A visual essay about the (mis)representation of women in the news</h2>
				<p class="credits">By <a href="https://pudding.cool/author/leonardo-nicoletti" class="creditLink">​​Leonardo
						Nicoletti</a>
					and <a href="https://pudding.cool/author/sahiti-sarva" class="creditLink">Sahiti Sarva</a></p>
			</div>
            <section class="intro-section">
			<p class="description"><span class="padded-dropcap">T</span>oday, research has suggested that women are
				significantly less likely to make the news compared to men. In the <a href="https://whomakesthenews.org/wp-content/uploads/2021/07/GMMP2020.ENG_.FINAL20210713.pdf">most recent
					report</a> published by the <a href="https://waccglobal.org/our-work/global-media-monitoring-project-gmmp">Global Media Monitoring Project
				(GMMP)</a>, the largest and longest running research on gender in the world’s news media, women were found to
				make up just 24% of news subjects and sources reported. According to this report, this number has not changed
				since 2010.</p>
			<p class="description">In the context of news, headlines <a href="https://thereader.mitpress.mit.edu/headlines-journalism"> introduce, frame and contextualize</a> a news
				story. Furthermore, research within the fields of educational and experimental psychology has demonstrated that
				news headlines can have a <a href="https://www.newyorker.com/science/maria-konnikova/headlines-change-way-think">disproportionate impact on
					the reader’s mind</a>, and that misleading headlines <a href="https://psycnet.apa.org/record/2014-44652-001">can
					bias readers toward a specific interpretation</a>.</p>
			<p class="description">So, if women are underrepresented in the news to begin with, what does it look like when
				women <i>do</i> make headlines? And how have headlines about women changed over time?</p>
			<p class="description">To explore these questions, we have visualized the language used in women-centered
				headlines and how this language has (or has not) changed over time. Using keywords associated with the word
				“woman” (like girl, mother and lady), we collected and analyzed 382,139 headlines published between 2005 and
				2021 by the top English-language news publications and news agencies in four countries: The United States of
				America (US), India, South Africa, and the United Kingdom (UK). A total of 186 publications were considered
				(i.e. 24 publications in South Africa, 51 publications in India, 57 publications in the UK, and 54 publications
				in the US).</p>
		</section>


    <!-- bump chart -->
    <div class="chart">
      <div id="observablehq-c1-9f31247f"></div>
      <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@observablehq/inspector@5/dist/inspector.css">
      <script type="module">
      import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@5/dist/runtime.js";
      import define from "https://api.observablehq.com/d/30a84ebdc808c7ff@945.js?v=4";
      new Runtime().module(define, name => {
        if (name === "c1") return new Inspector(document.querySelector("#observablehq-c1-9f31247f"));
      });
      </script>
    </div>

    <section class="barbell-section">
			<div class="header">
				<h2 class="sectionHeader">Headlines about women are more sensational</h2>
			</div>
			<div id="sortLollipop">
				<p class="description"><span class="padded-dropcap">S</span>ensationalism is an editorial tactic. The words in a
					sensational headline are carefully chosen for the purpose of enticing the reader. For example, a story titled
					“<a href="https://news.sky.com/story/woman-28-charged-after-stabbing-in-barnsley-town-centre-11494085">Woman,
						28, charged after 'stabbing' in Barnsley town centre</a>” could potentially garner a semi-conscious glance
					from its reader while one titled “<a href="https://www.express.co.uk/news/uk/1014846/barnsley-stabbing-woman-market-trader-hero-south-yorkshire-uk-knives-police">Woman
						screamed 'KILL KILL KILL!' while repeatedly stabbing a man in Barnsley market attack</a>” could be more
					likely to capture the reader’s attention.</p>
				<p class="description">But, is this sensationalism more or less prominent in women-focused headlines? To find
					out, we used sentiment analysis, a natural language processing technique used to quantify emotion in text, to
					rate every headline with a polarity score. A headline with either extremely positive or extremely negative
					sentiment is, for our analysis, considered sensational, and hence it is given a higher polarity score. As it
					turns out, not only is sensationalism on the rise, but it has also been consistently higher in headlines with
					keywords associated with women, as opposed to headlines about other topics.</p>
			</div>

      <!-- Line chart -->
      <div class="chart">
      <div id="observablehq-viewof-svg-3e856917"></div>
      <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@observablehq/inspector@5/dist/inspector.css">
      <script type="module">
        import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@5/dist/runtime.js";
        import define from "https://api.observablehq.com/d/30a84ebdc808c7ff.js?v=4";
        new Runtime().module(define, name => {
      if (name === "viewof svg") return new Inspector(document.querySelector("#observablehq-viewof-svg-3e856917"));
      });
      </script>
      </div>
			
			<div id="sortLollipop">
				<p class="description">How do different news outlets compare to each other? In the chart below, the absolute and
					percent difference in polarity scores between headlines about women and all other headlines is displayed for a
					representative sample of the news outlets analyzed.</p>
			</div>



      <!-- polarity chart -->
       <div class="chart">
      <div id="observablehq-c3-2304ef6e"></div>
      <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@observablehq/inspector@5/dist/inspector.css">
      <script type="module">
      import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@5/dist/runtime.js";
      import define from "https://api.observablehq.com/d/30a84ebdc808c7ff@945.js?v=4";
      new Runtime().module(define, name => {
        if (name === "c3") return new Inspector(document.querySelector("#observablehq-c3-2304ef6e"));
      });
      </script></div>
      </section>

	<div class="header">
		<h2 class="sectionHeader">Here’s how polarizing headlines are</h2>
		<p class="description">Using data from SimilarWeb we then tied the monthly viewership of every publication to the average polarity score of their women-centered headlines. While all outlets sensationalize their news to some extent, news outlets on the left end of the spectrum (i.e. less sensational) tend to be the ones who focus on either financial news, like Bloomberg in the United States and LiveMint in India, or on tech news, such as TechRadar and CNET. 
        Nature, a predominantly scientific publication, is the least sensational but it also has a more limited reach. BBC and The New York Times are the largest publications with the least sensational headlines compared to the Daily Mail, Huffington Post, Fox News or Aaj Tak who publish more shock value headlines.</p>
  </div>

  <!-- bubble chart 1 -->
   <div class="chart">
  <div id="observablehq-c4a-4b8007c4"></div>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@observablehq/inspector@5/dist/inspector.css">
  <script type="module">
  import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@5/dist/runtime.js";
  import define from "https://api.observablehq.com/d/30a84ebdc808c7ff@792.js?v=4";
  new Runtime().module(define, name => {
    if (name === "c4a") return new Inspector(document.querySelector("#observablehq-c4a-4b8007c4"));
  });
  </script>
  </div>

  <div class="header">
	<h2 class="sectionHeader">Here’s how biased headlines are</h2>
	<p class="description">While the theme of crime and violence got us delving into how sensational women-centered headlines are, the theme of gendered language led to the idea of measuring bias.

Explicit use of gendered language in English — words like “actress,” “congresswoman” or “landlady” — emphasizes the gender of the subject when there is no need to do so. Research from Yasmeen Hitti et al. has suggested that both gendered language and words that reinforce societal and behavioral stereotypes, such as “beautiful,” “emotional,” “supportive” or “dramatic,” add to the bias of a sentence. Using their research methodology, we attributed a bias score to each headline.

For example, the headline that reads “Daughter in emotional meeting with woman given life back by selfless courage of her dead mother” gets a higher bias score than the headline that reads “Hillary Clinton speaks out for the same American values upheld in retracted embassy statement.” In the chart below, we visualize this bias index for each publication. In contrast to our results for polarity, there is a greater variance in bias scores across publications. The Daily Mail scores the highest while the BBC and ESPN are among those who score the lowest.

Go ahead, hover on the bubbles and see for yourself if you think these headlines are extremely gendered.</p>
  </div>

  <!-- bubble chart 2 -->
   <div class="chart">
   <div id="observablehq-c4b-f983bdaa"></div>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@observablehq/inspector@5/dist/inspector.css">
  <script type="module">
  import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@5/dist/runtime.js";
  import define from "https://api.observablehq.com/d/30a84ebdc808c7ff@792.js?v=4";
  new Runtime().module(define, name => {
    if (name === "c4b") return new Inspector(document.querySelector("#observablehq-c4b-f983bdaa"));
  });
  </script>
   </div>

    <div class="header">
	<h2 class="sectionHeader">Headline trends: Less gendered language. More empowering words.</h2>
	<p class="description">In this final chart, we have visualized how the words used in headlines about women have changed over time.

Among other trends that can be observed from this chart, we found that while the use of many gendered words (e.g.“sexy,” “fat,” “housewife” or “gossip”) has faded out over time, the use of empowering words has increased over time (e.g. “founder,” “activist,” “leader” or “appoint”). Other words (e.g. “death,” “hurt,” and “drama”) have instead stood the test of time, as their use has remained consistent since 2005.

For each word’s ebb or flow, we tried to find a “remember when” memory to explain it. Remember when Caitlyn Jenner came out as transgender? That was part of a wave of increased trans visibility that helps to explain why “transgender” shot up in 2015. Remember when the #MeToo movement took off? That adds context to the sharp rise of “harassment” in 2017, and the sharp rise of the word “equality” in recent years. Such world events are arranged as bubbles in the timeline above the chart.

If you see an interesting rise, hover over one such bubble to see if you can find a world event that can explain it. If you think that we’ve missed out on an important event in your part of the world, let us know.</p>
  </div>

  <!-- ridge chart -->
   <div class="chart">
  <svg style="height: 0; width: 0;">
  <linearGradient id="areaGradient" x1="0%" y1="0%" x2="0%" y2="100%"><stop offset="0%" stop-color="#f76e45"></stop><stop offset="90%" stop-color="#FEFAF1"></stop><stop offset="100%" stop-color="#FEFAF1"></stop></linearGradient>
  </svg>

  <div id="observablehq-c5-4b6a74de"></div>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@observablehq/inspector@5/dist/inspector.css">
  <script type="module">
  import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@5/dist/runtime.js";
  import define from "https://api.observablehq.com/d/30a84ebdc808c7ff@792.js?v=4";
  new Runtime().module(define, name => {
    if (name === "c5") return new Inspector(document.querySelector("#observablehq-c5-4b6a74de"));
  });
  </script>
  </div>

  	<p class="description">

The story of when women make headlines is, like most stories about people, full of contradictions. It is violent, sensational, biased, hopeful and empowering although not all of them in equal measure. This visual essay suggests that headlines used to report women-centered news can be biased and can reinforce existing stereotypes. These headlines also tend to be more sensational than for other news topics, and they tend to represent women in situations of crime and violence. As a growing body of research has already indicated, this could imply that women are not only underrepresented in the news but also mis-represented.

Nonetheless, this visual essay also suggests that some progress has been made. Over time, we saw that the use of many empowering words has risen sharply while the use of some gender stereotypes has plummeted. Let’s hope this trend continues and, in the meantime, enjoy our news with a little grain of salt. After all, when women make headlines, no words, sensational or not, biased or not, can truly explain the nuance behind the event because words can only approximate.
</p>
	</div>
</body>