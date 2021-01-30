### CVPR Workshop: Challenge for Learning Image Compression

[2020 Papers](https://openaccess.thecvf.com/CVPR2020_workshops/CVPR2020_w7)

#### Evaluation Metrics

> The `evaluate()` in `metrics.py` function expects two dictionaries mapping filenames fo filepaths (the target PNGs and PNGs produced by the decoder).

> I attached the code that's used to evaluate submissions. The function `evaluate()` in `metrics.py` receives two dictionaries containing paths to the target PNGs and decoded PNGs. In the video challenge, these are the PNGs representing Y, U, and V channels. One thing to note is that the MS-SSIM is weighted by the number of pixels, so Y is weighted more strongly than U or V.
> - Lucas
