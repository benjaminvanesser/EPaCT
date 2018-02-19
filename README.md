# EPaCT (Electronics Performance and Composition Tool)

EPaCT is a simple tool for live electronics performance and composition. It includes some basic yet popular effects used in contemporary electronic and electro-acoustic music.

Hover the cursor over the effects and its parameters to get more information on what is is, what it does and how you can control it.

installation

EPaCT is MacOS only for the time being. Simply open the .dmg and drag EPaCT to your applications folder. When opening the app for the first time you might see the following warning: EPaCT is damaged and can’t be opened. You should move it to the Trash. This is MacOS Gatekeeper which, for safety reasons, prevents the app from starting. EPaCT is however totally safe to use. To bypass this message, open terminal.app and type: "sudo spctl --master-disable" and enter your password. Now you should be good to go.

audio status

Click 'audio status' to configure your input and output device. Click the speaker icon to activate EPaCT.

Thru

Click 'Thru' to connect the 'dry' input sound directly to the output (this is called throughput). The slider controls the throughput volume.

Preset

Save and recall parameter presets

Input

Configure the input source (microphone or sound file). When 'soundfile' is selected, click 'open' to select a file (.wav or .aiff). Use the 'play/stop button to to control the playback. Click 'loop' to loop the sound file.

Output

You can record EPaCT's audio output. To do so, specify the output's file format, click 'open' to chose a location to which the file will be saved once recorded. Click 'record' to start recording EPaCT's output.

Mapping

You can use the keyboard to control the effects. The controls are all roughly layed out to match a diagonal 'strip' of keys, ranging from the number keys to the lowest 'letter row'. 

All effect parameters can be automated. This means that you can record all your actions on the keyboard and play them back. In other words, the effect's parameters will move by themselves once you start playing back the actions you recorded earlier. To do this, press the corresponding number key (see notes below) to start recording your actions, press the same key once more to playback automation, press it once more to stop automation playback. Audio has to be enabled to use the feature.

What follows is a description of the keyboard layout. This works for both azerty and qwerty keyboards. the key(combinations) are mentioned in that order:

Reverb: 

a/q: toggle effect on/off
q/a: reverb up (+ shift key: volume up)
w/z: reverb down (+ shift key: volume down)
&/1: automation

Delay: 

z/w: toggle effect on/off
s: delay time up (+ shift key: volume up)
x: delay time down (+ shift key: volume down)
x+s: toggle simple or multitap mode
é/2: automation

Freeze:

e: toggle effect on/off
d + shift key: volume up
c + shift key: volume down
c: toggle freeze
"/3: automation

Looper:

r: toggle effect on/off
f: loop speed up (+ shift key: volume up)
v: loop speed down (+ shift key: volume down)
f+v: change direction
t: record loop
g: playback loop
b: stop loop playback
g/b: rest loop speed
'/4: automation

Stutter:

y: toggle effect on/off
h: stutter speed up (+ shift key: volume up)
n: stutter speed down (+ shift key: volume down)
h+n: trigger stutter
§/6: automation

Pitchshifter:

u: toggle effect on/off
j: pitch up (+ shift key: volume up)
,/m: pitch down (+ shift key: volume down)
è/7: automation

Bitcrusher:

i: toggle effect on/off
k: sample up (+ shift key: volume up)
;/,: sample down (+ shift key: volume down)
è/7: automation

Random

Random allows you to randomize all effect parameters available in EPaCT. Set Random to react automatically (auto) or to trigger on the input's volume (input). The dial respectively edits the automatic randomization's trigger interval (ms) and the input's treshold (dB). Use the 'p key' on the keyboard to select random's mode.

Patch created by Benjamin Van Esser (2018) | Commissioned by KCB

