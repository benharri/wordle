# wordle archive

archived from powerlanguage.co.uk/wordle at 
[tilde.team/~ben/wordle](https://tilde.team/~ben/wordle/)

so far NYT has just removed words from the answer list

	$ diff nyt.txt orig.txt
	241a242
	> 'agora',
	244a246
	> 'pupal',
	272a275
	> 'lynch',
	292a296
	> 'fibre',
	301a306
	> 'slave',
	391a397
	> 'wench',

unminified source in [main.js](main.js)


## new word changes

apparently we have new changes? NYT version pulled as of May 9, 2022

	diff --git a/nyt.txt b/nyt.txt
	index 3fbeddf..c2c683e 100644
	--- a/nyt.txt
	+++ b/nyt.txt
	@@ -282,7 +282,6 @@
	 'nymph',
	 'found',
	 'shall',
	-'harry',
	 'stove',
	 'lowly',
	 'snout',
	@@ -313,9 +312,7 @@
	 'heist',
	 'shown',
	 'zesty',
	-'hasty',
	 'trash',
	-'fella',
	 'larva',
	 'forgo',
	 'story',
	@@ -325,8 +322,8 @@
	 'badge',
	 'midst',
	 'canny',
	-'fetus',
	-'butch',
	+'shine',
	+'gecko',
	 'farce',
	 'slung',
	 'tipsy',
	@@ -358,7 +355,6 @@
	 'trait',
	 'girth',
	 'piety',
	-'payer',
	 'goose',
	 'float',
	 'donor',
	@@ -380,30 +376,24 @@
	 'gawky',
	 'hutch',
	 'pinto',
	-'gaily',
	 'egret',
	 'lilac',
	 'sever',
	 'field',
	 'fluff',
	-'hydro',
	-'flack',
	 'agape',
	 'voice',
	 'stead',
	-'stalk',
	 'berth',
	 'madam',
	 'night',
	 'bland',
	 'liver',
	 'wedge',
	-'augur',
	 'roomy',
	 'wacky',
	 'flock',
	 'angry',
	-'bobby',
	 'trite',
	 'aphid',
	 'tryst',
	@@ -436,14 +426,11 @@
	 'twang',
	 'shrug',
	 'treat',
	-'unlit',
	 'waste',
	 'merit',
	 'woven',
	-'octal',
	 'needy',
	 'clown',
	-'widow',
	 'irony',
	 'ruder',
	 'gauze',
	@@ -464,17 +451,14 @@
	 'booze',
	 'alpha',
	 'thyme',
	-'eclat',
	 'doubt',
	 'parer',
	 'chute',
	 'stick',
	 'trice',
	 'alike',
	-'sooth',
	 'recap',
	 'saint',
	-'liege',
	 'glory',
	 'grate',
	 'admit',
	@@ -496,7 +480,6 @@
	 'valid',
	 'ionic',
	 'equal',
	-'unset',
	 'floor',
	 'catch',
	 'spade',
	@@ -521,9 +504,6 @@
	 'photo',
	 'dream',
	 'stale',
	-'vomit',
	-'ombre',
	-'fanny',
	 'unite',
	 'snarl',
	 'baker',
	@@ -2262,8 +2242,6 @@
	 'undid',
	 'intro',
	 'basal',
	-'shine',
	-'gecko',
	 'rodeo',
	 'guard',
	 'steer',
	@@ -2306,4 +2284,26 @@
	 'rower',
	 'artsy',
	 'rural',
	-'shave'
	\ No newline at end of file
	+'shave',
	+'bobby',
	+'eclat',
	+'fella',
	+'gaily',
	+'harry',
	+'hasty',
	+'hydro',
	+'liege',
	+'octal',
	+'ombre',
	+'payer',
	+'sooth',
	+'unset',
	+'unlit',
	+'vomit',
	+'fanny',
	+'fetus',
	+'butch',
	+'stalk',
	+'flack',
	+'widow',
	+'augur'
	\ No newline at end of file
