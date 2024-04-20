In-depth explanations and usage guides are in the comments of each filter file.

- **Analyzer:** Prints a full analysis of a seed. Vouchers and bosses to be implemented.
	- It's highly recommended to run this with -n 1 to only look at a single seed.
	- Also recommended to customize the filter itself to your needs. (deck type, stake, maximum ante to search)
- **Bad Seeds:** Seeds with very little rare uncommon jokers in first 4 ante.
- **Buggy Erratic:** Searches for seeds with glitched erratic decks.
- **Buggy Seeds**: Searches for glitched seeds.
- **Cavendish:** Searches for a seed that has a Gros Michel in the first shop (or in the buffoon packs) followed by a Cavendish in the second shop (or in the buffoon packs).
- **Double Legendary:** Searches for a first ante with two packs that give legendary jokers
- **Emperor Fool:** Searches for Emperor-Fool Chains.
- **Erratic Flush Five:** Searches for an Erratic Deck seed with lots of an exact card.
	- Score output is the number of card matches. Increase the cutoff score to raise the minimum number of cards.
- **Erratic Ranks:** Searches for an Erratic Deck seed with lots of a rank.
	- Score output is the number of rank matches. Increase the cutoff score to raise the minimum number of cards.
- **Erratic Suits:** Searches for an Erratic Deck seed with lots of a type of suit.
	- Score output is the number of suit matches. Increase the cutoff score to raise the minimum number of cards.
- **Eternal:** Seeds with two eternal jokers in the first shop.
- **Four Deadly Jokers:** Searches for a first shop buffoon pack with the four jokers that give increased mult to suits.
- **High Score Demo:** Searches for a seed with a good setup for high score world record runs.
	- Only works for demo version.
- **Legendary Skip:** Searches for a Legendary joker from an arcana pack skip in ante 1.
- **Longest Joker Name:** Searches for seeds with a Polychrome Perishable Rental Delayed Gratification in the first shop.
	- Requires Gold Stake.
- **Low Percent:** Searches for a seed that can be beaten with 6 hands and 0 discards.
- **Max Cash Ante 1:** Maximum cash out possible in Ante 1.
- **Most Jokers:** Finds seeds with Perkeo, Ankh and Ectoplasm as consumables from shop. Used for most jokers WR (with eternal jokers).
- **Perkeo Analyzer:** Print all consumable generators queues of a seed (Seals, Judgement, Wraith, etc.)
	- The name has nothing to do with searching Perkeo.
- **Perkeo Observatory:** Searches for seeds with Observatory in ante 2 and Perkeo in ante 1 or 2.
- **Purchaseless:** Searches for seeds with a Top Up tag in ante 2 that gives a Superposition joker that then gives a Judgement.
	- Recommended to use a score cutoff of 2.
	- If the score is greater than 900, the judgement gives either a Bull, Green Joker, or Raised Fist.
- **Red Poly Glass:** Searches for seeds that have a Red Seal Polychrome Glass Card in the first shop.
- **Showman Emperor Fool:** Searches for seeds with Emperor->Fool/Emperor Chains with the help of Showman.
	- How to read result: 1020304
	- 1 -> longest chain
	- 2 -> showman appears ante 2 (in first 6 shop items or in a buffoon pack)
	- 3 -> emperor appears ante 3  (in first 6 shop items)
	- 4 -> best ante to use emperor
- **Speedrun Skipless:** Seeds with a Stuntman ante in 1 and Rocket or To The Moon in the next shop and Bull ante 5.
	- Score increments by 1 for each correct joker found.
	- Score is 999 if all 3 are met.
- **Speedrun:** Speedrunning seeds for Set Seed Skips.
	- The primary strategy utilized is going to be a single Bull carrying the run.
- **Straight Flushes:** Checks if the first two blinds of Ante 1 have straight flushes