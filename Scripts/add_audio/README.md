# Add Audio

**Version:** 1.4.0  
**Flame Version:** 2023  
**Author:** Michael Vaglienty  
**Created:** 2022-02-04  
**Last Updated:** 2024-01-20  
**Custom Action Type:** Batch

---

## 📖 Description

This script adds **stereo** or **5.1 surround** audio to selected Flame sequences.

### Stereo Audio

- To add stereo audio to a sequence, select the sequence, then select the audio clip to be added.
- To add stereo audio to multiple sequences, select in the order:  
  `sequence → audio → sequence → audio → ...`

### 5.1 Surround Audio

- To add 5.1 surround audio to a sequence, select the sequence followed by all the audio channels:  
  `LF, RF, C, LFE, LS, RS, Stereo`
- To add 5.1 audio to multiple sequences, select in the order:  
  `sequence → all audio channels → sequence → all audio channels → ...`

> 📝 **Note:**  
> The order of 5.1 files does **not** matter during selection.  
> When added to a sequence, they will be ordered as:  
> `LF, RF, C, LFE, LS, RS, Stereo`

5.1 file names must end with: `_LF`, `_RF`, `_C`, `_LFE`, `_LS`, `_RS`, or `_Stereo`.  
**Case-insensitive.**

---

## 🧭 Menu Location
