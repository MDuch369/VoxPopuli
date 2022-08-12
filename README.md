##############################
# VoxPopuli Readme
# Mateusz Duchnowski
##############################

### Mod for Stellaris overhauling internal politics and governance of countries ###

current features:
- mandates are now using situations system
- resource prduction tracking - system that tracks your economy to see how it performs and base future mandates on this data

roadmap:
- overhaul mandates:
  - add more mandates
  - make mandates more appropriate to your situation (e.g. no more "build mining stations" mandate, when you have no place to build them on)
  - dynamic mandates (economic mandates base their goal on prior performance of your economy)
  - ? multistage mandates
  - ? allow partial completion of mandates
  - ? mandates provide bonuses when they are active
 
- overhaul elections:
  - replace vanilla election system with a more modabble one (most likely using the situation system)
  - option to change term length
  - option to set term limit
	- election results based on electorate ideollogy
	- election campaigns, letting the player influence the outcome
	- candidates belong to different factions and have their support during elections

  
- overhaul factions (make faction more important and impactful):
  - dynamic factions (factions try to actively influence your government/society instead of just being there and being (dis)content with it)
  - more faction types
  - more faction interactions
  - introduce a measure of how much a faction can influence a country
	- new ui for faction overview and interactions (diplomating event window)
	- factions try to actively change policies to their liking, how hard they try, and if they succeed would be determined by how influential they are
	- faction status representing it's place in government/society (ruling - faction making up the government, opposition - faction that does not rule, but is 
		part of a government system <being part of parilament, monarchs court, etc.>, outsider - faction outside a formal government system <political party not present
		in parliament, faction representing lower classes in aristocratic society>, suppressed - faction that faces repressions from the government, banned - faction that have been 
		formally outlawed, underground - faction that still functions, despite being banned)
	- multiple leaders can belong to single faction, and it's leader is chosen from amongst them
	- ? different types of factions (political parties, court coteries, social movements, factions representing colonies)
  
- overhaul government:
  - new authorities based on how the ruler is chosen (election, inheritance, appointment, and maybe even sortition)
  - the government form would be further specified by civics (for example elective government can be an elective monarchy, democracy, oligarchy etc.)
  - government change is more gradual, and more involved than pressing one button (like the reform system in Victoria II)
	
- overhal policies:
	- add new policies that further flesh out governments (e.g. is there a parliament; if yes, is it elected, or appointed; if elected, who can vote etc.)
	- add more policies in general (and basically make them act like reforms in Victoria II)
	
- overhaul leaders:
	- leader ethics
	
potential features:

- Connection between unity and influence
		Unity and influence should be like two ends of a spectrum, connected to a spectrum of government types from democratic to authoritarian.
		Unity would represent government capacity to convince population, while influence capacity to coerce.
	They both would be currency for taking political actions, but by different means, for example when trying to enact a new law, democratic leader would
	make speech in a parliament using unity, while absolute monarch would just proclaim the law using influence. 
		How much of each resource is gained will also depend on government form, so democratic countries will gain a lot of unity, and smaller amounts of influence,
	while authoritarian ones would be in reverse situation. 
	The main problem here is how (and whether it is possible at all) to implement the interchangeability without too much bloat. (i.e. is there a way to make 
	lets say space stations require influence or unity to build, without creating two versions of it; one for unity, and one for influence)
		
  
- early gemplay focused on changing political landscape due to space colonization
    Colonizing another planets is a monumental change in the life of civilizations and the way the home planet was governed shouldn't just neatly translate to government of a whole empire. 
	First years (lets say 50) should be then focused on trying to forge a governing system fit for interstellar empire, either trying to maintain your starting one, 
	or leting your circumstances and choices change it into something new.
    As an example we could imagine a situation when country starts on its homeplanet as a monarchy, but has a strong republican tendentions in the population.
  When it colonizes a new planet it uses this opportunity to get rid of the republican opposition, by forcing them to migrate to this new colony. 
  All is well and good then, but the new colony turns out to be very fast growing and prosperous, and soon it rivals the homeplanet in capabilities. 
  So now we have a space monarchy ruling over a planet of very angry republicans and so a conflict is born, and this conflict would be the main internal 
  concern for the country. The resolution of this conflict would decide the future government of the whole empire, either the monarchy manages to suppress
  the colony and continue on its merry way, or the colony prevails and abolishes the monarchy althogether, or maybe it decides to just secede and both countries 
  go on their separate ways, or maybe they reach compromise, and the government changes to more representative, without abolishing the monarchy, or the colony 
  becomes highly autonomous and both parties agree to just mind their own bussiness, while still nominally being a single country. Thus created system of governance
  can be transplanted to newer colonies, solidifying it. Or not. Or when the republicans win and take over the whole empire, disgruntled monarchists flee
  to a new colony that was established in the meantime, growing their power and influence there and the whole situations repeats but with the roles switched
  and now we have Internal Struggle 2: Electric Boogaloo.
	
- Local governments
	Add a way to represent a local government of a colony (like the republican one in the example above) 

- political traditions 
	As mentioned above, in the early game the goverments should be rether unstable and prone to change, but it should crystalize with time (and actions taken)
and a final stage of this process would be adopting tradition representing this form of government, making it require enormous effort to change, and granting some bonuses
as traditions of course do. This would basically represent the idea that most people associate this country with particular government form (e.g. this country is, 
and historically <for the last few decades>, have been a republic <even though it started as monarchy> and people want it to stay that way).
  

- story driven tutorial
	A branching storyline that would also guide the player through changes done in this mod
  

comments:
	The ideal endpoint of this mod would be to turn Stellaris into sort of Space Victoria, although gameplay should be an important consideration, 
in the end there is no point of turning it into some kind of byzantine construct by adding complexity for complexity's sake, while making the mod 
not fun or entertaing to play. 
	Performance also should be kept in mind, although I doubt it will be very big issue, nevertheless it's better to not ignore it.
	The biggest limitation will be, without doubt, the fact that some things are hardcoded and cannot be changed by scripting, and some features can turn out to be 
impossible, or too cumbersome to implement and unfortunetaly will have to be dropped.
	It could also turn out that some features, while good on paper, do not work well when implemented, which could necesitate changing them drastically, 
or even droppping them completly, or in worst case, rethinking the whole idea behind the mod.
	Limited resources (time, energy) also have to be taken into mind, so more ambitious features could need to be reduced in scope.
	Another consideration is the AI, introducing such drasting changes to gameplay would necesitate overhauling the AI to be able to deal with them. If this turns out 
to be to hard to achieve, the mod could be done in such a way, that this changes apply only to player, although this should be only a last resort option.
