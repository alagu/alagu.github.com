---
layout: post
title: Alexa to personalise yoga routine
---

I've learnt Yoga through several training sessions (Bihar School of Yoga, Trainers and Cult.fit) and have been doing Yoga for past 10 years. But one thing that has been hard is to create a disciplined routine.

### Why routine?

- Habit building: The moment you wake up and think "what asanas should I do today?", it reduces chances of making it a habit. Activities like running have a benefit - you don't need to think. Just run. I wanted the habit to be as less friction as brushing my teeth.
- Benefit of compounding: Health is something that gives compounding returns when you do it consistently. I've been inspired by my Uncle (healthiest among his siblings) who has been doing Yoga for past 30 years. He spends 1 hour every day, fixed routine.

One negative effect of routines is that it might end up becoming monotonous/boring. But it hasn't happened so far for me.

### Using Alexa

Having phone while doing Yoga has never worked, I get distracted. I had to get rid of my phone. Alexa helped there. Alexa Developer console allows you to write custom skills and run it on your own devices.

I created my own Yoga routine that would play as a mp3 in Alexa using SSML (Speech Synthesis Markup Language). You can use [tts-cli](https://github.com/g4spow/tts-cli) (which internally uses Amazon Polly) to convert this to mp3 (I used voice Aditi to read Hindi sentences). It goes through each asana what I specifically want to do and reminds to Inhale and exhale.

Sample Snippet:

    <speak>
    <break time='1s' />Get ready for वीरभद्रासना on right leg <break time='5s' />
     Exhale  <break time='2500ms'/>
     Inhale  <break time='2500ms'/>
     Exhale  <break time='2500ms'/>
     Inhale  <break time='2500ms'/>
     Exhale  <break time='2500ms'/>
     Inhale  <break time='2500ms'/>
     Exhale  <break time='2500ms'/>
     Inhale  <break time='2500ms'/>
     Exhale  <break time='2500ms'/>
     Inhale  <break time='2500ms'/>
    5 <break time='2500ms'/>
    4 <break time='2500ms'/>
    3 <break time='2500ms'/>
    2 <break time='2500ms'/>
    1 <break time='2500ms'/>
    </speak>

This has helped me get into routine significantly because I've iterated on several versions of my routine. Starting with long sessions, removing some asanas, adding meditation, adding breathing exercises. It has served me quite well.

### What you get finally

https://www.youtube.com/watch?v=KYaA0c-ZaYc

And then it starts playing your audio: https://github.com/alagu/yoga-trainer/raw/master/short.mp3

In the above audio it does feel like Alexa is angry :-) I've improved the audio by adding pleasing background music using Audacity to make it less boring.

Resources if you'd like to setup similar for you:

1.  [Alexa Play Skill \[node.js\] - Github](https://github.com/alagu/alexa-mp3-play)
2.  [Generating Yoga mp3 using SSML \[Ruby\] - Github](https://github.com/alagu/yoga-trainer)

I've used similar Play Skill to stream Hello FM from Chennai and to play Lullaby for my daughter.
