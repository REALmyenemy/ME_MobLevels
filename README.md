# ME_MobLevels
A simple level plugin for mobs having levels.

0% progress  
It's a simple solution to mobs having levels. Each monster has a monster assigned, by default unless you use the notetag to set it.  

Notetags  
```<ME_MobLevel: X>```  
It sets the monster to have this level by default.  
```<ME_MaxMobLevel: X>```  
It sets the max level of the monster to X. It can be bypased by "set" command and MobLevel tag  
```<ME_MinMobLevel: X>```  
It sets the min level of the monster to X. It can be bypased by "set" command and MobLevel tag  


@OnPaper (Might change)  
Plugin commands  
```ME_MobLevel set x y```  
Sets level of mob Y in the database to X. You can use v1 to use variable number 1, v2 for variable number 2... or the number.  
```ME_MobLevel add x y```  
Adds Y levels to mob X. This doesn't bypass cap.  
```ME_MobLevel increase x y```  
Adds Y levels to mob X in the battle. This doesn't bypass cap.  

Extensions  
X_MEML_MobLeveling: It will allow the maker to change in percentages mob stats, drops, gold earnt and experience (or any combination of that), maybe sparams and xparams too.  
X_MEML_MobLevelSkills: It will allow the maker to make a monster have skills if they have specific level, or specific and higher. (Might take months or even one year)  
