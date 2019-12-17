---
layout: post
title:      "`CLI Data GEM PROJECT`"
date:       2019-12-17 06:35:45 +0000
permalink:  cli_data_gem_project
---


**The Struggle:**

When I say the struggle was real....boy was it REAL. I was caught in the middle of starting a brand new job, moving and a horrible break-up all at once. But I let nothing deter me from my destiny as a coder. I first thought of this elaborate CLI gem parsing all of the popular video games. Then....I changed my mind. I dont play video games much ad thought I was at a disadvantage from knowledge of the game scene. Then I thought of several other ideas...none stuck. Until......


**The Epiphany:**

Until I found my car towed from parking in a place where I SWORE I could park. Not only was my car towed....but it was in between pay days. Talk about upset. I mean were the cops just waiting for me to leave to tow my hoopty. The tow was 1/3 the cost of my entire car. My car, though it is very...uhh...lets say frugile spirited is stil my transportation around town. I'd been catching the bus last year. So I know the importance of solid transportation. After coughing up a hunk of money. I was then presented with the latest project for my school.Hey!! I know...I'll make a CLI gem to help people not let what happened to me happen to them. So off to the on-line free parking searches I went.

**The Code:**

Well I felt I coded a lot better than I actually did. Oh what elaborate plans I had for the best code in the world. The bee knees of coding, theupper echelons of top tier code. Weellll...Not exactly. I found myself stuck time and time again. Not to mention I started a lot later than the rest of my cohort. But "mama aint raise a quitter." I dug in and never let that shovel (<<) go. 

First I found a great website with lots of great parking spaces. Next, I used Nokogiri and Open URI to parse and scrape the needed data. Scraping is not difficult....YET very precise, and demands precision for even the most trivial tasks. After locating my target. I shot my shot. BOOM. It was on like Donkey Kong. I scraped....and scraped....and scraped. Then I fillany located the right tags and anchors. Classes and id's.  Once Parsed, all I had to do was the simple CLI interface and define some methods in a scraper file. Therewas one other file also. That defined methods to be use by the CLI.
```
def list_spots
  
	puts  "Please enter your spot selection. Type 'list spots' => for a list of spots; 'Details' => for more info; Link => for the      website; Menu at anytime or exit to end session."
  
	@spots = VegasParking::Scraper.names
     @spots.each.with_index(1) do | place, i|
           puts "#{i} #{place.name}"
    end
  
	        puts "***Pick a number any number :) ***"
          puts "***Remember, you can press menu at anytime***" 
   end
```

**The Conclusion:**

By the End of the project I was exhausted yet relieved. But the battle was hopefully won. But the war for my education was far from over. There is so much more I need to learn. But I must say. This project taught me a WEALTH of information. And I did it alone. I never once asked for help. Even tough I could have. But to concour Goliath with just my own stone, made my smile ear to ear. What a journey. And its not over. 
"The Marathon Continues".

Tariq "GhostScript" Bailey

           












