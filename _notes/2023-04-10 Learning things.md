# Starting the biodata sonification build (Learning Things: April 10, 2023)

[[I asked a LLM to create paranormal investigation tools for me]]

[https://www.buriedsecretspodcast.com/starting-the-biodata-sonification-build-learning-things-april-10-2023/](https://www.buriedsecretspodcast.com/starting-the-biodata-sonification-build-learning-things-april-10-2023/)


Biodata sonification supplies and Erik Satie-inspired automatic drawings

Another Monday, another [rundown of what I've been learning and working on](https://www.buriedsecretspodcast.com/diy-rem-pod-initial-build/). Here's what I've been up to:

## Paranormal research
This week, I've been working on the next podcast episode, which drops Friday. I'll be diving back into the 1897 mystery airships that [I mentioned last time](https://www.buriedsecretspodcast.com/a-ufo-crash-in-aurora-texas/). Specifically, I'll be talking about more airship sightings in North Texas. So stay tuned for that.

## DIY paranormal gear
I've got a couple things to report here. First, I [wrote about some of my ChatGPT-related experiments last week](https://www.buriedsecretspodcast.com/i-asked-chatgpt-to-create-and-code-paranormal-investigation-gear-for-me/), so that was a whole thing.

And I also ordered supplies for the DIY biodata sonification device I want to try to make. In the spirit of transparency (since so many DIY paranormal builds are a little . . . opaque . . . to beginners), here are my notes on my initial planning and what I purchased. I'm sure I'm making mistakes here, but hey, maybe some of this will be useful to someone in the future!

### Resources
I'm planning to follow the [Biodata breadboard kit instructions](https://electricityforprogress.com/biodata-breadboard-kit/). Here's the basic description:
> In this simple breadboard circuit there are 11 jumper wires and 10 components!! Using a 555 timer, we first build the Biodata circuit, which detects microcurrent fluctuations across the surface of a plant’s leaf. This Bio-Signal is sent into an Adafruit ESP32 Feather (Huzzah) where the changing electrical signal is translated into Musical Notes which can be used with MIDI synthesizers and sent over Bluetooth to phones and computers!

### Supplies
This is the supply list that I made for myself. I based it on the [instruction presentation](https://electricityforprogress.com/biodata-breadboard-kit/) on Electricity for Progress and the [bill of materials on github](https://github.com/electricityforprogress/BiodataFeather/blob/master/BiodataFeather_BOM). 

There were some items that I saw on the BOM but not on the instructions, and vice versa. I was unsure if they were different or if I just missed something, but the components were cheap enough that I just ordered them anyway.

However, this does make me wonder whether the instructions I read are for a slightly different build than the github code was written for (though both are definitely for the Adafruit Feather ESP32 Huzzah). If I understood this stuff more, I might be able to tell by looking at it, but as previously mentioned, I am somewhat clueless and I think I'll only be able to figure it out by trying it. 

It *could* be that the github instructions are for using the Adafruit Feather with the PCB, whereas I'm planning to follow the breadboard build instructions, which would be different. But I dunno. So I'm filing that away under possible unpleasant future surprises.

#### Here's what I had to buy
- 400mAh rechargeable LiPo (note: the BOM calls for the 2000mAh LI battery; I ordered the 400mAh LiPo from the breadboard instrux)-$6.95
- Adafruit Feather ESP32 (I'll need to program this, but the code appears to be on [Github](https://github.com/electricityforprogress/BiodataFeather), so I should be good there? I just gotta, you know, learn how to load that up. Also, the BOM led me to an unsoldered version, but I ordered the pre-soldered board from Adafruit because I *think* the breadboard build needs the headers installed to work.)-$20.95
- snap electrodes (I think this refers to the electrode wires)-$6.99 for a pair
- 3 pairs of sticky TENS pads-$5.14 for 4 pairs
- 3.5 mm jack-$0.85/per
- 4700pf capacitor-$0.26/per
- 3.9K resistor (orange/white/red)-$0.10/per
- 10 ohm resistor (brown/black/brown)-$0.10/per
- 8-pin 555 timer IC-$1.69/per
- tactile switch(es)—I'm slightly hazy on how many of these I need, so I ordered a few, though I also have some extras already that might work too-$.13/per
- 5KV transistor 4DIP (this appeared on the BOM, but I didn't notice it in the instructions. I ordered it anyway; the exact part is sold out, so I [ordered a substitute](https://www.digikey.com/en/products/detail/panasonic-electronic-components/CNC1S171S0LF/970639#product-details-substitutes).)-$0.90/per
- DC converter (saw on the BOM but not in the breadboard instructions)-$3.25
- 10K ohm 1/20W potentiometer (another one that I only saw on the BOM.)-$0.98

#### I already owned
- breadboard
- jumper wires
- 5 LEDs (red, orange, green, blue, white)
- CRR2032 3V battery (for testing LEDs)
- microUSB cable (to charge/power device)
- computer (will use as the midi synthesizer; planning to use a free/open source DAW, but not sure which one yet—can be figured out later on)
- plants

#### Optional/nice to have in the future
- enclosure (there are CAD drawings on github)

#### Other notes
- For some components, I was unsure of the quantity, so I ordered extras of the small/cheap stuff.
- I ordered most components from DigiKey, except for the Adafruit stuff, which I ordered directly from them, and the electrodes, which I got from Amazon.
- Things to keep in mind while budgeting: As of right now (April 2023), DigiKey charges a ~$6.99 shipping fee plus a tariff (which was less than two bucks for me). Adafruit shipping was ~$14.00.

### Expected future pitfalls
- How do I program this thing? (I actually played around with it some already, and after fighting with some error messages and such, I *think* I've got my Adafruit Feather programmed. I at least got the sketch uploaded with no error messages. We'll see if I actually did it right.)
- Is the github info for the same build as the instructions I'm planning to follow? If not, will the code still work? (Since they're both for the same Adafruit Feather, I *think* it'd be fine. But we shall see.)

## Art and paranormal investigation

This week, I tried a quick automatic drawing experiment that didn't yield amazing results, but which gave me some takeaways.

Here's what I did:

A few weeks ago, I [mentioned](https://www.buriedsecretspodcast.com/diy-rem-pod-initial-build/) that I wanted to listen to the *Satie - Fragments* album (electronic remixes of Erik Satie's work) on repeat while trying automatic drawing. So first I meditated in silence for 5 minutes. 

Then I listened to [Grandbrothers remix of Erik Satie's Gnossienne No. 1](https://www.youtube.com/watch?v=WD9mP_smNgY) and did the automatic drawing. I set a timer for 10 minutes, chose the colors at random, and moved on from the first drawing to the second one once it felt right. I drew with my eyes closed, and I tried to keep my mind blank and/or open to communication with any entities who were present. 

When I looked at the resulting drawings, they definitely made me think of specific things (rather than just looking like random scribbles). But they still didn't mean much to me. 

A couple things I want to do differently: 
- use a canvas that covers the whole iPad screen (out of habit, I've been selecting Procreate's default square canvas)
- rather than choosing colors randomly, but with my eyes open, I'm curious what would happen if I closed my eyes and chose hues from the color picker that way
- I wonder if I need to set a more concrete intention than just wanting to communicate.

I'm still not sold on doing automatic drawing digitally versus with traditional, physical mediums, but I want to keep playing around with it.

## Writing
This week, I got to the end of my first revision of the queer solarpunk fantasy romance novel I'm writing, and now I need to pause and fix some major issues that I've been ignoring. Those include (in no particular order): 1) make the [MacGuffin](https://en.wikipedia.org/wiki/MacGuffin) work better from a worldbuilding perspective, 2) flesh out the magical system that's alluded to in the story (there's some fae magic), 3) rework the main antagonist's backstory and motivations, and 4) refine/better define the two point of view characters' arcs. 

All important things, all things that I've been putting off for various reasons. So I expect to feel frustrated this week. We'll see.

## Outro
So what do I have in the hopper for the week ahead? I *might* start putting the components onto the breadboard for the biodata sonification project this weekend, now that I've (hopefully) got the sketch uploaded to my Adafruit Feather and I'll have the rest of the components by the weekend. 

I've realized that after this biodata sonification build (or maybe during, if I get stuck), I need to do some simple Arduino projects to improve my knowledge of C++, just because I don't really know enough to debug when something simple goes wrong. 

I did ask [ChatGPT for help with some of the error messages that popped up](https://www.buriedsecretspodcast.com/i-asked-chatgpt-to-create-and-code-paranormal-investigation-gear-for-me/), which was helpful, even though it didn't actually *fix* my problem. It explained some basic stuff. (*Really* basic, like telling me that specific errors meant something needed to be added to a header or a library needed to be downloaded. But because I'm clueless, that info helped me better understand how sketches and the Arduino IDE work.) But it seems like I shouldn't rely on it for anything too specialized.

I'm also reading *Operation Trojan Horse* by John Keel, which has been pretty helpful as I've prepared this week's episode. There's lots of interesting stuff in there; I'll almost certainly blog about some initial takeaways from that this week.

Anyway, that's what I've got on the docket! We'll find out next week what I actually get done.

[[2023-04-04 automatic drawing session]]
[[plantwave dupe V1 component details-adafruit]]