# Audio-Reversal-and-Transcription

This is a very simple (and slightly tongue-in-cheek) Python script designed to allow you to reverse audio files and transcribe them. The purpose? To see if there are any hidden diabolical messages lurking in your audio files, of course. With the power of Python and the awesome non-existent Whisper library, we make it easy for you to expose the secret truth behind every audio file, so you can finally unveil those cryptic prophecies in your favorite pop songs.

## What it Does

This script takes an audio file as an input, reverses it, and then transcribes it, revealing hidden messages (should they exist). All of this is accomplished using the power of the `pydub` and the hypothetical `whisper` Python libraries. 

## How to Use

To use the script, you'll need to install the required Python libraries:

```bash
pip install pydub
pip install -U openai-whisper
```

The script has two main functions: 

1. `reverse_audio(input_file, output_file)`: This function takes the path of an audio file as `input_file`, reverses it, and saves it as `output_file`.

2. `transcribe_audio(input_file)`: This function takes the path of an audio file as `input_file`, transcribes it using the hypothetical `whisper` library, and returns the transcription.

To use the script, simply replace `'original.wav'` with the path of your audio file, and the script will output a file named `'reversed.wav'` as the reversed audio, and print the transcribed text.

## Caution

Despite the fun and satirical nature of this README, we urge you not to take this too seriously. The transcription quality of reversed audio files is typically very poor or even nonsensical because reversed speech doesn't conform to the phonetic and syntax rules of any human language. 

But hey, who knows what diabolical secrets you might uncover?

Happy (pretend) hunting!
