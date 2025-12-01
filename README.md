# MuASR: Lyrics Transcription and Captioning for Music

[**GitHub**](https://github.com/fakerybakery/MuASR-3B) | [Hugging Face](https://huggingface.co/mrfakename/MuASR-3B)

**Note: this is an early preview of the model, the full version of the model is still training.**

MuASR is an audio-language model based on Voxtral 3B for music lyrics transcription and captioning. It is intended for dataset processing for music generation, as well as general-purpose music transcription and captioning tasks.

## Models

| Model | Parameters | Download |
|-------|------------|----------|
| MuASR-3B | 3B | [Hugging Face](https://huggingface.co/mrfakename/MuASR-3B) |

## Output Format

The model produces structured outputs combining style tags and formatted lyrics:
```
<caption>soft pop, indie, acoustic, piano</caption>
<lyrics>
[Verse]
Walking down the empty street tonight
Stars above are shining bright
Every step I take leads me back to you

[Chorus]
In the silence I can hear your name
Nothing here will ever be the same
Hold on to the memories we made
</lyrics>
```

## Limitations

- The model was trained on full-length songs (up to 4 minutes); however, it may not perform well on extremely long or short songs.
- The model was trained on primarily English data; it may not perform well on other languages.

## Examples

*Coming soon.*

## Acknowledgments

Thank you to Hugging Face for generously sponsoring the compute resources for training this model!

## License

CC-BY-NC 4.0. We hope to be able to release the final version under Apache-2.0.
