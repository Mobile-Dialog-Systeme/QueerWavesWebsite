# 🏳️‍🌈 About Queer Waves

**Queer Waves** is a German speech dataset designed to support the development of equitable and inclusive speech technologies. It features approximately **335 hours of spontaneous speech** from over **400 self-identified LGBTQIA+ speakers**, collected from podcasts and YouTube content. The dataset spans a wide range of **gender identities, sexual orientations, ages (18–86) from speakers all over Germany and Austria**. 

The data collection a strong emphasis on **ethical and legal safeguards**, especially in handling sensitive personal data. By expanding the diversity of voices in speech technology, Queer Waves contributes to building **fairer and more representative AI systems**.

## 📊 Dataset Statistics

Below you find visual insights into the distribution of gender identities, sexual orientations, speaker age, and episode durations in the Queer Waves dataset.

<div style="display: flex; gap: 2%; flex-wrap: wrap; justify-content: space-between;">

  <div style="flex: 0 0 48%;">
    <h4>Gender Identity Distribution</h4>
    <img src="assets/img/gender_identification" alt="Gender Identification" style="width: 100%;">
  </div>

  <div style="flex: 0 0 48%;">
    <h4>Sexual Orientation Distribution</h4>
    <img src="assets/img/sexual_orientation" alt="Sexual Orientation" style="width: 100%;">
  </div>

  <div style="flex: 0 0 48%; margin-top: 20px;">
    <h4>Age Range of Speakers regarding gender identification</h4>
    <img src="assets/img/age_identification" alt="Age Distribution" style="width: 100%;">
  </div>

  <div style="flex: 0 0 48%; margin-top: 20px;">
    <h4>Age Range of Speakers regarding sexual orientation</h4>
    <img src="assets/img/age_orientation" alt="Age Distribution" style="width: 100%;">
  </div>

  <div style="flex: 0 0 48%; margin-top: 20px;">
    <h4>Distribution of amount of material per speaker </h4>
    <img src="assets/img/duration_distribution" alt="Distribution of amount of material per speaker" style="width: 100%;">
  </div>

</div>


## 🎙️ Podcast and Youtube Sources
The following podcasts were included in the creation of the Queer Waves dataset. Where noted, only episodes up to a specific date were used. All content was carefully selected for linguistic and identity diversity and features self-identified LGBTQIA+ speakers.

| **Podcast Title**                             | **Selection Status**      |
|----------------------------------------------|----------------------------|
| Auf eine Tüte: Der Potcast mit Hengameh      | Complete                   |
| BBQ – Der Black Brown Queere Podcast         | Complete                   |
| Bootycall                                     | Complete                   |
| Böttinger Wohnung 17                          | Complete                   |
| Hotel Matze                                   | Until 2024-11-20           |
| Out and About                                 | Complete                   |
| Queer as Berlin                               | Complete                   |
| Queerkram                                     | Until 2024-11-02           |
| Radiomilch                                    | Complete                   |
| Reden ist Gold                                | Complete                   |
| Somewhere Over The Hay Bale                   | Complete                   |
| SPUTNIK Pride                                 | Until 2024-11-08           |
| Willkommen im Club                            | Until 2024-11-20           |

> Dates reflect the latest episode included from each feed at the time of dataset extraction.

## 🔧 Processing Pipeline
- **Collection**: Curated podcast selection using [podcast-dl](https://github.com/lightpohl/podcast-dl)
- **Preprocessing**: Format conversion and segmentation
- **Transcription**: OpenAI Whisper
- **Diarization**: Speaker segmentation (1–4 speakers)
- **Annotation**: Sexual Orientation, Gender Identity, Age and Region based on self-identification
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

## 📊 Dataset Statistics
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
- Dataset: Available only under a **research-only usage agreement**

## 📚 How to Cite
> Siegert, I., & Mustermann, A. (2025). *Queer German Podcast Corpus (QDPC)*. Zenodo. DOI: 10.5281/zenodo.1234567

## 👥 Authors
- **Ingo Siegert** 
- **Jan Marquenie** 
- **Sven Grawunder**
