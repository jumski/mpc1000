# Random MPC 1000 tips

## Speed up shortcuts

* SHIFT + PLAY START - move to beginning, SHIFT + PLAY - move to end
* NEXT BAR / PREV BAR = zoom in/out in TRIM mode
* `SHIFT + <BAR>` = move to the next event on the same line
* Q1 button + pad = select track
* MODE button + DATA WHEEL = TRACK - or TRACK +
* NEXT SEQ button + DATA WHEEL = SEQUENCE - or SEQUENCE +
* MAIN shortcut: Hold MAIN + PADn
* NUMERIC shortcut: Hold numeric + PADn (can have 2 shortcuts)
* STOP + PLAYSTART on main will play whole sequence
* STOP + DATA WHEEL = contrast

## Various Tricks

* Finding unused samples with .PAC
  ```
  make sure you start without any samples loaded. if the .pgm is in it's own folder with the samples load the entire folder. go to GPE and hold SHIFT + F2 to PACK the .pgm and all it's samples. head to TRIM mode and make note of which samples are leftover. if you want to keep the leftover samples, go back to GPE and hit SHIFT + F2 to UNPACK and assign unused samples to the program. repack the .pgm, then head to LOAD and delete the folder the .pgm was contained in. save the .PAC file in a PAC folder or something.
  ```

## TRIM and CHOP

* SHIFT + Fkey -> edit options easy available
* PAD3 and PAD7 - reverse playback
* PAD1-4 -> note on preview
* PAD5-8 -> one shot preview
* PAD9 -> play 200ms before START point
* PAD10 -> play region
* PAD11 -> play 200ms before END point
* PAD12 -> play after END point

```
Moreover, a start or an end point can be adjusted, carrying out audition, if a DATA wheel is turned pressing a pad (PAD1-PAD4 and PAD9-PAD12).
If PAD1, PAD2, PAD5, PAD6, PAD9, and PAD10 are pressed, cursor will move to St field.
If PAD3, PAD4, PAD7, PAD8, PAD11, and PAD12 are pressed, cursor will move to End field.
If PAD9-PAD12 and PAD14-PAD16 are pressed, the waveform of a play portion will blink.
It works similarly on the screen of F5 (CHOP).
However, there is no reverse playback of PAD3 and PAD7.
```
