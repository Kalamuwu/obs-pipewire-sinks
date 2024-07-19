# obs-pipewire-sinks

A setup and teardown shell script to create Pipewire sinks for recording with OBS. This allows you to sort your audio streams.

The `obs-pipewire-setup` script creates three sinks: `OBS-Game`, `OBS-Mic`, and `OBS-Chat`. These are so that you can separate out your game audio, microphone audio, and any voice chat or call you might be in.

Link OBS audio devices to the created sinks.
