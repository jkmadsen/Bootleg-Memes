# Bootleg-Memes
Google App built directly on top of the Google Docs Translate Add-On example that iteratively re-translates text, for the sake of memes.

# Installation
This Google App is supposed to be used as a Docs Add On.  I don't want to even try to publish it as A) it looks like a hassle B) Google probably won't publish an almost literal copy of one of their examples C) I don't want to come up with a logo.  So the installation is manual, and pretty crappy.

1) Create a new document in Google Docs.  Name it something you'll remember, like "Bootleg Memes".  
2) Hit Tools -> Script editor.
3) Delete whatever text you see in the auto-generated file.  Copy-paste main.js into this file.  When you save, it will ask you to enter the project name.  Write whatever you like - I did "Bootleg Memes".
4) Make a new html file (File -> New -> HTML File) called "sidebar" (or whatever you want), delete whatever is automatically written in the file, and copy paste sidebar.html into it. Save that.
5) Now, if you return to the tab with your Google Doc and refresh, Bootleg Memes (or whatever you named the project) should appear in the "Add Ons" drop down (between help and tools).

Maybe some day I'll figure it out, but basically this add on is now installed -only- for this single file.  This is why I said to name it something you'll remember - if you want to use the tool, you have to come back to this document unless you want to go through installation again...or if you're smarter than me and know how to expand the App's scope to all of your documents.

# Use
Hit Add-ons -> Bootleg Memes -> Start
Select source and destination languages
Use the slider to adjust the number of iterations - or type the desired number in directly (1 - 100)
Hit translate
The mangled text now sits before you

# Tricks
Interpret (e.g.) English source text as some other Roman-typed language (e.g. German).  For example, I started with the Tragedy of Darth Plagueis the Wise in English.  I chose German as source language, Chinese (Traditional) as destination language, and iterated 26 times.  The result was:
Hast du von der Tragödie von Schädlingen gehört? Ich denke nicht. Dies ist nicht die Geschichte, die Jedi dir erzählt hat. Dies ist die Legende der Sith. "Prag" ist der dunkle König der Sith. Er ist sehr stark und schlau. Er kann Assassinen benutzen, um sein Leben zu erschaffen. Die dunkle Seite der Polizei ist, was viele Leute über nicht-natürliche Fähigkeiten denken. Er wurde so mächtig ... Das Einzige, woran er sich Sorgen machte, war, seine Kraft zu verlieren, natürlich verlor er seine Kraft. Leider brachte er seinem Lehrling sein Wissen bei, und dann tötete ihn sein Lehrling im Schlaf. Ironischerweise kann er andere vor dem Tod retten, aber nicht sich selbst

Which I ran throgh regular ol' Google Translate to yield

Did you hear about the tragedy of pests? I do not think so. This is not the story Jedi told you. This is the legend of the Sith. "Prague" is the dark king of the Sith. He is very strong and smart. He can use Assassins to create his life. The dark side of the police is what many people think about non-natural abilities. He became so powerful ... The only thing he worried about was losing his power, of course he lost his power. Unfortunately, he taught his apprentice his knowledge, and then his apprentice killed him in his sleep. Ironically, he can save others from death, but not himself
