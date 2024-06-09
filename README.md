## Denoising Diffusion Probabilistic Models

Denoising Diffusion Probabilistic Models (DDPMs) are a class of generative models that sequentially transform a simple initial noise distribution into complex data distributions through a series of gradual denoising steps. Each step in the process slightly reduces the noise, guided by a probabilistic model that learns to reverse the diffusion process. This approach leverages the power of both deep learning and probabilistic modeling to produce high-quality, diverse samples, making DDPMs particularly effective for applications in image and audio synthesis. The training process involves optimizing a variational bound on the data likelihood, ensuring that the model captures intricate data structures and patterns.

### Forward Process:

![Screenshot from 2024-06-09 14-58-41](https://github.com/TalalAhmed311/Diffusion/assets/64472176/66c3fa49-a866-4fb9-84c0-030fc8edc915)

### Reverse Diffusion Process:


![Screenshot from 2024-06-09 15-03-24](https://github.com/TalalAhmed311/Diffusion/assets/64472176/900ceb2e-7d92-4f76-9240-1d37e4bd613e)

![Screenshot from 2024-06-09 15-03-51](https://github.com/TalalAhmed311/Diffusion/assets/64472176/249e50fa-f253-4e88-8d3b-79c0fa0de8e1)


#### Resources:

https://www.youtube.com/watch?v=H45lF4sUgiE

https://www.youtube.com/watch?v=HoKDTa5jHvg&pp=ygUWc3RhYmxlIGRpZmZ1c2lvbiBtYXRocw%3D%3D
