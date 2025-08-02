<script>
  import Header from "./Header/Header.svelte";
  import Headline from "./Header/Headline.svelte";
  import Bump from "./Charts/Bump.svelte";
  import Line from "./Charts/Line.svelte";
  import Polarity from "./Charts/Polarity.svelte";
  import Bubble1 from "./Charts/Bubble1.svelte";
  import Bubble2 from "./Charts/Bubble2.svelte";
  import Ridge from "./Charts/Ridge.svelte";
</script>

<title>When Women Make Headlines</title>

<body>
  <div>
    <Header></Header>
    <Headline></Headline>
  </div>
  <p class="description">
    <span class="padded-dropcap">T</span>oday, research has suggested that women
    are significantly less likely to make the news compared to men. In the
    <a
      href="https://whomakesthenews.org/wp-content/uploads/2021/07/GMMP2020.ENG_.FINAL20210713.pdf"
      >most recent report</a
    >
    published by the
    <a
      href="https://waccglobal.org/our-work/global-media-monitoring-project-gmmp"
      >Global Media Monitoring Project (GMMP)</a
    >, the largest and longest running research on gender in the world’s news
    media, women were found to make up just 24% of news subjects and sources
    reported. According to this report, this number has not changed since 2010.
  </p>

  <p class="description">
    In the context of news, headlines <a
      href="https://thereader.mitpress.mit.edu/headlines-journalism"
    >
      introduce, frame and contextualize</a
    >
    a news story. Furthermore, research within the fields of educational and experimental
    psychology has demonstrated that news headlines can have a
    <a
      href="https://www.newyorker.com/science/maria-konnikova/headlines-change-way-think"
      >disproportionate impact on the reader’s mind</a
    >, and that misleading headlines
    <a href="https://psycnet.apa.org/record/2014-44652-001"
      >can bias readers toward a specific interpretation</a
    >.
  </p>
  <p class="description">
    So, if women are underrepresented in the news to begin with, what does it
    look like when women <i>do</i> make headlines? And how have headlines about women
    changed over time?
  </p>
  <p class="description">
    To explore these questions, we have visualized the language used in
    women-centered headlines and how this language has (or has not) changed over
    time. Using keywords associated with the word “woman” (like girl, mother and
    lady), we collected and analyzed 382,139 headlines published between 2005
    and 2021 by the top English-language news publications and news agencies in
    four countries: The United States of America (US), India, South Africa, and
    the United Kingdom (UK). A total of 186 publications were considered (i.e.
    24 publications in South Africa, 51 publications in India, 57 publications
    in the UK, and 54 publications in the US).
  </p>

  <div class="chart">
    <Bump></Bump>
  </div>
  <div>
    <h2 class="sectionHeader">Headlines about women are more sensational</h2>
  </div>
  <div>
    <p class="description">
      <span class="padded-dropcap">S</span>ensationalism is an editorial tactic.
      The words in a sensational headline are carefully chosen for the purpose
      of enticing the reader. For example, a story titled “<a
        href="https://news.sky.com/story/woman-28-charged-after-stabbing-in-barnsley-town-centre-11494085"
        >Woman, 28, charged after 'stabbing' in Barnsley town centre</a
      >” could potentially garner a semi-conscious glance from its reader while
      one titled “<a
        href="https://www.express.co.uk/news/uk/1014846/barnsley-stabbing-woman-market-trader-hero-south-yorkshire-uk-knives-police"
        >Woman screamed 'KILL KILL KILL!' while repeatedly stabbing a man in
        Barnsley market attack</a
      >” could be more likely to capture the reader’s attention.
    </p>
    <p class="description">
      But, is this sensationalism more or less prominent in women-focused
      headlines? To find out, we used sentiment analysis, a natural language
      processing technique used to quantify emotion in text, to rate every
      headline with a polarity score. A headline with either extremely positive
      or extremely negative sentiment is, for our analysis, considered
      sensational, and hence it is given a higher polarity score. As it turns
      out, not only is sensationalism on the rise, but it has also been
      consistently higher in headlines with keywords associated with women, as
      opposed to headlines about other topics.
    </p>
  </div>

  <div class="chart">
    <Line></Line>
  </div>

  <div>
    <p class="description">
      How do different news outlets compare to each other? In the chart below,
      the absolute and percent difference in polarity scores between headlines
      about women and all other headlines is displayed for a representative
      sample of the news outlets analyzed.
    </p>
  </div>

  <div class="chart">
    <Polarity></Polarity>
  </div>

  <p class="description">
    Outlets that sensationalize headlines about women less, like Nature and
    FiveThirtyEight do not regularly deal with everyday news but go deeper into
    significant topical trends.
  </p>

  <h2 class="sectionHeader">Here’s how polarizing headlines are</h2>
  <p class="description">
    <span class="padded-dropcap">U</span>sing data from
    <a href="https://www.similarweb.com/top-websites">SimilarWeb</a> we then tied
    the monthly viewership of every publication to the average polarity score of
    their women-centered headlines. While all outlets sensationalize their news to
    some extent, news outlets on the left end of the spectrum (i.e. less sensational)
    tend to be the ones who focus on either financial news, like Bloomberg in the
    United States and LiveMint in India, or on tech news, such as TechRadar and CNET.
    Nature, a predominantly scientific publication, is the least sensational but
    it also has a more limited reach.
  </p>
  <p class="description">
    BBC and The New York Times are the largest publications with the least
    sensational headlines compared to the Daily Mail, Huffington Post, Fox News
    or Aaj Tak who publish more shock value headlines.
  </p>
  <div class="chart">
    <Bubble1></Bubble1>
  </div>

  <h2 class="sectionHeader">Here’s how biased headlines are</h2>
  <p class="description">
    <span class="padded-dropcap">W</span>hile the theme of crime and violence
    got us delving into how sensational women-centered headlines are, the theme
    of gendered language led to the idea of measuring bias.
  </p>
  <p class="description">
    Explicit use of gendered language in English — words like “actress,”
    “congresswoman” or “landlady” — emphasizes the gender of the subject when
    there is no need to do so. Research from <a
      href="https://aclanthology.org/W19-3802">Yasmeen Hitti et al.</a
    > has suggested that both gendered language and words that reinforce societal
    and behavioral stereotypes, such as “beautiful,” “emotional,” “supportive” or
    “dramatic,” add to the bias of a sentence. Using their research methodology,
    we attributed a bias score to each headline.
  </p>
  <p class="description">
    For example, the headline that reads “<a
      href="https://www.mirror.co.uk/news/real-life-stories/daughter-emotional-meeting-woman-given-6522901"
      >Daughter in emotional meeting with woman given life back by selfless
      courage of her dead mother</a
    >” gets a higher bias score than the headline that reads “<a
      href="https://www.washingtonpost.com/blogs/she-the-people/post/hillary-clinton-speaks-out-for-the-same-american-values-upheld-in-retracted-embassy-statement/2012/09/13/ccbf05f2-fdd6-11e1-b153-218509a954e1_blog.html"
      >Hillary Clinton speaks out for the same American values upheld in
      retracted embassy statement</a
    >.” In the chart below, we visualize this bias index for each publication.
    In contrast to our results for polarity, there is a greater variance in bias
    scores across publications. The Daily Mail scores the highest while the BBC
    and ESPN are among those who score the lowest.
  </p>
  <div class="chart">
    <Bubble2></Bubble2>
  </div>

  <h2 class="sectionHeader">
    Headline trends: Less gendered language. More empowering words.
  </h2>
  <p class="description">
    <span class="padded-dropcap">I</span>n this final chart, we have visualized
    how the words used in headlines about women have changed over time.
  </p>
  <p class="description">
    Among other trends that can be observed from this chart, we found that while
    the use of many gendered words (e.g.“sexy,” “fat,” “housewife” or “gossip”)
    has faded out over time, the use of empowering words has increased over time
    (e.g. “founder,” “activist,” “leader” or “appoint”). Other words (e.g.
    “death,” “hurt,” and “drama”) have instead stood the test of time, as their
    use has remained consistent since 2005.
  </p>
  <p class="description">
    For each word’s ebb or flow, we tried to find a “remember when” memory to
    explain it. Remember when Caitlyn Jenner came out as transgender? That was
    part of a wave of increased trans visibility that helps to explain why
    “transgender” shot up in 2015. Remember when the #MeToo movement took off?
    That adds context to the sharp rise of “harassment” in 2017, and the sharp
    rise of the word “equality” in recent years. Such world events are arranged
    as bubbles in the timeline above the chart.
  </p>
  <p class="description">
    If you see an interesting rise, hover over one such bubble to see if you can
    find a world event that can explain it. If you think that we’ve missed out
    on an important event in your part of the world, let us know.
  </p>
  <div class="chart">
    <Ridge></Ridge>
  </div>

  <p class="description">
    The story of when women make headlines is, like most stories about people,
    full of contradictions. It is violent, sensational, biased, hopeful and
    empowering although not all of them in equal measure. This visual essay
    suggests that headlines used to report women-centered news can be biased and
    can reinforce existing stereotypes. These headlines also tend to be more
    sensational than for other news topics, and they tend to represent women in
    situations of crime and violence. As a growing <a
      href="https://edizionicafoscari.unive.it/media/pdf/books/978-88-6969-479-0/978-88-6969-479-0-ch-12.pdf"
      >body</a
    >
    of
    <a
      href="https://journals.sagepub.com/doi/full/10.1177/0095798416665967?casa_token=1YYGkNHNIEgAAAAA%3AagaE2Oo3-JtPupya7SD3_p8c-QI4GSQVks1rBFFSoIiHc7GCxLlbn6exGZMo8aBe2vGTKD6YUSDO"
      >research</a
    >
    has already
    <a
      href="https://onlinelibrary.wiley.com/doi/full/10.1111/j.1559-1816.2011.00781.x?casa_token=HptwkBvWYIcAAAAA%3ANAuO998zBCAbtje5eKPIqe1RMASbx0F6dsRHCpz2FaONq0Dl0LsPLkPEUF4ZPLt-Nb4RxByWqnsGZIU"
      >indicated</a
    >, this could imply that women are not only underrepresented in the news but
    also <i>mis</i>-represented.
  </p>
  <p class="description">
    Nonetheless, this visual essay also suggests that some progress has been
    made. Over time, we saw that the use of many empowering words has risen
    sharply while the use of some gender stereotypes has plummeted. Let’s hope
    this trend continues and, in the meantime, enjoy our news with a little
    grain of salt. After all, when women make headlines, no words, sensational
    or not, biased or not, can truly explain the nuance behind the event because
    words can only approximate.
  </p>
</body>

<style>
  body {
    background-color: #fdf8f0;
    -webkit-font-smoothing: antialiased;
    width: auto;
    font-family: "Domine", serif;
  }

  a {
    text-decoration: underline;
    text-underline-offset: 5px;
  }
  a:hover {
    text-decoration-color: #e76b2d;
  }

  .chart {
    display: flex;
    width: auto;
    justify-content: center;
    padding: 25px;
  }

  .sectionHeader {
    font-family: "Barlow Condensed";
    font-size: 48px;
    text-align: center;
    font-style: italic;
    font-weight: 900;
    line-height: 38.4px;
    text-decoration: rgb(40, 40, 40);
    text-transform: uppercase;
    color: #282828;
    height: 39.4px;
    width: auto;
    padding: 0px;
    border-bottom: 1px solid rgb(40, 40, 40);
    transform: matrix(1, 0, -0.176327, 1, 0, 0);
  }

  .description {
    font-family: "Domine", serif;
    font-size: 18px;
    letter-spacing: -0.01em;
    font-weight: 300;
    line-height: 1.65;
    text-align: justify;
    padding: 1rem 1rem;
    max-width: 640px;
    margin: 0 auto;
    color: #282828;
  }

  .padded-dropcap {
    padding: 1rem 1.25rem 1rem 1rem;
    margin: 1rem 1.25rem -0.5rem 0.25rem;
    font-family: "Barlow Condensed", sans-serif;
    font-size: 64px;
    float: left;
    box-sizing: border-box;
    position: relative;
    top: -0.1em;
    font-weight: 900;
    border: 1px solid #282828;
    line-height: 0.8;
    color: #282828;
    float: left;
    transform: skew(-10deg, 0);
    background: #f2c5d3;
  }
</style>
