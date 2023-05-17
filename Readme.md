# Custom keyboard
This project arrises from a need of mine for good quality, comfortable and
cheap keyboard. From my research, there is no keyboard that satisfies all
criterion. My dream keyboard type is way too expensive for me to buy. Luckily
for me, I'm an engineer, so I can build it myself, for a fraction of the price.

## Requirements
I recently switched to Colemak as my layout, so my keyboard has to support that
natively. Also, I am a soft-core gamer, and most games are build with qwerty in
mind. I want to be able to toggle the layouts quickly. Also, the standard
keyboard is not comfortable, I'd like a keyboard that supports tilting. Additionally,
the layout will be column staggered. I often use the function keys, numbers
and HOME, END, DELETE and ARROWS. Finally, I want to try mechanical keyboard
because I heard that it is easier to maintain/repair.

## Inspiration
I really like moonlander keyboard design, but it is way too pricey. I will use
the thumb cluster idea and similar tilting mechanisms. I also like the idea of
macros. I don't use them now but want to be able to program something in the
keyboard.

## Final Details
Many controllers have analogue inputs. Although, I want to use Brown Switches
now, I want the ability to switch them to optical and game on the keyboard with
linear activation.

## Chosen layout
Keyboard Layout Editor ([link](http://www.keyboard-layout-editor.com/#/)) is a
tool to create custom keyboard layouts. Raw JSON data of layout I chose can be
found in this repo.

Idea is to maybe make the two parts detachable?? For now, I just want a
keyboard, so will just bash it to just work as well as I can. 

I will use Arduino nano, and it has 19 I/O ports. I have only 81 buttons
currently assigned. Therefore, I'll use one analogue signal as output to inform
user of state or something like that.
