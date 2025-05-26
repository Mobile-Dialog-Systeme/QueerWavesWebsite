# Queer Waves

Welcome to the official website of Queer Waves Corpus, a German Speech Dataset Capturing Gender and Sexual Diversity from Podcasts and YouTube
German-language podcasts.

## 🎙️ Podcast and Youtube Sources
The corpus includes over 350 hours of audio from 400+ self-identified LGBTQIA+ speakers, spanning ages from 18 to 86 years from all over Germany and Austria.

## 🔧 Processing Pipeline
- **Collection**: Curated podcast selection
- **Preprocessing**: Format conversion and segmentation
- **Transcription**: OpenAI Whisper
- **Diarization**: Speaker segmentation (1–4 speakers)
- **Annotation**: Gendered expressions, community terms
- **Validation**: Manual spot checks and metadata curation

## 📂 Available Data
We provide:
- Podcast and episode metadata (JSON)
- Annotation scheme (Gender identity, sexual orientation, age, speaker region)
- Automatic Processing Pipeline descripion + scripts(if available)
- Example transcripts (JSON)
- Metadata overview
- Documentation

> ⚠️ The full dataset is only available **on request** for non-commercial academic use.

## 📊 Corpus Statistics
- **Total Audio**: 335 hours
- **Speakers**: 400+
- **Episodes**: XXX
- **Languages**: German (main)

## 📝 Sample Entry
```json
{
  "episode_id": "ep_045",
  "title": "Queer Voices in Berlin",
  "speakers": [
    {
      "id": "spk_01",
      "gender": "non-binary",
      "segments": [
        {
          "start": "00:00:05",
          "end": "00:02:15",
          "transcript": "Welcome to our discussion on queer identities..."
        }
      ]
    }
  ]
}
```

## 📥 How to Get the Data
1. Contact us: [ingo.siegert@ovgu.de](mailto:ingo.siegert@ovgu.de)
2. Describe your academic use case
3. Sign the [Data Usage Agreement](license.html)
4. Receive access credentials

## 📄 License
- Website & Documentation: **CC BY-NC 4.0**
- Corpus Data: Available only under a **research-only usage agreement**

## 📚 How to Cite
> Siegert, I., & Mustermann, A. (2025). *Queer German Podcast Corpus (QDPC)*. Zenodo. DOI: 10.5281/zenodo.1234567

## 👥 Authors
- **Ingo Siegert** 
- **Sven Grawunder**
- **Jan Marquenie** 
- **Taylor Kim**
