# Welcome to the HEM Sound Library.

The HEM Sound Library (HEM SL) is an open-source collection of sound samples in WAV and Ableton Live format.

HEM SL contains many beautiful instrument-based sounds and textures, ready for use in any genre of music.
It also contains some rather more curious artefacts like [studio outtakes](http://google.com), [noise reduction artefacts](), 
[condenser mic feedback](), [no-input mixer](), and [secondhand-store vinyl]().

HEM SL also includes generative sample playback engine for Ableton Live.

## Getting Started

You're probably looking for what's in the `Sounds` folder. Each sound in there has a `Swatches` folder which contains ready-to-play texture files
illustrating a bit of what each sample pack can do.

## Using with Ableton Live

## Contributing

The best way to contribute is to fork this repository, add a folder of sounds, and submit a pull request.

Ideally, your contribution will look like the other sub-folders under `Sounds`:

    MySound

    - README.md

    – cover-art.jpg [optional]

    – Ableton [optional]
    –– Ableton Project Info
    –– MySound.als
    –– Base Sampler.adg
    –– Sound 1.adg
    –– Sound 2.adg
    –– Sound 3.adg
    etc..

    – Audio [swatches]
    –– WAV File 1
    –– WAV File 2
    –– WAV File 3
    etc..

    – Swatches
    –– WAV File 1
    –– WAV File 2
    –– WAV File 3
    etc..

    – Scripts [optional]
    –– package.json
    –- README.md
    –– index.ts
    –– lib
    --- my-fancy-middleware.ts|.sc|.pd|.whatever

If you are adding Ableton-specific devices then make sure you have a proper project file in there *however*
move your audio files to the `Audio` folder so non-Ableton users can easily find your audio files! "Sound" here, 
of course, refers to whatever type of Ableton device rack you've got wired up to play back your samples.