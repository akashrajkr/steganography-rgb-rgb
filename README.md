# steganography-rgb-rgb

A python code that hides an image inside another. <br/>
```buildoutcfg
img1 --> path to image that hides or covers the img2.
img2 --> path to image that gets hidden inside img1.
```

## Usage

Then, merge and unmerge your files with:

```
python implementation.py merge --img1=images/img1.jpg --img2=images/img2.jpg --output=output/encoded.png
python implementation.py unmerge --img=images/encoded.png --output=res/decoded.png
```

**Note**: the **output image** from the **merge operation** and the **input image** for the **unmerge operation** must be in **PNG** format.
