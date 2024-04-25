# yoga-slim-7-gen8-amd
Documentation for the flaws and workarounds of this laptop


Known Issues:
- protruding power button on the side leads to accidental shutdowns when the button is long pressed, even if the lid is closed. Happens by accident when putting it into a bag.
- The holes in the bottom cover for the air intake have just the right diameter and shape to start whistling like when you blow on a bottle top
- terrible fan curve + a fan controller not visible to the OS, cannot be controlled

Linux specific:
- does not go into s2idle, does not have s3: partially fixed, acpi override at boot required
- only tweeter works: fixed by darnip
- battery health feature to only charge to 80% at night does not work
- IR face recognition does not work with howdy
- cannot wake laptop from sleep with external mouse/keyboard or power button when connected to monitor and lid is closed. You have to open the lid.

