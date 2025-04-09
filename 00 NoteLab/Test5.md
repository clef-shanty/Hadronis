This is my Obsidian Vault, and when I think of 
the word "vault," I think of it as a place where you store important information—something valuable 
that you don't want to be taken away. This is why I was struggling with creating my own personal 
knowledge management system using Obsidian. I was not understanding the three steps of real 
knowledge management that are actually useful. Step one is being able to get information 
into my vault in an efficient and frictionless way. Step two is being able to categorize that 
information in a frictionless way. And step three, and this is the part I was really not doing 
well on, is how to actually get access to that information to solve a problem when 
I actually need the solution—right now. That's why I finally figured out 
how to use AI and automation to solve all three of these problems 
and finally make my Obsidian vault actually useful—so useful that it helps me 
to make money. Let me show you how I did it. Hey there, it is I versus AI, 
and this is the primordial... (Bell ringing) I wanted to scroll in to show you, so 
that we can reference this later on, how this vault is built. It is built on notes, 
which are the blue dots. It is built on links, which are the green dots. And it's also 
built on tags, which are the orange dots. What I wanted to achieve with this vault is 
a complete knowledge management solution with the least amount of friction, effort, and 
struggle from me to maintain it. For that, I turned to AI. So, all of these links, 
tags, and some of the notes that you see in here—many of them were brought into my vault, 
categorized in my vault using AI automation. Let's start with this note. This is a note that 
was automatically created using an N8N automation, which produces a note—this is a YouTube video 
summary from a transcript, having key takeaways, callouts, tables, bullet points, and all of this, 
including the links down at the bottom. These are created from this N8N automation, where 
I simply put a YouTube link into a GPT. It starts the trigger here, 
brings through the transcript, the transcript is then summarized here, 
sent back to the GPT, then it goes on and creates the front matter, which is 
otherwise known as note properties—links, which you've just seen. It creates a markdown 
note, drops it into my Dropbox folder, which is then linked to this transcripts folder in 
my basket, where everything comes into my vault. The key thing I want you to notice 
here are the properties—properties, otherwise known as YAML front matter. 
In earlier versions of Obsidian, the way in which step two of my personal 
knowledge management system works, that is organizing and categorizing these notes. 
Without well-done properties, I always struggled to get the information out of my vault. Let's 
be honest, when I would create a new note, I often struggled to think of all of the 
important properties that I could put here. I might put a tag or two. I never bothered 
with aliases, and I never wrote descriptions. I’d do the title created, if I did that 
much. What would happen is that notes would pile up in my basket here, 
waiting for me to process them, and I would get overwhelmed at having to process 
so many notes, thinking of the title and creating all of these properties. I would struggle 
with that and end up just doing nothing. Then, I'd feel like my knowledge management system 
was a failure, and I'd start my vault over. I love properties, but to be honest, I'm 
just not going to sit here and add in all of these properties, typing in title, channel, 
author—all of this kind of stuff. I'm just not going to do it. But AI is really good at being 
able to categorize information into properties. You've seen one of the ways in which I 
bring information into my vault. One of the ways is through this N8N automation, which 
creates this note. But what if I have written the note or have an automation that doesn't 
add properties and I need to do them myself? Like with this note, which is the result of 
an automation, it creates all of the metadata and even a slideshow that I use to create my 
YouTube videos like this one. This section of the automation takes the input data from a form, 
where I tell it everything that the video is going to be about and what it's going to contain. 
It goes ahead and defines the target audience, the angle from which I can approach 
the video, keyword phrases, emotion, and power phrases, title suggestions, search 
phrases, description, refined description. It also goes ahead and creates a markdown file, 
which is this file. Now, let's say I want to keep this file and I want to add properties, but as 
I've already said, I'm not going to do them by hand because ain't nobody got time for that. 
So I'm going to head to the top of the note, hit the enter key a couple of times to 
make some space, add my cursor at the top. I'm going to go over here, hit text generator 
templates, and I love this plugin so much that if it did not exist, I'd have a hard 
time using Obsidian. It does so much more than just generate text. Text Generator 
is an open-source AI tool that brings large language models right into your vault. And 
for those of you who are thinking, "Wait, wait, wait, hold on. I do not want some other 
company, OpenAI or Google Gemini or whatever, having access to my vault," you can use 
local private models that are on your computer. They can be used just like 
any other model with Text Generator. In fact, both of the AI tools I'm going to 
show you in this video allow use for local large language models. But what I love 
about Text Generator is this template... Right here. Templates are what allow 
me to remove friction from my vault. So I created a template which would take the 
entirety of the note, as well as the title, and with a click, generate the front matter 
or the note properties for the entire note. When it comes in, it will always come in 
with a space at the top, and front matter properties don't show up properly unless they 
are at the very tippy top of the note. Like so, here in the created field comes into play 
another plugin that I love, called Templater. Templater allows me to make my 
vault really, really useful, powerful, by putting in little spots where 
you can add in information that is static, such as creation of the note. For example, 
there's so much you can do with Templater. I've just scratched the surface, but in this 
case, I'm using it to automatically put the created date as the file creation date—the 
creation date of the actual note file. To do so, I simply right-click, and if 
you're wondering how I have added in all these lovely colors here and how I've 
done so over here with these buttons, that is from the plugin called Commander. I 
love this plugin because I love to make my Obsidian vault look peaceful and easy on the 
eyes. I'm going to spend a lot of time here. I have a color scheme that I use 
throughout my vault. I'll show you other plugins that I'm using as I move 
through this process—this three-step process of how I made my Obsidian vault 
useful and solved my knowledge management problem. I'm going to click on "Templatized 
Note" here, and it simply assigns the date. You can also see Templater at play in my daily 
note. It's based upon this template. You can see a lot of Templater code here, which makes 
the note show up. Then, the previous note, the note for the next day, and even assigns a 
place where my cursor will automatically show up when I click in the note because this is where I 
want to add the task—the first task for that day. The links make it very easy to move through my 
notes by yesterday or tomorrow. And if you're looking at this daily note and would like to have 
this for yourself, as well as the template which creates the note properties and also the template 
which adds all of the links for your content, that means everything that's in the note, it will 
give you a block of internal relevant links which you can go through and keep what you think is 
worthwhile or trim the block down as you wish. These two templates that generate front 
matter note properties and the links template, along with my daily notes template, 
are available for you to get a hold of right now on my Gumroad shop and remove 
friction from your Obsidian vault too. Because these really were a game-changer for 
me when I struggled so much to make value out of my notes. A lot of the challenge came from 
not actually getting access to my notes later on because I had not properly categorized 
them—just like trying to find a book in the library. You need to have an idea of 
where that book is, and that book needs to be carefully and properly categorized 
so you can find it in the card catalog. I'll show you step three of how I get useful 
information that solves my problems now out of my vault, whether that information is 
stored in just one note or across many notes. Before I show you that, I want to show you how 
I use my Obsidian vault to help me make money, and particularly how I use it to 
create AI automations, how I use it for prompt crafting and prompt chaining, which 
is part of what I do. Also, how I use it to help me in building out my AI Automators Prompt 
Crafting Society, which opens on January 1st. This is a real-life use case for how I 
use my vault. Here is my folder structure, with my basket, where I've shown you that 
everything comes in. This is my personal folder, my professional folder, and my knowledge 
folder. Over here in my I versus AI folder, you'll see my products folder. If you're 
wondering how I have made these lovely icons and colors for my folders, that comes from two 
plugins—Iconize, which is a fantastic plugin, and File Color, which allows you to change your 
files to whatever color scheme you would like. This is the folder for the YouTube notes 
automation I showed you earlier. When I'm building out an automation, there's a lot of 
prompt crafting. For example, this transcript breakdown prompt here. This whole double line 
here breaks up prompts, shows me this is a system prompt and this is a user prompt, and this 
corresponds to this node in the automation where you can see the same prompt here. It's a system 
prompt, and here's the user prompt, and so on. This is called prompt chaining, and when 
I'm working with a very large prompt, like the final prompt in this prompt chain, 
a prompt that is very long like this, I have found that Obsidian is the best 
tool for working with those long and complicated prompts and prompt chains. 
And that's because of one word: Markdown. Obsidian is a markdown editor, and 
Markdown, in case you're wondering, is just a way to format text. In this case, this 
means headers, bullet points, or bolding. All of this here is Markdown, and I have it hidden for 
readability. But Obsidian—which, by the way, I should have mentioned this early—is 
free and allows you to work with Markdown. Now, if you're thinking, "I could not work with 
Markdown. I don't understand what that is," that's where a plugin like the Editing Toolbar comes 
in, which allows you to quickly assign bold, italics, headers, and lots of other things, 
including tables, to your text. Markdown is key. Obsidian and large language models 
make great partners. So, by using this to create N8N automations, which I 
then sell and use for my own problems, every automation I create is for a problem that 
I am personally experiencing. I've created the solution to it and then I offer it to you, 
in case you have the same problem as well. I also use Obsidian to help me make money by 
creating quick-start guides that go with my products. A quick-start guide is another way that 
Obsidian helps me to make money with my vault, by creating a quick-start guide that 
goes with each of the products. This is the one for the YouTube metadata automation. I am able to add images, and I can then turn this 
into a PDF and include this with the product. I also create a notes PDF that goes with the 
product. This basically shows all of the node notes for the automation—so basically 
every node, what it does in the automation, and how to think about it, what gets 
stored in this node, the output data, and the next step. This also goes out to the buyer 
so they can see exactly what they're getting, how the information flows, and also use it as a way to 
learn and perhaps build out their own automations. Also, I use Obsidian to help me build out my AI 
Automators Prompt Crafting Society—from storing the prompts for the images, to helping me build 
out the onboarding, to helping me understand how the profiles work, so that when it's time to 
set up the community, all I need to do is go into the table here, see what I'm going to 
add to the profiles for my members, and get an explanation of those fields so I can quickly 
do so when it comes time to set up the community. So not only do I store notes in my 
vault, I literally work inside my vault. Another neat trick about Text Generator and 
another way that you can bring information into your vault in very few clicks is here 
with this feature for Text Generator called Extractor. I've just added this YouTube video 
link here. I'm going to click on Text Extractor, and if there's anything in that note 
here, it will come up as a file URL. It can work with PDFs, it can work with images 
as an OCR. It can read what's in the image and input that as text into your vault. It can 
do that both with images on your machine and images that you just have a URL for. It 
can also do so with web pages and audio, including all the different formats—m4a, mp3, 
and so on. I'm going to right-click here, click on Text Extractor, and click Convert. 
You can see it takes a second—literally, literally a second—to add this entire transcript 
here, and it's exactly from the video. I'm just going to click "Copy" and you'll 
see here that the entire transcript comes through. But you might be thinking 
this is a mess and nowhere near as neat and organized as this transcript 
I showed you, but with Text Generator, you can simply type in what it is you want to 
do with the text above it—like format this text. You can even use something like "Rewrite text for 
readability," adding paragraphs and punctuation. This is another template that I use in Text 
Generator, and if you would like this template as well, let me know in the comments. If enough 
of you ask for it, I will add it to the product that I've already put up on Gumroad, which has 
these two templates in my daily note template. So, I've covered step one—how 
I solve my problem of having a useful vault by getting information into 
it effortlessly through AI automation. Now, I showed you how to add properties to my 
vault, both through automation or through one click with Text Generator templates. And 
now, I'm going to show you how I process a note and then finally how I get information 
from my vault when I need to solve a problem. In order to process a note, 
everything comes into my basket here. Here is a transcript by Anna Hickman, who has a 
YouTube channel, and she is a very smart person. Her channel is wonderful, and she offers really 
great information, so I would highly recommend giving her a listen. After I watched this video, 
I really wanted to get its benefits into my vault, so I'm going to head down here to the 
bottom, right above the link block, and I'm going to show you Auto Note Mover in 
order to get this file where I want it to go. You might be wondering what system I'm using—what 
personal knowledge management system I'm using. Obsidian is the tool I'm using, but what system 
am I using within that? I'm not using any system. It's basically just a folder system. I looked 
at Zettelkasten, and you'll hear of PARA, and you'll hear of maps of content, and there 
are many different ways to organize your system in a way that works for you. I found 
that the way that works for me are folders. Because I don't ever go looking for notes, I go 
looking for the knowledge in those notes. But if I ever do need to find a note, it's very 
easy because it's pretty simple as to where it's going to be. It's a knowledge note; it's 
going to be in one of these folders. If it's a personal note, it's here in this folder, 
and it's pretty easy for me to find things. For example, this is a sovereign craft note. That 
just means something that I use to earn money, my craft, what I do for a living. And 
I'm going to just hit the tab button here and hit "Sovereign Craft." And when I 
do so, I want you to take a look up in the upper right-hand corner. You'll see this 
pop up here, and you'll see the note has left the transcripts file and is now in my 
"Sovereign Craft" folder, and it is here. This means that I don't bog myself down 
by having a lot of things in my basket that I need to process. It's basically 
a few clicks—just put in whatever the tag is that I've assigned to the 
note, to the folder where I want it to go. I just put that tag in, and 
the note goes where it needs to go. And that's important because, even though 
these folders look like they're here, they're not actually here. These notes aren't 
actually here. They are symlinked here using symlink because they are in a Dropbox folder. 
That's where they come into at the end of any automation I run. This is an automation that 
I run to create all of the metadata for any new product I create on Gumroad. Because I 
have now four different products on Gumroad, the one that's about to go live with 
the templates that I've just shown you. And I found myself again with that same 
old kind of dread, friction feeling of, "Oh, I have to write out this entire 
product description," and I just, again, do not have time for that. So, this adds 
everything I need for the description, and it also adds a frequently asked questions 
page, a section here at the bottom, custom link, a summary, additional details, and it 
even includes an image prompt for... That's how this looks when it's done. This 
is the product page for the templates that I've just shown you. This is the summary. This is 
all of the description that was written by GPT. These are the additional details, the features 
of the product here, and all of this, again, is written by GPT-4. And this is one of the images 
that I create for every product I create—an image of the product being held with a laptop, and 
I also create the box image as well, too. So now we have step one covered—that's 
bringing notes into the vault. We have step two covered—that's categorizing and 
also putting those notes where they go in as frictionless a way as possible. But now we 
need to get that information out of our notes, and that is where Copilot comes in. 
Copilot is a plugin by Logan Yang, and this plugin is awesome. It's really 
wonderful because it turns your entire vault basically into a knowledge base. You can 
query your entire vault and ask it questions, which it will gather from the 
contents of your notes to answer. It's basically the desire to build the ultimate 
AI assistant based upon your personal, and this is the key point, your personal knowledge 
base, while also being privacy-focused. And that's because this one also takes in—and 
I am using GPT-4 with this—but you can use local large language models as well and a 
local index that you use for the questions. So, this one works by heading over here and 
typing in anything that you would want—a problem or a question that you might have. 
And when you realize that you can answer your problems by knowledge you've already gathered, 
it really fuels your fire to gather more useful knowledge and bring it into the privacy 
and safety of your own personal vault. For this, I'm going to ask something about 
business. I've typed in, "What do I need to focus on in my business according to Justin Welsh?" who 
is someone that I have several notes about here, and it will give here some overview. But you can 
also go in further. Like, for example, I know that Justin Welsh talks a lot about systems—creating 
business systems, so I can ask about that. What I love about this response is that it 
is actually referencing real notes. In fact, notes that came into my vault automatically using 
my YouTube notes automation brought in all of the properties, all of the information. And if I want 
to go back into the information and check it out, I just need to click on one of the timestamps 
for the area that is of interest to me, and I can head straight into the video 
from there by clicking on this link. The information that you talk about in the 
chat, that you talk about here, can be turned into its own note. So, you could begin a note 
about the 80/20 principle here, go to YouTube, search for videos about the 80/20 principle, 
bring that knowledge into your knowledge base, and then keep learning by talking about the 
new information right here in your vault. Because here is the deal: 2025 is 
just a few days away. But automated knowledge that you can use to solve 
your real problems—that is here now, right now. And in order to get the most of 
it, you need to understand about automation, how it works, and how you can use it to remove 
the pain and stress and solve your own problems. If you'd like to know how I created the automation 
for this N8N process, where I bring in a YouTube link and it turns into this wonderful 
transcript, that video is on screen right now.This is my Obsidian Vault, and when I think of 
the word "vault," I think of it as a place where you store important information—something valuable 
that you don't want to be taken away. This is why I was struggling with creating my own personal 
knowledge management system using Obsidian. I was not understanding the three steps of real 
knowledge management that are actually useful. Step one is being able to get information 
into my vault in an efficient and frictionless way. Step two is being able to categorize that 
information in a frictionless way. And step three, and this is the part I was really not doing 
well on, is how to actually get access to that information to solve a problem when 
I actually need the solution—right now. That's why I finally figured out 
how to use AI and automation to solve all three of these problems 
and finally make my Obsidian vault actually useful—so useful that it helps me 
to make money. Let me show you how I did it. Hey there, it is I versus AI, 
and this is the primordial... (Bell ringing) I wanted to scroll in to show you, so 
that we can reference this later on, how this vault is built. It is built on notes, 
which are the blue dots. It is built on links, which are the green dots. And it's also 
built on tags, which are the orange dots. What I wanted to achieve with this vault is 
a complete knowledge management solution with the least amount of friction, effort, and 
struggle from me to maintain it. For that, I turned to AI. So, all of these links, 
tags, and some of the notes that you see in here—many of them were brought into my vault, 
categorized in my vault using AI automation. Let's start with this note. This is a note that 
was automatically created using an N8N automation, which produces a note—this is a YouTube video 
summary from a transcript, having key takeaways, callouts, tables, bullet points, and all of this, 
including the links down at the bottom. These are created from this N8N automation, where 
I simply put a YouTube link into a GPT. It starts the trigger here, 
brings through the transcript, the transcript is then summarized here, 
sent back to the GPT, then it goes on and creates the front matter, which is 
otherwise known as note properties—links, which you've just seen. It creates a markdown 
note, drops it into my Dropbox folder, which is then linked to this transcripts folder in 
my basket, where everything comes into my vault. The key thing I want you to notice 
here are the properties—properties, otherwise known as YAML front matter. 
In earlier versions of Obsidian, the way in which step two of my personal 
knowledge management system works, that is organizing and categorizing these notes. 
Without well-done properties, I always struggled to get the information out of my vault. Let's 
be honest, when I would create a new note, I often struggled to think of all of the 
important properties that I could put here. I might put a tag or two. I never bothered 
with aliases, and I never wrote descriptions. I’d do the title created, if I did that 
much. What would happen is that notes would pile up in my basket here, 
waiting for me to process them, and I would get overwhelmed at having to process 
so many notes, thinking of the title and creating all of these properties. I would struggle 
with that and end up just doing nothing. Then, I'd feel like my knowledge management system 
was a failure, and I'd start my vault over. I love properties, but to be honest, I'm 
just not going to sit here and add in all of these properties, typing in title, channel, 
author—all of this kind of stuff. I'm just not going to do it. But AI is really good at being 
able to categorize information into properties. You've seen one of the ways in which I 
bring information into my vault. One of the ways is through this N8N automation, which 
creates this note. But what if I have written the note or have an automation that doesn't 
add properties and I need to do them myself? Like with this note, which is the result of 
an automation, it creates all of the metadata and even a slideshow that I use to create my 
YouTube videos like this one. This section of the automation takes the input data from a form, 
where I tell it everything that the video is going to be about and what it's going to contain. 
It goes ahead and defines the target audience, the angle from which I can approach 
the video, keyword phrases, emotion, and power phrases, title suggestions, search 
phrases, description, refined description. It also goes ahead and creates a markdown file, 
which is this file. Now, let's say I want to keep this file and I want to add properties, but as 
I've already said, I'm not going to do them by hand because ain't nobody got time for that. 
So I'm going to head to the top of the note, hit the enter key a couple of times to 
make some space, add my cursor at the top. I'm going to go over here, hit text generator 
templates, and I love this plugin so much that if it did not exist, I'd have a hard 
time using Obsidian. It does so much more than just generate text. Text Generator 
is an open-source AI tool that brings large language models right into your vault. And 
for those of you who are thinking, "Wait, wait, wait, hold on. I do not want some other 
company, OpenAI or Google Gemini or whatever, having access to my vault," you can use 
local private models that are on your computer. They can be used just like 
any other model with Text Generator. In fact, both of the AI tools I'm going to 
show you in this video allow use for local large language models. But what I love 
about Text Generator is this template... Right here. Templates are what allow 
me to remove friction from my vault. So I created a template which would take the 
entirety of the note, as well as the title, and with a click, generate the front matter 
or the note properties for the entire note. When it comes in, it will always come in 
with a space at the top, and front matter properties don't show up properly unless they 
are at the very tippy top of the note. Like so, here in the created field comes into play 
another plugin that I love, called Templater. Templater allows me to make my 
vault really, really useful, powerful, by putting in little spots where 
you can add in information that is static, such as creation of the note. For example, 
there's so much you can do with Templater. I've just scratched the surface, but in this 
case, I'm using it to automatically put the created date as the file creation date—the 
creation date of the actual note file. To do so, I simply right-click, and if 
you're wondering how I have added in all these lovely colors here and how I've 
done so over here with these buttons, that is from the plugin called Commander. I 
love this plugin because I love to make my Obsidian vault look peaceful and easy on the 
eyes. I'm going to spend a lot of time here. I have a color scheme that I use 
throughout my vault. I'll show you other plugins that I'm using as I move 
through this process—this three-step process of how I made my Obsidian vault 
useful and solved my knowledge management problem. I'm going to click on "Templatized 
Note" here, and it simply assigns the date. You can also see Templater at play in my daily 
note. It's based upon this template. You can see a lot of Templater code here, which makes 
the note show up. Then, the previous note, the note for the next day, and even assigns a 
place where my cursor will automatically show up when I click in the note because this is where I 
want to add the task—the first task for that day. The links make it very easy to move through my 
notes by yesterday or tomorrow. And if you're looking at this daily note and would like to have 
this for yourself, as well as the template which creates the note properties and also the template 
which adds all of the links for your content, that means everything that's in the note, it will 
give you a block of internal relevant links which you can go through and keep what you think is 
worthwhile or trim the block down as you wish. These two templates that generate front 
matter note properties and the links template, along with my daily notes template, 
are available for you to get a hold of right now on my Gumroad shop and remove 
friction from your Obsidian vault too. Because these really were a game-changer for 
me when I struggled so much to make value out of my notes. A lot of the challenge came from 
not actually getting access to my notes later on because I had not properly categorized 
them—just like trying to find a book in the library. You need to have an idea of 
where that book is, and that book needs to be carefully and properly categorized 
so you can find it in the card catalog. I'll show you step three of how I get useful 
information that solves my problems now out of my vault, whether that information is 
stored in just one note or across many notes. Before I show you that, I want to show you how 
I use my Obsidian vault to help me make money, and particularly how I use it to 
create AI automations, how I use it for prompt crafting and prompt chaining, which 
is part of what I do. Also, how I use it to help me in building out my AI Automators Prompt 
Crafting Society, which opens on January 1st. This is a real-life use case for how I 
use my vault. Here is my folder structure, with my basket, where I've shown you that 
everything comes in. This is my personal folder, my professional folder, and my knowledge 
folder. Over here in my I versus AI folder, you'll see my products folder. If you're 
wondering how I have made these lovely icons and colors for my folders, that comes from two 
plugins—Iconize, which is a fantastic plugin, and File Color, which allows you to change your 
files to whatever color scheme you would like. This is the folder for the YouTube notes 
automation I showed you earlier. When I'm building out an automation, there's a lot of 
prompt crafting. For example, this transcript breakdown prompt here. This whole double line 
here breaks up prompts, shows me this is a system prompt and this is a user prompt, and this 
corresponds to this node in the automation where you can see the same prompt here. It's a system 
prompt, and here's the user prompt, and so on. This is called prompt chaining, and when 
I'm working with a very large prompt, like the final prompt in this prompt chain, 
a prompt that is very long like this, I have found that Obsidian is the best 
tool for working with those long and complicated prompts and prompt chains. 
And that's because of one word: Markdown. Obsidian is a markdown editor, and 
Markdown, in case you're wondering, is just a way to format text. In this case, this 
means headers, bullet points, or bolding. All of this here is Markdown, and I have it hidden for 
readability. But Obsidian—which, by the way, I should have mentioned this early—is 
free and allows you to work with Markdown. Now, if you're thinking, "I could not work with 
Markdown. I don't understand what that is," that's where a plugin like the Editing Toolbar comes 
in, which allows you to quickly assign bold, italics, headers, and lots of other things, 
including tables, to your text. Markdown is key. Obsidian and large language models 
make great partners. So, by using this to create N8N automations, which I 
then sell and use for my own problems, every automation I create is for a problem that 
I am personally experiencing. I've created the solution to it and then I offer it to you, 
in case you have the same problem as well. I also use Obsidian to help me make money by 
creating quick-start guides that go with my products. A quick-start guide is another way that 
Obsidian helps me to make money with my vault, by creating a quick-start guide that 
goes with each of the products. This is the one for the YouTube metadata automation. I am able to add images, and I can then turn this 
into a PDF and include this with the product. I also create a notes PDF that goes with the 
product. This basically shows all of the node notes for the automation—so basically 
every node, what it does in the automation, and how to think about it, what gets 
stored in this node, the output data, and the next step. This also goes out to the buyer 
so they can see exactly what they're getting, how the information flows, and also use it as a way to 
learn and perhaps build out their own automations. Also, I use Obsidian to help me build out my AI 
Automators Prompt Crafting Society—from storing the prompts for the images, to helping me build 
out the onboarding, to helping me understand how the profiles work, so that when it's time to 
set up the community, all I need to do is go into the table here, see what I'm going to 
add to the profiles for my members, and get an explanation of those fields so I can quickly 
do so when it comes time to set up the community. So not only do I store notes in my 
vault, I literally work inside my vault. Another neat trick about Text Generator and 
another way that you can bring information into your vault in very few clicks is here 
with this feature for Text Generator called Extractor. I've just added this YouTube video 
link here. I'm going to click on Text Extractor, and if there's anything in that note 
here, it will come up as a file URL. It can work with PDFs, it can work with images 
as an OCR. It can read what's in the image and input that as text into your vault. It can 
do that both with images on your machine and images that you just have a URL for. It 
can also do so with web pages and audio, including all the different formats—m4a, mp3, 
and so on. I'm going to right-click here, click on Text Extractor, and click Convert. 
You can see it takes a second—literally, literally a second—to add this entire transcript 
here, and it's exactly from the video. I'm just going to click "Copy" and you'll 
see here that the entire transcript comes through. But you might be thinking 
this is a mess and nowhere near as neat and organized as this transcript 
I showed you, but with Text Generator, you can simply type in what it is you want to 
do with the text above it—like format this text. You can even use something like "Rewrite text for 
readability," adding paragraphs and punctuation. This is another template that I use in Text 
Generator, and if you would like this template as well, let me know in the comments. If enough 
of you ask for it, I will add it to the product that I've already put up on Gumroad, which has 
these two templates in my daily note template. So, I've covered step one—how 
I solve my problem of having a useful vault by getting information into 
it effortlessly through AI automation. Now, I showed you how to add properties to my 
vault, both through automation or through one click with Text Generator templates. And 
now, I'm going to show you how I process a note and then finally how I get information 
from my vault when I need to solve a problem. In order to process a note, 
everything comes into my basket here. Here is a transcript by Anna Hickman, who has a 
YouTube channel, and she is a very smart person. Her channel is wonderful, and she offers really 
great information, so I would highly recommend giving her a listen. After I watched this video, 
I really wanted to get its benefits into my vault, so I'm going to head down here to the 
bottom, right above the link block, and I'm going to show you Auto Note Mover in 
order to get this file where I want it to go. You might be wondering what system I'm using—what 
personal knowledge management system I'm using. Obsidian is the tool I'm using, but what system 
am I using within that? I'm not using any system. It's basically just a folder system. I looked 
at Zettelkasten, and you'll hear of PARA, and you'll hear of maps of content, and there 
are many different ways to organize your system in a way that works for you. I found 
that the way that works for me are folders. Because I don't ever go looking for notes, I go 
looking for the knowledge in those notes. But if I ever do need to find a note, it's very 
easy because it's pretty simple as to where it's going to be. It's a knowledge note; it's 
going to be in one of these folders. If it's a personal note, it's here in this folder, 
and it's pretty easy for me to find things. For example, this is a sovereign craft note. That 
just means something that I use to earn money, my craft, what I do for a living. And 
I'm going to just hit the tab button here and hit "Sovereign Craft." And when I 
do so, I want you to take a look up in the upper right-hand corner. You'll see this 
pop up here, and you'll see the note has left the transcripts file and is now in my 
"Sovereign Craft" folder, and it is here. This means that I don't bog myself down 
by having a lot of things in my basket that I need to process. It's basically 
a few clicks—just put in whatever the tag is that I've assigned to the 
note, to the folder where I want it to go. I just put that tag in, and 
the note goes where it needs to go. And that's important because, even though 
these folders look like they're here, they're not actually here. These notes aren't 
actually here. They are symlinked here using symlink because they are in a Dropbox folder. 
That's where they come into at the end of any automation I run. This is an automation that 
I run to create all of the metadata for any new product I create on Gumroad. Because I 
have now four different products on Gumroad, the one that's about to go live with 
the templates that I've just shown you. And I found myself again with that same 
old kind of dread, friction feeling of, "Oh, I have to write out this entire 
product description," and I just, again, do not have time for that. So, this adds 
everything I need for the description, and it also adds a frequently asked questions 
page, a section here at the bottom, custom link, a summary, additional details, and it 
even includes an image prompt for... That's how this looks when it's done. This 
is the product page for the templates that I've just shown you. This is the summary. This is 
all of the description that was written by GPT. These are the additional details, the features 
of the product here, and all of this, again, is written by GPT-4. And this is one of the images 
that I create for every product I create—an image of the product being held with a laptop, and 
I also create the box image as well, too. So now we have step one covered—that's 
bringing notes into the vault. We have step two covered—that's categorizing and 
also putting those notes where they go in as frictionless a way as possible. But now we 
need to get that information out of our notes, and that is where Copilot comes in. 
Copilot is a plugin by Logan Yang, and this plugin is awesome. It's really 
wonderful because it turns your entire vault basically into a knowledge base. You can 
query your entire vault and ask it questions, which it will gather from the 
contents of your notes to answer. It's basically the desire to build the ultimate 
AI assistant based upon your personal, and this is the key point, your personal knowledge 
base, while also being privacy-focused. And that's because this one also takes in—and 
I am using GPT-4 with this—but you can use local large language models as well and a 
local index that you use for the questions. So, this one works by heading over here and 
typing in anything that you would want—a problem or a question that you might have. 
And when you realize that you can answer your problems by knowledge you've already gathered, 
it really fuels your fire to gather more useful knowledge and bring it into the privacy 
and safety of your own personal vault. For this, I'm going to ask something about 
business. I've typed in, "What do I need to focus on in my business according to Justin Welsh?" who 
is someone that I have several notes about here, and it will give here some overview. But you can 
also go in further. Like, for example, I know that Justin Welsh talks a lot about systems—creating 
business systems, so I can ask about that. What I love about this response is that it 
is actually referencing real notes. In fact, notes that came into my vault automatically using 
my YouTube notes automation brought in all of the properties, all of the information. And if I want 
to go back into the information and check it out, I just need to click on one of the timestamps 
for the area that is of interest to me, and I can head straight into the video 
from there by clicking on this link. The information that you talk about in the 
chat, that you talk about here, can be turned into its own note. So, you could begin a note 
about the 80/20 principle here, go to YouTube, search for videos about the 80/20 principle, 
bring that knowledge into your knowledge base, and then keep learning by talking about the 
new information right here in your vault. Because here is the deal: 2025 is 
just a few days away. But automated knowledge that you can use to solve 
your real problems—that is here now, right now. And in order to get the most of 
it, you need to understand about automation, how it works, and how you can use it to remove 
the pain and stress and solve your own problems. If you'd like to know how I created the automation 
for this N8N process, where I bring in a YouTube link and it turns into this wonderful 
transcript, that video is on screen right now.