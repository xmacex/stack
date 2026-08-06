# Stack

A stack of 8 fixed-frequency resonant bandpass filters, for Monome Norns. Each filter is one octave apart.

- Use `ENC1` to choose which filter is active

Filter selection can be recorded and played back as a pattern.

- Press `KEY2` to begin recording
- Play with `ENC1` to select active filter
- Press `KEY3` to finish recording and play back pattern
- Play around with your input audio!
- Press `KEY2` then `KEY3` to clear pattern (record empty pattern)

## crow

- CV in `INPUT1` to choose which filter is active
- Gate `INPUT2` to recording/playback, like `KEY2` and `KEY3`
- `OUTPUT1` active filter frequency in v/oct
- `OUTPUT2` pattern triggers
- `OUTPUT3` left output amplitude
- `OUTPUT4` right output amplitude

Stack operates on a stereo input signal.

This is a crow-enabled fork of [the Stack script by cfdrake](https://github.com/cfdrake/).
 
## Installation

Install via Maiden with the usual `;install https://github.com/xmacex/stack`. The original Stack without crow features is in the community catalog.

Note that after installing you must `SYSTEM => RESET` your Norns before running this script, as it includes a new SuperCollider engine.

## SuperCollider Engine

This script makes a new SuperCollider engine available, `Stack`. Please see `lib/Engine_Stack.sc` for the latest parameter definitions.
