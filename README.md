# Free small FFT in multiple languages

Copy from: https://www.nayuki.io/page/free-small-fft-in-multiple-languages

## Introduction

The fast Fourier transform (FFT) is a versatile tool for digital signal processing (DSP) algorithms and applications. On this page, I provide a free implementation of the FFT in multiple languages, small enough that you can even paste it directly into your application (you don’t need to treat this code as an external library).

Also included is a fast circular convolution function based on the FFT. Note that the FFT, with a bit of pre- and postprocessing, can quickly calculate the discrete cosine transform (DCT), which is used in many multimedia compression algorithms.

My implementation has a reasonable amount of optimization (such as building trigonometric tables), but is not intended to squeeze every last drop of performance. Instead, the implementation is optimized for clarity and conciseness. You’re welcome to add more optimizations on your own if you wish.

## more content please see "Free small FFT in multiple languages.pdf" or https://www.nayuki.io/page/free-small-fft-in-multiple-languages
