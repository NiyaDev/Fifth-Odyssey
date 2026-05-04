
### v0.1: The First Landing
#### Map changes
- Core regions of North America

#### Buildings
- Basic administration
  - +10 food
  - -0.5 prosperity
  - Destroyed after food in province is > +10 monthly
- The Library of Elysium (Event allowed)
  - +Literacy for all?
  - +1 Renaissance
  - ???
- The Great Cothon (Event allowed)
  - Trade capacity
  - ???
- The Collisseum (Event allowed)
  - ???

#### Starting
##### Priviliges
###### Tribes
- Allow Gatherings
- Native Communities
- Protected Tribal Faith
- Respected Tribal Traditions
- Tribal Land rights

#### Events

#### Mission-like Events
- Get maps of Illysio
  - NOTES: Even though they are weird, I want to integrate Societies of Pops into the mod
  - OPTION: Ask for maps from neighbors
    - Trigger: Doeg opinion > +100
    - Free maps
  - OPTION: Lead a campaign
    - Doeg, Piscataway, Nentego, Accawmacke, Rappahannock, Tsenacommacah, Nansemond, and Nottoway -100 opinion
    - Tribes -20 satisfaction
- Revocation of Native rights:
  - Trigger: All society of pops within territory -100 or less opinion
  - Remove Native Communities
- Subjegation of the Natives:
  - Trigger
    - Revocation of Native Rights
    - Less than 3 privilidges
- Integration of Natives:
  - Trigger: All society of pops within territory +100 or more opinion
  - Swap Native Communities with Native Integration

#### Priviliges
- No X presence:
  - Can i just disable nobles, clergy, and burghers for a little?
  - -100% Power? Maybe more?
  - 0% satisfaction
  - -1000? expected in provinces?
- Native Communities:
  - 10% satisfaction
  - 100% power
  - Block Tribesmen Promotion
  - Assimilation of Tribesmen blocked
- Native Integration:
  - 10% satisfaction
  - 100% power

#### Estates
- Romanyoti-led estate? Maybe thats a thing for another version?

#### Situations
##### The Fifth Oddyssey
###### Variables
- Money
- Money per month (mpm)
- Pops
  - 80% Peasants
  -  8% Laborers
  -  5% Burghers
  -  5% Clergy
  -  2% Nobles
- Slaves
- Different cultures
  - 85% Peasants
  - 10% Laborers
  -  5% Burghers
- Ships
- Knowledge
- Greek Silk
- Horses

###### Actions
- Allow Nobles
  - Nobles start in colony
- Bring in Nobles
  - +50% Noble strength per click
  - +1g per month per click

- Allow Clergy
  - Clergy start in colony
  - Resistance to Hellenistic conversion
- Bring in Clergy
  - Clergy start in colony
  - +50%  Clergy power per click
  - 0.5g per month per click

- Allow Burghers
  - Burghers start in colony
- Bring in Burghers
  - +50% Burghers strength per click
  - +1g per month per click

- Bring in Commoners
  - +50% Commoners strength per click
  - +additional peasants/laborers/soldiers in fleet

- Commission Shipwright
  - Gain ships

- Rent ships out to traders
  - Gain mpm per ship rented

- Leave:
  - Start the leaving event chain
  - Doesn't activate automatically, but more bad events happen the longer you wait

###### Events / Chains
- **Important**
  - Buy old books and scrolls from venetians who destroyed The Great Library
    - Potentially gives Greek Fire, Renaissance, Aquaducts, etc
  - Steal Silk from the empire
    - Once a basic economy is born, RGO in capital changes to Illysian Silk
  - Buy horses from Cossack breeders
    - A province will have Horses in the new world eventually
    - Start with horses advances
- **Good**
  - Commoners abandon lands to join journey (+pops)
  - Lesser nobles offer money and serfs to join (+money/+pops)
  - Burghers offer wealth and ships to join (+money/+ships)
  - Greeks from Frankokratia want freedom (+pops)
  - Romanyoti offer money for joining and religious freedom (+money/+diffpops)
    - Can only happen if Clergy not invited
  - Romanyoti worried about influence of clergy and back out (-diffpops)
  - Bank of Bardy/Peruzzi approached for loan (+money/-mpm)
  - Rented ships get attacked, but manage to survive and capture enemy ships (+ships)
    - Only at war
  - Rented ships get attacked by North African Pirates
    - CHOICE: Keep pirates as slaves, keep ships, release and direct them to harrass enemies
- **Bad**
  - Rented ships get attacked, lose some (-ships)
    - Only at war
  - Rented ships get attacked by North African Pirates (-ships)
  - Ships need repairs after disuse (-money) 3+ years
  - Nobles/Burghers/Clergy want their money back (-mpm) 3+ years
  - Unrest among participants (-people) 3+ years
  - Crackdown on exodus (-everything) 5+ years

