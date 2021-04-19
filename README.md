# Giant-Steps



To listen to the fruits of my labour, [click here](https://www.youtube.com/watch?v=umTxOUambXw&ab_channel=IanCoulter)

## What is this?

What I am presenting to you is a version of the infamous John Coltrane classic Giant Steps, written entirely using Ruby code.

## How I did it

I'm sure you are thinking 'hold on a minute! It's not possible to write music in Ruby.' Well you are half right. I actually used the code based music creation tool [Sonic Pi](https://sonic-pi.net/).

Created by [Sam Aaron](https://twitter.com/samaaron), Sonic Pi uses the Ruby language to allow users to create music and even perform live.

In my code, I defined 2 methods that dealt with the notes of the music. The first method was 'note_play'. 'note_play' takes 2 arguments that determine the pitch and the length of the note. The second method is 'rest'. 'rest' takes 1 argument that determines the length of rests

In order to keep my code as clean as I could, I divided the melody, bass and harmony into their own separate methods and called them at the end. If I had not done this, my code would have been much messier and more difficult to write. I would have had to take all notes into account all at once with would have caused me a lot of confusion.
