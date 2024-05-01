# signals

## Signal Enveloping

### Snake Math!
For example:
Given 1-d Signal, A:
- A >> MAX kernel >> MEAN kernel,  and 
- A >> MIN kernel >> MEAN kernel

Looks like this:

![image](https://github.com/kkmcgg/signals/assets/36888812/a380e021-f00f-4b65-9325-293277c57e3d)

### More Snake math!

You can switch the order, for signal A, do
- A >> MEAN >> MAX, and
- A >> MEAN >> MIN

That will look like this:
![image](https://github.com/kkmcgg/signals/assets/36888812/53d2da7f-5c0e-4a93-b5f1-ad606d2b5ac2)

Kinda neat! 
You can of course mess with the kernels for different effects. Tune in next time for how this can be used with images. 

Here you can see it being used with a real signal:

![image](https://github.com/kkmcgg/signals/assets/36888812/d8cebfa4-e30c-4fea-83af-5ddda0ffee27)

## Others (apparently)
- Hilbert Transform
- Peak Detection and Interpolation
- Moving Average or Filtering
- Empirical Mode Decomposition (EMD)
- Wavelet Transform

  ## Future Topics
  - Normalizing Difference Ratio - The famed, magical (a-b)/(a+b)
  - Optimal Transport
  - Ground Plane Detection (dribble?)
  - Hidden Point Removal 
  - MAMBA natworks 
