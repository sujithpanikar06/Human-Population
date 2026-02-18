Here is a set of colorful flashcards created from the provided CSV file. They are designed for easy and engaging studying.
<style>
.flashcard-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  padding: 20px;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: #f4f7fb;
}

.flashcard {
  width: 300px;
  height: 200px;
  perspective: 1000px;
  cursor: pointer;
}

.flashcard-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.6s;
  transform-style: preserve-3d;
  box-shadow: 0 8px 16px rgba(0,0,0,0.1);
  border-radius: 15px;
}

.flashcard:hover .flashcard-inner {
  transform: rotateY(180deg);
}

.flashcard-front, .flashcard-back {
  position: absolute;
  width: 100%;
  height: 100%;
  backface-visibility: hidden;
  border-radius: 15px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 15px;
  box-sizing: border-box;
  font-weight: 500;
  line-height: 1.5;
  word-wrap: break-word;
}

/* Colorful Front Styles */
.flashcard-front {
  background: linear-gradient(145deg, #6a5acd, #8a6de9); /* Slate Blue */
  color: white;
  border: 2px solid #f0e68c;
}

.flashcard-front.term-1 { background: linear-gradient(145deg, #ff6b6b, #ee5a5a); } /* Coral */
.flashcard-front.term-2 { background: linear-gradient(145deg, #4ecdc4, #3ab4ad); } /* Turquoise */
.flashcard-front.term-3 { background: linear-gradient(145deg, #ffe66d, #f3d64b); color: #2c3e50; } /* Mustard */
.flashcard-front.term-4 { background: linear-gradient(145deg, #c77dff, #b05eff); } /* Lavender */
.flashcard-front.term-5 { background: linear-gradient(145deg, #ffb347, #ff9f1c); } /* Orange */
.flashcard-front.term-6 { background: linear-gradient(145deg, #a2d6f9, #7ec8ff); color: #1e3c5c; } /* Light Blue */
.flashcard-front.term-7 { background: linear-gradient(145deg, #f7b2b2, #f28b8b); } /* Pink */
.flashcard-front.term-8 { background: linear-gradient(145deg, #b8e0d2, #a1d6c2); color: #1d4e3d; } /* Mint */
.flashcard-front.term-9 { background: linear-gradient(145deg, #d9bf77, #ccaa55); color: #2a3d1f; } /* Khaki */
.flashcard-front.term-10 { background: linear-gradient(145deg, #b48c9c, #a57386); } /* Mauve */
.flashcard-front.term-11 { background: linear-gradient(145deg, #8989ff, #6c6cf0); } /* Periwinkle */
.flashcard-front.term-12 { background: linear-gradient(145deg, #79c9a2, #5bbd89); } /* Seafoam */
.flashcard-front.term-13 { background: linear-gradient(145deg, #edc49b, #e7b374); color: #4e3022; } /* Peach */
.flashcard-front.term-14 { background: linear-gradient(145deg, #c0a0e0, #ac85d4); } /* Wisteria */

/* Back Style */
.flashcard-back {
  background: #f9f9f9;
  color: #2c3e50;
  transform: rotateY(180deg);
  border: 2px solid #3498db;
  font-size: 0.95em;
  text-align: center;
  box-shadow: inset 0 0 10px rgba(52,152,219,0.1);
}

.flashcard-back strong {
  color: #e67e22;
  margin-bottom: 10px;
  font-size: 1.1em;
  display: block;
}

/* Small note for card count */
.card-note {
  width: 100%;
  text-align: center;
  color: #7f8c8d;
  margin-top: 20px;
  font-size: 0.9em;
}
</style>

<div class="flashcard-container">
<!-- Card 1 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-1">What is the term for the study of human population size, density, distribution, movement, and birth and death rates?</div>
    <div class="flashcard-back"><strong>Answer:</strong> Demography</div>
  </div>
</div>
<!-- Card 2 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-2">Historically, how was the human population size characterized until recent times?</div>
    <div class="flashcard-back"><strong>Answer:</strong> It remained relatively stable for thousands of years.</div>
  </div>
</div>
<!-- Card 3 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-3">What significant event in the $1300$s killed an estimated one-third of Europe's population?</div>
    <div class="flashcard-back"><strong>Answer:</strong> The bubonic plague</div>
  </div>
</div>
<!-- Card 4 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-4">In what year did the human population first reach an estimated $1$ billion people?</div>
    <div class="flashcard-back"><strong>Answer:</strong> $1804$</div>
  </div>
</div>
<!-- Card 5 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-5">What was the estimated size of the human population in $1999$?</div>
    <div class="flashcard-back"><strong>Answer:</strong> $6$ billion people</div>
  </div>
</div>
<!-- Card 6 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-6">Approximately how many people are currently added to the world population annually?</div>
    <div class="flashcard-back"><strong>Answer:</strong> $70$ million people</div>
  </div>
</div>
<!-- Card 7 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-7">Based on current growth rates, in approximately how many years is the world's population expected to double?</div>
    <div class="flashcard-back"><strong>Answer:</strong> $53$ years</div>
  </div>
</div>
<!-- Card 8 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-8">Term/Definition: Carrying capacity</div>
    <div class="flashcard-back"><strong>Answer:</strong> The maximum number of individuals in a species that an environment can support for the long term.</div>
  </div>
</div>
<!-- Card 9 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-9">How have humans historically altered the environment to change its carrying capacity?</div>
    <div class="flashcard-back"><strong>Answer:</strong> Through agriculture and the domestication of animals.</div>
  </div>
</div>
<!-- Card 10 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-10">What specific technological advance reduced human deaths from parasites and disease?</div>
    <div class="flashcard-back"><strong>Answer:</strong> Medicine</div>
  </div>
</div>
<!-- Card 11 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-11">How did improvements in shelter affect the human survival rate?</div>
    <div class="flashcard-back"><strong>Answer:</strong> They made humans less vulnerable to climatic impacts.</div>
  </div>
</div>
<!-- Card 12 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-12">What is the current trend in the human population growth rate?</div>
    <div class="flashcard-back"><strong>Answer:</strong> The rate of growth is slowing down.</div>
  </div>
</div>
<!-- Card 13 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-13">In which year did the human population growth rate reach its peak at over $2.2\%$?</div>
    <div class="flashcard-back"><strong>Answer:</strong> $1962$</div>
  </div>
</div>
<!-- Card 14 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-14">What major event caused a sharp dip in human population growth in the $1960$s?</div>
    <div class="flashcard-back"><strong>Answer:</strong> A famine in China that killed about $60$ million people.</div>
  </div>
</div>
<!-- Card 15 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-1">By $2003$, the percent increase in human population growth had dropped to what approximate value?</div>
    <div class="flashcard-back"><strong>Answer:</strong> $1.2\%$</div>
  </div>
</div>
<!-- Card 16 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-2">What is the projected overall population growth rate by the year $2050$?</div>
    <div class="flashcard-back"><strong>Answer:</strong> Below $0.6\%$</div>
  </div>
</div>
<!-- Card 17 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-3">Identify two primary factors contributing to the decline in the human population growth rate.</div>
    <div class="flashcard-back"><strong>Answer:</strong> Diseases such as AIDS and voluntary population control.</div>
  </div>
</div>
<!-- Card 18 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-4">What is a 'demographic transition'?</div>
    <div class="flashcard-back"><strong>Answer:</strong> A change in a population from high birth and death rates to low birth and death rates.</div>
  </div>
</div>
<!-- Card 19 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-5">What defines an 'industrially developed country' in terms of population dynamics?</div>
    <div class="flashcard-back"><strong>Answer:</strong> A country with advanced technology and a high standard of living.</div>
  </div>
</div>
<!-- Card 20 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-6">How does a 'developing country' differ from an industrially developed one?</div>
    <div class="flashcard-back"><strong>Answer:</strong> It has a relatively low level of technological capabilities and a low standard of living.</div>
  </div>
</div>
<!-- Card 21 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-7">According to $2005$ data, what was the population growth rate of the United States?</div>
    <div class="flashcard-back"><strong>Answer:</strong> $0.92\%$</div>
  </div>
</div>
<!-- Card 22 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-8">According to $2005$ data, what was the population growth rate of Honduras?</div>
    <div class="flashcard-back"><strong>Answer:</strong> $2.16\%$</div>
  </div>
</div>
<!-- Card 23 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-9">Between now and $2050$, how many people are developing countries expected to add to the world population compared to industrially developed countries?</div>
    <div class="flashcard-back"><strong>Answer:</strong> $73$ million vs. $3$ million</div>
  </div>
</div>
<!-- Card 24 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-10">Which country is expected to see its population expand from $12$ to $53$ million by $2050$?</div>
    <div class="flashcard-back"><strong>Answer:</strong> Niger</div>
  </div>
</div>
<!-- Card 25 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-11">Which industrially developed country is expected to see a population decline from $8$ million to $5$ million by $2050$?</div>
    <div class="flashcard-back"><strong>Answer:</strong> Bulgaria</div>
  </div>
</div>
<!-- Card 26 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-12">Under what condition does 'zero population growth' (ZPG) occur?</div>
    <div class="flashcard-back"><strong>Answer:</strong> When the birthrate equals the death rate.</div>
  </div>
</div>
<!-- Card 27 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-13">What is the projected timeframe for the world to reach zero population growth?</div>
    <div class="flashcard-back"><strong>Answer:</strong> Between $2020$ and $2029$</div>
  </div>
</div>
<!-- Card 28 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-14">What change occurs to a population's age structure once it reaches zero population growth?</div>
    <div class="flashcard-back"><strong>Answer:</strong> The numbers at pre-reproductive, reproductive, and post-reproductive ages become approximately equal.</div>
  </div>
</div>
<!-- Card 29 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-1">Term/Definition: Age structure</div>
    <div class="flashcard-back"><strong>Answer:</strong> The number of males and females in the pre-reproductive, reproductive, and post-reproductive age groups.</div>
  </div>
</div>
<!-- Card 30 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-2">What age range is considered the 'reproductive stage' for humans in demography?</div>
    <div class="flashcard-back"><strong>Answer:</strong> $20$ to $44$ years</div>
  </div>
</div>
<!-- Card 31 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-3">Humans are considered to be in the 'pre-reproductive stage' before what age?</div>
    <div class="flashcard-back"><strong>Answer:</strong> Age $20$</div>
  </div>
</div>
<!-- Card 32 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-4">What age range defines the 'post-reproductive stage' in human age structure diagrams?</div>
    <div class="flashcard-back"><strong>Answer:</strong> After age $44$</div>
  </div>
</div>
<!-- Card 33 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-5">What is the typical shape of an age structure diagram for a rapidly growing country?</div>
    <div class="flashcard-back"><strong>Answer:</strong> A broad-based pyramid shape.</div>
  </div>
</div>
<!-- Card 34 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-6">What does the age structure diagram of a country with negative growth look like?</div>
    <div class="flashcard-back"><strong>Answer:</strong> It has a narrower base than its middle or top sections.</div>
  </div>
</div>
<!-- Card 35 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-7">Which country type's age structure does the current world human population most closely resemble?</div>
    <div class="flashcard-back"><strong>Answer:</strong> A rapidly growing country</div>
  </div>
</div>
<!-- Card 36 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-8">What are the predicted consequences if human population growth continues to overcrowding?</div>
    <div class="flashcard-back"><strong>Answer:</strong> Widespread disease and starvation.</div>
  </div>
</div>
<!-- Card 37 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-9">How does resource consumption per person typically differ between developed and developing countries?</div>
    <div class="flashcard-back"><strong>Answer:</strong> Individuals in industrially developed countries use far more resources.</div>
  </div>
</div>
<!-- Card 38 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-10">What does the land requirement calculation for supporting a person include besides food production?</div>
    <div class="flashcard-back"><strong>Answer:</strong> Forest products, housing, and land to absorb the $CO_{2}$ produced by burning fossil fuels.</div>
  </div>
</div>
<!-- Card 39 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-11">Why is the increasing development of countries like India significant for Earth's carrying capacity?</div>
    <div class="flashcard-back"><strong>Answer:</strong> They are adding more people while simultaneously increasing their per-capita resource use.</div>
  </div>
</div>
<!-- Card 40 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-12">From which Greek word does the prefix 'demo-' in demography originate, and what does it mean?</div>
    <div class="flashcard-back"><strong>Answer:</strong> It comes from *demos*, meaning people.</div>
  </div>
</div>
<!-- Card 41 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-13">From which French word does the suffix '-ography' in demography originate, and what does it mean?</div>
    <div class="flashcard-back"><strong>Answer:</strong> It comes from *graphie*, meaning writing.</div>
  </div>
</div>
<!-- Card 42 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-14">What was the core prediction of Thomas Malthus's $1798$ essay on human population?</div>
    <div class="flashcard-back"><strong>Answer:</strong> Exponential population growth would lead to famine, poverty, and war.</div>
  </div>
</div>
<!-- Card 43 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-1">How many people are estimated to have survived the global climate changes from the Toba supervolcano eruption in $69,000$ BC?</div>
    <div class="flashcard-back"><strong>Answer:</strong> Between $15,000$ and $40,000$ people</div>
  </div>
</div>
<!-- Card 44 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-2">Which historical era led to a dramatic population explosion around $1800$?</div>
    <div class="flashcard-back"><strong>Answer:</strong> The Industrial Revolution</div>
  </div>
</div>
<!-- Card 45 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-3">How many people were killed by the Spanish Flu in $1918$?</div>
    <div class="flashcard-back"><strong>Answer:</strong> Between $20$ and $40$ million people</div>
  </div>
</div>
<!-- Card 46 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-4">What was the estimated death toll of World War II ($1939$-$1945$)?</div>
    <div class="flashcard-back"><strong>Answer:</strong> Approximately $58$ million people</div>
  </div>
</div>
<!-- Card 47 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-5">In $2004$, how many people were estimated to have died from AIDS in sub-Saharan Africa?</div>
    <div class="flashcard-back"><strong>Answer:</strong> $2.3$ million people</div>
  </div>
</div>
<!-- Card 48 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-6">According to Table 4.1, which country has a population growth rate of $0.0\%$?</div>
    <div class="flashcard-back"><strong>Answer:</strong> Germany</div>
  </div>
</div>
<!-- Card 49 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-7">According to Table 4.1, which country has the highest population growth rate listed at $4.77\%$?</div>
    <div class="flashcard-back"><strong>Answer:</strong> Afghanistan</div>
  </div>
</div>
<!-- Card 50 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-8">According to Table 4.1, what is the population growth rate for Bulgaria?</div>
    <div class="flashcard-back"><strong>Answer:</strong> $-0.89\%$</div>
  </div>
</div>
<!-- Card 51 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-9">According to Table 4.1, what is the population growth rate for Kenya?</div>
    <div class="flashcard-back"><strong>Answer:</strong> $2.56\%$</div>
  </div>
</div>
<!-- Card 52 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-10">What is the primary role of a demographer?</div>
    <div class="flashcard-back"><strong>Answer:</strong> To study human population dynamics like growth rates, density, and distribution.</div>
  </div>
</div>
<!-- Card 53 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-11">The demographic transition in the United States shifted from high birth and death rates to _____.</div>
    <div class="flashcard-back"><strong>Answer:</strong> Low birth and death rates</div>
  </div>
</div>
<!-- Card 54 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-12">Process/Sequence: What happens to human survival chances when sanitation and medical care improve?</div>
    <div class="flashcard-back"><strong>Answer:</strong> They increase by reducing deaths from disease.</div>
  </div>
</div>
<!-- Card 55 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-13">In the context of age structure, the 'reproductive stage' spans what years?</div>
    <div class="flashcard-back"><strong>Answer:</strong> Ages $20$ through $44$</div>
  </div>
</div>
<!-- Card 56 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-14">If a country has a growth rate of $2.63\%$, which representative growth category from Figure 4.14 does it fit?</div>
    <div class="flashcard-back"><strong>Answer:</strong> Rapid growth</div>
  </div>
</div>
<!-- Card 57 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-1">Concept: Resource Usage Observation: Industrially developed countries like the United States use more land area per person than developing countries like India.</div>
    <div class="flashcard-back"><strong>Answer:</strong> (Observation noted)</div>
  </div>
</div>
<!-- Card 58 -->
<div class="flashcard">
  <div class="flashcard-inner">
    <div class="flashcard-front term-2">What is the relationship between voluntary population control and global growth rates?</div>
    <div class="flashcard-back"><strong>Answer:</strong> Voluntary control through family planning helps reduce the overall population growth rate.</div>
  </div>
</div>
</div>
<div class="card-note">
  🌟 Hover over cards to flip. 58 colorful flashcards generated from your data. 🌟
</div>
