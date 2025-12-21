# My ZMK keyboard 4x4.
This is my my first attempt to build a handwired zmk based keyboard.

The first step is to learn how ZMK works, hence this simple 4x4 ortholinear matrix.

# Step 1. Procure Required HW.
Start cheap, select a cheap microprocessor so when I the magic smoke escapes I can start again relatively cheap, and buy a handful.
(DONE Google TENSTAR ROBOT NRF52840 Development Board Compatible With Nice!Nano V2.0 on aliexpress $4 aussie dollars each.
Had a supply of keys and wire etc.

# Step 2. Build Simple 4x4 matrix and Flash Lily 58 LEFT to it.
Handbuild a simple 4x4 matrix and attempt to put an existing firmware on the microprocessor.
Picked a lily58 at random and tried to flash the firmware.
- Opps cooked one microcontroller, shorted the reset to Vcc must remember to not do that. Figured this out after a few hours attempting to figure
  out why the nice nano folder would not appear. Must remember not to do that.
- 5 processors to go..
- Managed to get the lily58 lhs to install and run on my hardware, worked first time, with all rows and columns appearing to function.
  Who needs a schematic, better to be lucky than good, but I did watch a fair few videos from skottokeebs.

#Step 3. Install ZMK and Create Repo.
OMG Im going nuts.... After about 4 or 5 days of not understanding zmk I did manage to create this repo and it actually compiled to produce an output.
- First build flashed, no good.
- Tried changing a board to nice_nano_v2 in build.yaml. NO improvement (guess anyway.)
- Swapped rows and cols, I think I got this wrong.
