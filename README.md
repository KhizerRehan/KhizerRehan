# Khizer Rehan Portfolio

#### Name:Khizer Rehan.

#### Designation:Frontend Developer.

#### Email : khizerrehan92@gmail.com.

#### CV : [click here.](https://khizerrehan.github.io/khizerrehan/cv/khizerrehan_cv.pdf)

#### Portfolio link : [click here.](https://khizerrehan.github.io/khizerrehan/)


# RUN Docker image:

Build Docker Image

```
docker build -t <conatainer-name:version-no> [Dockerfile Path]

e.g docker build -t portfolio:v1 .
```

Run Docker Image

```
docker images # see new docker image is created.

docker run -p 81:80 --name portfolio-v1 -d  portfolio:v1
```

Open Browser:

```
localhost:81 # Go to browser and hit url
```