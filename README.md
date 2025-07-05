# XMIL
Imitation Learning for Humanoid


### Downloading the SMPL model
- Download the SMPL parameters from [SMPL](https://smpl.is.tue.mpg.de/) -- only the neutral body parameters are required (it's the middle link under "Download").
- Rename the file containing the neutral body parameters to `SMPL_NEUTRAL.pkl`.
- Place the file in the `data/smpl` directory.

### Downloading and processing AMASS Dataset
- First, download the AMASS dataset(https://amass.is.tue.mpg.de -- it's the SMPL-H dataset).
- Then, run the following script on the unzipped directory:
```bash
python src/utils/convert_kit.py --path <path_to_kit_dataset>
```
