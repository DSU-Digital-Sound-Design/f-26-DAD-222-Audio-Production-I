+++
title = "The Rough Balance: Faders, Panning, and Sends"
outputs = ["Reveal"]
[reveal_hugo]
+++

## The Rough Balance

### Faders, panning, and sends

Most of your mix quality comes from balance, not plugins.

{{% note %}}
Frame the day: this is the lesson that makes Project 3 possible. Mike Senior, the author of the multitrack library we use, allows himself only three tools at the start of every mix: the fader, the pan knob, and a high-pass filter. Today we work the same way.
{{%/ note %}}

---

{{< slide class="stepped" >}}

## A mix is decisions, not effects

- Every fader move answers one question
- **What should the listener pay attention to right now?**
- EQ, compression, delay, reverb can't answer it
- They only support an answer the faders already made
- Wrong balance + plugins = a louder, brighter wrong balance

{{% note %}}
Students have spent three weeks collecting tools. Reset the hierarchy: tools serve balance, not the other way around. If the balance is wrong, EQ and compression just make the wrong balance more polished.
{{%/ note %}}

---

## The static mix

A rough draft made with only three tools:

1. The **fader**
2. The **pan knob**
3. A **high-pass filter**

No EQ moves, no compression, no effects. Yet.

{{% note %}}
This is Mixing Secrets chapter 8. Get the static mix right and many problems you would have reached for plugins to solve simply disappear. The term "static" means nothing moves yet: no automation, one setting for the whole song. Automation is a DAD 322 topic.
{{%/ note %}}

---

{{< slide class="stepped" >}}

## Step 1: rank your tracks

Order of importance to the **listener**, not track order:

- Lead vocal
- Drums (kick and snare first)
- Bass
- Chord instruments (guitars, keys)
- Everything else: doubles, percussion, ear candy

{{% note %}}
The ranking is a musical decision and changes by genre. In a dance track the kick might be number one. The point is to decide on purpose before touching a fader. Ask the class: what would the ranking be for the last song we listened to?
{{%/ note %}}

---

{{< slide class="stepped" >}}

## Step 2: build up from silence

- Pull every fader to **-inf dB**
- Loop a full-sounding section (a chorus, not the intro)
- Bring up track #1, peaking around **-6 dB** on the master
- Add track #2 where it sounds right *against #1*
- Continue down your list, one track at a time

{{% note %}}
Working in ranked order means every decision is a comparison, not a guess. The important things get the space first; the less important things have to fit around them. Demo this live with the bluegrass multitrack before the lab.
{{%/ note %}}

---

## Headroom

If the master meter creeps toward 0 dB:

**turn the tracks down, not the master.**

The space you leave is headroom, and every plugin you add later will need it.

{{% note %}}
Peaking around -6 dB on the master leaves room for EQ boosts, compression makeup gain, and effects returns later in Project 3. Turning the master down instead hides the problem: the tracks are still slamming the bus.
{{%/ note %}}

---

{{< slide class="stepped" >}}

## Trap 1: fader creep

- Something feels buried, so you turn it up
- Now something else feels buried, so you turn *that* up
- Twenty minutes later: every fader higher, master clipping
- And the balance is exactly as bad as when you started
- The rule: **to make something louder, turn other things down**

{{% note %}}
Fader creep is common enough to have its own Wikipedia page. If more than two or three faders have drifted up, the honest fix is to pull everything back down and rebuild from the ranked order.
{{%/ note %}}

---

{{< slide class="stepped" >}}

## Trap 2: louder always sounds better

- Your ears judge louder as better, every time
- More volume = fuller bass and treble (equal loudness, week 1)
- Pick a comfortable monitor volume and **leave it alone**
- Distrust any improvement made by turning something up

{{% note %}}
Any balance seems more exciting when it's louder, even when nothing else changed. Connect back to the equal-loudness curves from the sound-and-hearing lecture. This is also why every A/B comparison later today has to be volume-matched, and why mixing loud for long stretches wrecks both your judgment and your ears.
{{%/ note %}}

---

{{< slide class="stepped" >}}

## Pan with a plan: the center

The stereo field is real estate. The middle is reserved:

- **Kick, snare, bass, lead vocal stay center**
- The power of the song lives in the middle
- Anything with heavy low end stays in the middle

{{% note %}}
Low frequencies carry the energy of the mix; splitting them off-center wastes power and falls apart on club systems and mono speakers. The center is for the elements the song cannot lose.
{{%/ note %}}

---

{{< slide class="stepped" >}}

## Pan with a plan: the sides

- **Hard left and right:** matched pairs
- Two rhythm guitars, doubled vocals, drum overheads
- Splitting a pair wide = instant width for free
- **In between:** everything else finds an off-center home
- Keep the two sides roughly balanced

{{% note %}}
If the hi-hat leans left, let a shaker or guitar lean right. Demo the payoff live: play a mix with everything center, then open the pairs out. Then toggle the master to mono and listen to what survives; a good stereo mix collapses gracefully.
{{%/ note %}}

---

## Sends vs. inserts

An **insert** is a guitar pedal.

The whole signal goes through and comes out changed.

EQ and compression live here.

{{% note %}}
Inserts are for changing that track and nothing else. Students have been using inserts for three weeks without the name; give them the name.
{{%/ note %}}

---

{{< slide class="stepped" >}}

## A send makes a copy

- The copy is mailed to another track holding the effect
- The original stays dry; the copy comes back wet
- You blend the two
- Reverb and delay live here

{{% note %}}
This is the concept underneath the send recipes from the delay and reverb lessons. Project 3 asks them to design their own sends, so they need the model, not just the steps.
{{%/ note %}}

---

{{< slide class="stepped" >}}

## Why bother with the copy?

- **One space, many instruments** — send snare, guitars, and vocal to the same reverb and they share a room
- **One plugin instead of ten** — reverbs are CPU-hungry
- **Separate control** — send level sets how much goes in; the effect track's fader sets how loud the space is

{{% note %}}
Cohesion is the big one: ten separate reverbs is ten different rooms. One shared reverb is a band playing in one place.
{{%/ note %}}

---

{{< slide class="stepped" >}}

## Making a send in Reaper

- Create a track named for the effect
- Set its plugin fully wet: **wet 0 dB, dry -inf** (like the reverb lesson)
- Drag from the source track's **Route** button onto the effect track
- The send level lives in that routing window

{{% note %}}
Demo this live. The drag-to-route gesture is the part students fumble; do it twice, once slow.
{{%/ note %}}

---

## Check against a reference

A/B your balance against a real mix.

**Match the volume first.**

The louder one always sounds better.

{{% note %}}
For Project 3 the reference is the Cambridge preview mix of the same song. Turn the reference down until it feels the same loudness, then compare one thing at a time: where is their vocal versus yours? How loud is their kick?
{{%/ note %}}

---

{{< slide class="stepped" >}}

## Saved for Audio Production II

DAD 322 spends a semester on the rest:

- Monitoring, rooms, and building a reference-mix library
- Compression and EQ used *to hold a balance in place*
- Automation: a balance that changes with the song
- Master bus processing and mastering

{{% note %}}
Explicit hand-off so we don't duplicate 322. Pitch it: if mixing is the part of this class you've enjoyed, that course is where it goes deep.
{{%/ note %}}

---

{{< slide class="stepped" >}}

## Lab: rough balance in 20 minutes

Bluegrass multitrack from the [EQ lesson](/lectures/week-5/eq-multitrack/). Faders and pans only.

- Rank the five tracks; choose your center
- All faders to -inf, loop a busy section
- Build in ranked order, peak around -6 dB
- Pan: what stays center? which pair splits?
- Toggle mono and listen

{{% note %}}
Five tracks: guitar, lead guitar, mandolin, banjo, bass. No drums, so the class has to argue about what deserves the center. No EQ, no compression, no effects. We listen to a few balances at the end and compare choices. While they work, circulate and watch for fader creep; it will happen to someone within ten minutes, which makes a perfect teaching moment.
{{%/ note %}}

---

## Next: Project 3

The first thing you'll do to the *Angels in Amplifiers* multitrack
is exactly what you just practiced.

[Project 3: In-class mixing assignment](/projects/project-3-mix/)

### Resources

- [Mixing Secrets ch. 8 resources](https://cambridge-mt.com/ms2/ch8/) — free raw-balance workflow video
- [LANDR: the static mix](https://blog.landr.com/static-mix/)
- [iZotope: aux vs. inserts](https://www.izotope.com/en/learn/aux-vs-inserts-to-send-or-not-to-send)

{{% note %}}
Introduce Project 3 requirements and the due date (10/23), then let them start the organization steps if time remains.
{{%/ note %}}
