# arclidian

Euclidean sequencer for [monome arc](https://monome.org/docs/arc/) made with Max and Pure data

<img src="arclidian.gif" width="600" height="193" />  

This was created with the intention of being an experimental playground for creating patches for arc using Max or Pure Data

The main patch to open is called `arclidian.maxpat`/`arclidian.pd`

### Functions:

- knob 0 - clock multiply/division (Max) / clock BPM (Pd)
- knob 1 - step count
- knob 2 - beat count
- knob 3 - offset

Clock follows Max's global transport tempo (Max)

## Dependecies

- [monome serialosc](https://github.com/monome/serialosc/releases)
- [monome package](https://github.com/monome/monome-max-package) (Max)
- cyclone library (Pd)
- osc library (Pd)
- [`monome-device`](https://monome.org/docs/grid/studies/pd/#prerequisites) object is included (Pd)
