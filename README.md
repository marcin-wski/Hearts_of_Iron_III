# Hearts_of_Iron_III
This is just a few simple events added to the main game. They don't change the actual game play or screw up the actual way history goes.
This repo includes 3 files:

(there's also a historically plausible explanation to all changes down below)

## custom_script_political
### Event id 0001
Triggered only by user through the in-game script (started by pressing "\`" or "~" while in game)
  1. Increases paternal autocrats' popularity in the parliament
  2. Decreases fascistic popularity in the parliament
  3. Decreases socialist and communist popularity in the parliament
  4. Decreases neutrality to 0
  5. Increases relations with Germany and Italy
  6. Decreases relations with all Komintern nations
  7. Slightly decreases relations with England and France
### Event id 0002
Triggered only by user through the in-game script (started by pressing "\`" or "~" while in game)
  1. Lithuania, Latvia, Estonia all declare war on each other
  2. Lithuania, Latvia, Estonia all declare war on Poland
  3. Romania, Hungary, Yugoslavia, Greece, Bulgaria, and Albania all declare war on each other

## custom_script_military
### Event id 0003
Triggered only by user through the in-game script (started by pressing "\`" or "~" while in game)
Gives two options for new troops in a few Polish provinces:
  1. 7 5-brigade infantry divisions and 3 3-brigade divisions with Military Police brigades
  2. 5 4-brigade armor divisions and 3 2-brigade divisions with Military Police brigades

## custom_script_turkey_and_greece
### Event id 0004
Trigger:
  1. Is = Turkey
  2. Poland controls capital cities of Yugoslavia, Greece, Bulgaria, and Romania
  3. Poland has joined Axis
  4. Poland is not at war with Greece
Result:
  1. Turkey joins Axis
  2. Turkey receives a minor boost to materials and manpower, a boost to national unity, and a solid decrease in neutrality
  3. Turkey has increased relations with Axis nations and decreased relations with Komintern nations
  4. Turkey secedes the European provinces (including Istanbul) to Poland
  5. Poland secedes an island (previously owned by Greece) to Turkey
  6. Turkish paternal autocrats have increased popularity in the parliament
  7. Turkey gets increased industry in 4 provinces (basically to even out the industry they lost in Istanbul)
  8. Turkey gets 3 3-brigade divisions of mountain infantry and 2 2-brigade divisions of cavalry

### Event id 0005
Trigger:
  1. Is = Greece
  2. Poland controls Athens and Salonica
Result:
  1. Poland gets a slight decrease in threat to everyone
  2. Poland ends war with Greece
  3. Poland gets a solid decrease in threat to Greece
  4. Greece signs a non-aggression pact with Poland
  5. Greece gets a minor dissent and 100 neutrality
  6. Greece moves capital city to Crete
  7. Crete gets a boost to industry, naval base, anti air artillery, land fort, and coastal fort
  8. Greece secedes all provinces to Poland. Only Crete remains Greek
  
## Explanation
It's year 1936... the world has seen and lived through World War I and truly hoped that it really was the "war to end all wars". This has been proven to be false - Hitler came into power, Germany began training the army and building up the fleet, Soviet Union grows in power and the defeat of 1919-20 did not stop their hopes for spreading the revolution to the rest of the world, Italy has a fascist government, bad things begin happening in Spain, USA goes back to the policy of isolationism, Japan strengthens their hold over Korea and attacks China, United Nations is an utterly powerless organization that cannot prevent any of this from happening, France and England want peace above everything else...

In sight of all these events Eastern Europe grows more and more worried. Polish right-wing movements understand that the Allies are unlikely go to war even to defend their ally and start reviewing their options. ONR _(Obóz Narodowo-Radykalny)_, a fascistic movement, drastically limits its organization and actions and give its full support to OZN _(Obóz Zjednoczenia Narodowego)_ - a more moderate alternative - while at the same time tirelessly undermining the socialist and communist parties and spreading anti-communist propaganda. Thanks to their efforts the public starts looking more favorably towards OZN, which after all was the driving force behind the defeat of the Bolsheviks in 1919-20. The Polish public begins noticing that the Soviet armies are quite literally standing on the border ready to cross at a moment's notice. The Polish army receives a surge of volunteers ready to once more defend their homeland against the Bolshevik invasion and, thanks to the now strongly right-wing leaning of Polish public, Germany supplies a small quantity of medium tanks straight out of the factory.

Poland is not the only one in this troubling time, however, and the Baltic states understand that no one will help them once the Soviet Union comes knocking. They all decide that their only option is the unthinkable - another war, and soon. Lithuania resents Poland, so their choice seems easy... buuuuuut Latvia and Estonia are not far behind and quickly border incidents escalate to a full-blown war in every direction. Baltic states are now engulfed in war.

Balkans follow the suit - Romania looks hungrily at Bulgaria, Yugoslavia wants to unite with Albania, Hungary wants to re-live their glory days of their Empire, and Greece grows worried of Yugoslavia... No one wants to be first to start the fire, but when a group of Romanian soldiers find themselves on the wrong side of Romanian-Yugoslavian border and chooses to shoot rather than answer questions from the Yugoslavian patrol all hell breaks loose. Yugoslavia crosses the border to Romania while gathering the reserves to take over Albania. Romania launches a large scale offensive into Yugoslavia and Bulgaria. Greece preemptively strikes Yugoslavia and rolls through Albanian defense forces. Hungary feels the moment of "now or never" and backstabs Yugoslavia and Romania hoping they will bleed themselves out first. At the end of the day the Balkans are in flames in a brutal war of everyone against everyone. Only Turkey remains neutral... waiting for the right time to strike, perhaps hoping for the rebirth of the Ottoman Empire.

### User choices now (+ historical explanation for them)
As this scenario is clearly catered to player being Poland, the main thing is to clean up the mess in Baltic states uniting them under the Polish banner and turn your attention south, to Czechoslovakia. Remind the Czechs that you are all from the same Slavic family and bring them to heel with a swift attack cutting through their lines, encircling their capital city, and showing them the prosperity of the Republic of Poland. The next objective would be to observe the Balkans. Romania and Greece are the main players here - Romania is the largest nation with the strongest army in the region, Greece fights basically only on one (northern) front. Once Albania and Yugoslavia are no longer a problem Hungary and Bulgaria will stand for a few weeks before collapsing as well. Roll through the Balkans when you see fit, aiming to take out Romania as a priority - the sooner the better. Once you deal with Hungary and Romania, deal with Bulgaria if it still stands, and cut through Greece. Now this is where an AI choice comes in - once you control Athins and Salonica Greece will receive an option of "bitter peace" and secede all their Balkan possession, holding only to Crete, giving you the opportunity to end the war and not having to build the fleet to take over Crete. Otherwise the war can go on, and on, and on until you do just that. Once the war with Greece is over you should be receiving an invitation to join the Axis soon. Your paternal autocrats hold the parliament in a tight grip and Germany would not let an opportunity like that pass. Once you join the Axis there goes Turkey...

From the (pseudo-)historical standpoint it makes sense - you took over the entire Balkans and control the main Greek cities. In order to avoid total defeat and annihilation Greek government sues for peace, hoping to just keep holding on to Crete. That's a clear win-win as Crete will not really do you any good anyway in a long run but saves you from having to create a fleet. Once you are done with Greece Turkey stands at a very difficult place - Poland just _steamrolled_ through the Balkans, finalized the war with Greece, and can now turn their full, undivided attention to Turkey. That's not something Turkey is likely to survive. Aside from that it is clear by now that the war is imminent, the question is only - who attacks first? For Turkey there are four options:
  1. Stay neutral and hope Poland won't annihilate you
  2. Join Allies and _pray_ they help you when the Axis attacks... and that they help you fast enough
  3. Join the communists. That would make the least sense as Turkish government is already right-wing and they never liked Russia. Joining the Komintern wouldn't make sense historically speaking
  4. Join the Axis and have Poland and Germany rally behind you when the war breaks out and you fight either in Middle East with Allies or in Caucasus with Russia
  
You don't have be a historian or strategist to realize that Turkey really has only one option that does not lead to imminent, total annihilation. That option is to negotiate with Poland and join the Axis. Now, Poland is a generous neighbor and as war with Greece already shown Poland doesn't just blindly destroy nations (that is if you let Crete be. You can always invade Crete before taking over Athens or Salonica, thus taking over Crete before the event can be triggered), so when Turkey approaches Poland with offer of an alliance against the communists Poland gives just a few requirements - Turkey has to give away the European provinces. This way Poland fortifies its power as the (de facto) Eastern Empire bordering Russia from Baltic to the Black Sea. At the same time Polish and German government promise to rebuild Turkish government near Ankara, help train Turkish recruits to create new mountain infantry divisions, and sweeten the deal by giving away this one lonely Greek island (let's be honest - you won't utilize it anyway so why bother holding it?). Option 4 clearly seems like the best deal - you get more industry, new divisions, powerfull ally next to you, even more powerfull ally in Western Europe who will help you sort out the Middle East, AND your government is already right-wing anyway so it's an ideological closeness as well.

This scenario does not go any further than this. None other events are changed. Should you want to just kick back and relax now the world will mostly follow the same pattern, especially in the West - Germany will attack Denmark, roll through Netherlands and Belgium to get to France, then help Italy deal with the British forces in Africa, in 1941-1942 Japan will surprise attack USA. Germany will eventually try to bring England to submission although it's unlikely that it will be a successful operation... However, Eastern front is going to be a bit different - Germany _will not_ declare war on the Soviet Union. If you do not attack the Soviets in 1941 USSR will eventually declare war on you somewhere between 1942 and 1943 (just like historians believe Stalin would anyway. When German troops rolled through USSR in 1941 many Soviet troops were in marching positions and many units were explicitly training to attack the West rather than to defend their positions). Winter War of 1940 between USSR and Finland also seem to not be happening, which could be easily explained historically - Russia now borders potentially hostile Poland instead of Germany bound by a non-aggression pact and therefore cannot just move their divisions north to fight Finland...
Another thing - Since German attack on USSR does not happen, D-Day in June, 1944 also does not happen. If you allow it enough time it will probably happen eventually, but it's hard to determine when. It would greatly depend on the war in Africa, invasion on Italy, and the progress of German attacks on England. Especially since USA will be mostly involved in war with Japan at this point.
So the scenario does not change the world too drastically, and there's nothing that stands opposed to the historical realities of 1930's-1940's Europe - No, Spain will not join the Axis (without you explicitly trying for it to happen). Ireland sits quietly and does not join Allies or Axis. No one attacks Switzerland. Scandinavian countries remain largely neutral (Germany may or may not attack Norwey. I've seen them do either one, my guess is it's random at this point). Despite first successes in Ethiopia the Italian forces are quickly overrun by England and France at the beginning of the war. Japan will not be in a position to attack British India (although they will help you if/when Soviet Union attacks you). Mexico and South America will not join the war until much later (when they join the Allies, following the historical pattern). Sooner or later you will be at war with 75-80% of the world.

The scenario might evolve over time if there's bugs or I realize something makes more sense (the Turkish script evolved a few times, and the Greek part came very, very last when I realized that any sane country would sue for peace at the sight of such great defeat, especially since they're alone in that war and cannot expect help from anyone, even if they _do_ join the Allies while they're already at war with the Allies will not actually provide them any help or declare war on you), but it should largely remain the same.
