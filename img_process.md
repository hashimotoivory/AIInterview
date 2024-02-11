## Image Denoising

> Mean Filter
>
> > $$
> > \begin{align}
> > \hat{f}(x,y)=\frac{1}{mn}\sum_{(s,t)\in\mathbb{S}_{xy}}g(s,t)
> > \end{align}
> > $$
> >
> > where,
> >
> > - $g(\cdot)$ is the pixels of an image.
>
> Median Filter
>
> > $$
> > \begin{align}
> > \hat{f}(x,y) = \text{median}\{g(s,t) \mid (s,t) \in \mathbb{S}_{xy}\}
> > \end{align}
> > $$
>
> Gaussian Blur
>
> > $$
> > \begin{align}
> > G(x,y) = \frac{1}{2\pi\sigma^2} \exp\left(-\frac{x^2 + y^2}{2\sigma^2}\right)
> > \end{align}
> > $$
> >
> > The Gaussian kernel generated by this function is then convolved with the image to produce the blurred effect. The kernel size and the value of \(\sigma\) determine the degree of blurring.
>
> Wavelet Transform
>
> > continuous, 
> > $$
> > \begin{align}
> > CWT(a,b) = \frac{1}{\sqrt{|a|}} \int_{-\infty}^{\infty} f(t) \psi\left(\frac{t-b}{a}\right) dt
> > \end{align}
> > $$
> > discrete, 
> > $$
> > \begin{align}
> > DWT_{jk} = \sum_{n} f[n] \cdot \psi_{jk}[n]
> > \end{align}
> > $$
> > where, 
> >
> > - $\psi(\cdot)$ is the wavelet function.
>
> non-local means
>
> deep learning

---

## Image Enhancement

> histogram equalization
> 
> adaptive histogram equalization
> 
> gamma correction
> 
> unsharp masking
> 
> high boost filtering

---

## Edge Detection Operators

> sobel operator
> 
> scharr operator
> 
> prewitt operator
> 
> canny edge detector
> 
> laplacian of gaussian