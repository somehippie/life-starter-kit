# Drone: lessons

| Lesson | Why it tends to hold | How to apply it |
|---|---|---|
| Learn in a simulator first | Crashes are free, and the stick skills transfer | Start with a general FPV sim, then switch to one that models your type of drone |
| Buy the radio first | It is both your simulator controller and your real controller | Choose one that works as a USB joystick and matches your drone's receiver protocol |
| Read the source, not the forum thread | Issue comments and forum replies are leads, not confirmation | For "does feature X work on my hardware", check official release notes or the build configuration |
| Budget hardware can lose features in firmware updates | Radios with little storage get features compiled out of newer firmware | Before updating, check which features are excluded for your specific model, not just what the release adds |
| Write down why you are on a firmware version | A later update can undo the reason you flashed it | Keep a one-line note: version, date, and why |
| When a feature disappears, check the default first | The basic mode often already covers what you actually need | Try the simplest setup before hunting for workarounds |
| If one flashing method fails, try the other | Radios often offer two update modes (for example DFU and mass storage) | Switch methods before assuming the radio or cable is broken |
| Confirm changes on the device itself | The computer can report success while the device did not change | After flashing, check the version and saved models on the radio |
| Fix simulator feel in the simulator | Changing the real radio setup for the sim can carry over to real flights | Use the sim's own settings or a separate sim-only model, and keep the flying model untouched |
| Do not copy a throttle curve from a different size of drone | A tiny whoop hovers far lower on the stick than a 5-inch drone | Put the curve's midpoint near where your drone actually hovers |
| Check exact specs on small parts | Screws, props and connectors look alike across models but differ | Match screw size, prop mount and battery connector to your frame's spec sheet |
| Read the bundle variant before checkout | "Developer kit" listings can mean unassembled parts that need soldering | Pick the ready-to-fly or pre-built variant if you want to fly straight away |

## What did not work

| Tried | What went wrong | Do this instead |
|---|---|---|
| Updating radio firmware for its new features | The update removed a joystick mode the older version had been installed for | Check what your exact model loses before updating |
| Treating forum comments as confirmation | The answer turned out to be in the firmware build file, not the thread | Go to the source for anything you will act on |
| Ordering a generic spare screw pack | It was the wrong thread size for the frame | Order spares listed for your exact model |
