### Disclaimer
**This setup is not a replacement for a professional oscilloscope. Using your sound card for tasks it's not designed for may cause damage to your hardware. Use with caution, and proceed at your own risk.**

---

### Turn Your Sound Card Into an Oscilloscope!

To be clear, this won’t work well due to the low-pass filter commonly applied to sound cards. The waveform shown in the image below actually has a 38kHz carrier frequency, but the filter smoothed it into a constant "one." Even with a 192kHz sampling rate, it still makes for a very poor oscilloscope.

![](Figure_1.png)

To capture this signal, I cut the old guitar cable in half and connected it on one side with the TRS input of the sound card, and another - with the signal source.


### Be Careful with Input Voltage

My sound card supports line-level input (~1.3V) or instrument-level input (even lower). With the gain adjustment, it's possible to capture signals up to 10V, though I haven’t tested higher voltages. Regardless, I’m confident that trying to use this "oscilloscope" with 220V AC will result in your device exploding. Always measure the voltage level before connecting anything to your sound card.
