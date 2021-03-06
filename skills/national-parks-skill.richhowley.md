---
description: Information on US National Parks
---

### _national-parks-skill.richhowley_  
## Description:  
Get listings of US National Parks by state, have Mycroft read descriptions of  national parks and even test your knowledge of where National Parks are located.

To use this skill  you will need to obtain an API key from the [National Park Service](https://www.nps.gov/subjects/developer/get-started.htm).  Just follow the link and fill in the form, it's free and you will not be required to create an account.  When the skill is installed there will be a new settings entry in the Skills section of [Mycroft Home](https://home.mycroft.ai) under National Parks.  Paste in your API key and click the Save button.  As soon as the skill picks up the API key it will be able to connect to the NPS servers.

For the purpose of this skill the term "National Park" is used loosely to refer to almost any property managed by the US National Park Service.  Properties with a designation of  National Monument, National Historic Site or National Recreation Area will be included in park listings.   The only designation that is explicitly excluded from park listings is National Historic Trail.  All information is provided by the National Park Service.

When asking for a park description the skill will do a search on the words given, so one does not need to say the complete park name.  For example, 'describe Edgar national park", "describe Edgar Allan national park" and "describe Edgar Allan Poe national park" will all provide a description of Edgar Allan Poe National Historic Site.

Since definite articles are dropped from speech, searches for descriptions of some properties will fail if they are included.  For example, trying to hear a description of Rosie the Riveter WWII Home Front National Historical Park by saying "describe Rosie the Riveter national park" will fail but "describe Rosie national park" and "describe Riveter national park" will succeed.

After asking to be quizzed Mycroft will ask what state a particular National Park Service property is in.  The answer may be spoken after the beep without using the wake word but there will only be a few seconds to answer.  If Mycroft does not respond to the answer use the wake word with "Repeat national parks quiz" and answer after the beep.  
  
![](../.gitbook/assets/star.png)  
  
### Platform:  
 ![Mark I](../.gitbook/assets/mark-1-icon.png)  ![Mark II](../.gitbook/assets/mark-2-icon.png)  ![Picroft](../.gitbook/assets/picroft-icon.png)  ![plasmoid](../.gitbook/assets/kde.png)   
### Examples:  
> List national parks in Utah.  
> Describe Yellowstone national park.  
> Quiz me on national parks.  
> Repeat national parks quiz.  
  
## Installation:  
{% hint style="info" %}
This skill is in Mycroft Market and is thereby aproved by the Mycroft Skill testers
{% endhint %}
    
{% tabs %}
{% tab title="Install by voice" %}
> Hey Mycroft - install National Parks
{% endtab %}
  {% tab title="Install by mycroft-msm" %}
``` mycroft-msm install National Parks```
{% endtab %}
  {% endtabs %}
    
## Summary:  
**Github:** [https://github.com/richhowley/national-parks-skill](https://github.com/richhowley/national-parks-skill)  
**Owner:** [@richhowley](https://github.com/richhowley)  
**Created:** 2018 Nov 11 17:31:25 UTC  **Last updated:** 2019 May 22 01:53:00 UTC  
**License:** GNU General Public License v3.0  
**Market status:** [In Market](https://market.mycroft.ai/skill/national-park)  
**Categories:** [ Information ]   
**Tags:** \#nationalparks \#parks \#vacation   
