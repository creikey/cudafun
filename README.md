# cudafun
Cool tech I've always wanted to be able to implement since I was young. This repo will have all of my notes on various textbooks/papers, and the implementation of the various algorithms for cuda on linux, with some additional webgpu implementations (and their deployments) for sharing and visibility. I'm aiming to completely reproduce these algorithms from scratch so that I understand them.

## roadmap
- [ ] gaussian splat renderer
- [ ] normal perceptron neural network
- [ ] convnets
- [ ] ORB slam
- [ ] webgpu port of gaussian splat renderer
- [ ] DTAM
- [ ] webpu port of dtam
- [ ] transformers
- [ ] gaussian splat learner
- [ ] ASH paper algorithm
- [ ] webgpu port of ASH rendering and training (train live on webcam in browser)
- [ ] Fast 2d rigidbody physics from scratch using something like XPBD (extended position based dynamics) implemented on cpu then implemented with cuda
- [ ] Cool looking 3d ocean with a good spectrum and fast inverse fourier transform, good shading. Probably raymarch it?

## reference material and progress through it (roughly in the order and grouped by what is necessary to implement the above software)
- (cudaguide) For cuda in general [Official Cuda Guide](https://docs.nvidia.com/cuda/cuda-c-programming-guide/index.html) - 1.2 (2/130) 1.53%
- gaussian splatting paper - 0%
- (linearalg) linear algebra done right (I own this in print) - (2/31) = 6.45%
- (parallelcomp) For parallel computing theory [Programming Massively Parallel Processors: A hands-on approach](http://gpu.di.unimi.it/books/PMPP-3rd-Edition.pdf) - 0%
- (dlbook) For perceptron, convnets, and RNNs [deep learning book](https://www.deeplearningbook.org) - 0%
- (mvgeobook) For orb slam [Multiple View Geometry in Computer Vision](https://www.r-5.org/files/books/computers/algo-list/image-processing/vision/Richard_Hartley_Andrew_Zisserman-Multiple_View_Geometry_in_Computer_Vision-EN.pdf) - 0%
- Orb slam original paper - 0%
- DTAM original paper - 0%
- attention is all you need paper for transformers - 0%
- (cgoverview) computer graphics overview and refresher[Fundamentals of computer graphics](https://theswissbay.ch/pdf/Gentoomen%20Library/Computer%20Graphics/Fundamentals%20of%20Computer%20Graphics%20--%20Peter%20Shirley.pdf) - 0%
- ASH paper - 0%
- (gamephys) To get the gist on game physics overall [Game Physics Engine Development](https://www.r-5.org/files/books/computers/algo-list/realtime-3d/Ian_Millington-Game_Physics_Engine_Development-EN.pdf) - 0%
- Position based dynamics paper by Muller - 0%
- XPBD by Muller - 0%
