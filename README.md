# Find title of song that is on your mind
building AI course project
## Summary
It is iritating to have a piece of a melody or a song on you mind and not knowing the title ,the artist, date of release etc.
I want to make an AI based recognition system to find the rest of the song or melody. You just tap on the microfon (beat), or sing (or just make some noise that remind you of that song if you can not remember the words) and the AI method comes whith the song or songs that resembles best.
## Background
having a piece of a song in ones head whithout knowing where it comes from is a very common little problem that many people have from time to time, so why dont solve it.
## How is it used?
An example, lets say I have speculated the whole week about a melody: na na na na  nanana, I tried to ask people what is the name of the song but nobody can help. So I open my smartphone and sing na na na na nanana, and it imidately come up with a solution. Its from 'the ghostbusters'.
Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)
If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">
This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]
   totPop = sum(pop)
   totFish = sum(fishers)
   # write your solution here
   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%
main()
```
## Data sources and AI methods
I wold ofcourse need a big library with music. Then I would compare the music i was thiking about with a song. Fitst from the beginning, then I would move my song one tenth of a secondforward and compare again the do it again and again until the song I was thinking about would end at the same time as the songin the library. The I would compare my song the same way to every song in my library.
The I would use the nearest fi qualifier to choose the song that fit best.

If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |
## Challenges
What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?
## What next?
How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 
## Acknowledgments
* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
