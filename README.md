# Heroes-of-Code-and-Logic-VII

You got your hands on the most recent update on the best MMORPG of all time – Heroes of Code and Logic. You want to play it all day long! So cancel all other arrangements and create your party! 

 

On the first line of the standard input you will receive an integer n – the number of heroes that you can choose for your party. On the next n lines, the heroes themselves will follow with their hit points and mana points separated by empty space in the following format:  

{hero name} {HP} {MP}  

where HP stands for hit points and MP for mana points 

a hero can have a maximum of 100 HP and 200 MP 

After you have successfully picked your heroes, you can start playing the game.  You will be receiving different commands, each on a new line, separated by " – ", until the "End" command is given.  

There are several actions that can be performed by the heroes: 

CastSpell – {hero name} – {MP needed} – {spell name}  

If the hero has the required MP, he casts the spell, thus reducing his MP. Print this message:  

"{hero name} has successfully cast {spell name} and now has {mana points left} MP!" 

If the hero is unable to cast the spell print: 

"{hero name} does not have enough MP to cast {spell name}!" 

TakeDamage – {hero name} – {damage} – {attacker} 

Reduce the hero HP by the given damage amount. If the hero is still alive (his HP is greater than 0) print: 

"{hero name} was hit for {damage} HP by {attacker} and now has {current HP} HP left!" 

If the hero has died, remove him from your party and print: 

"{hero name} has been killed by {attacker}!" 

Recharge – {hero name} – {amount} 

The hero increases his MP. If a command is given that would bring the MP of the hero above 200, MP is increased so that it reaches the maximum. Print the following message: 

"{hero name} recharged for {amount recovered} MP!" 

Heal – {hero name} – {amount} 

The hero increases his HP. If a command is given that would bring the HP of the hero above 100, HP is increased so that it reaches the maximum. Print the following message: 

"{hero name} healed for {amount recovered} HP!" 
