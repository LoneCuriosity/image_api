# Image API
Date: 5/4/2023
## Screenshots

![App Screenshot](http://ramongarciajr.tech/Image%20API.png)


## Lessons Learned

During the process of developing this streamlined API, I gained valuable insights into the diverse range of response codes, their meanings, and appropriate usage scenarios. Additionally, I acquired knowledge regarding the functionality of the API handler within the next.js framework. Furthermore, I familiarized myself with JIMP, a robust Node.js library capable of extracting various information from provided images.


## Optimizations


There are certain aspects I aim to optimize within the system, particularly concerning the improved handling of provided image URLs. It has been observed that, in certain cases, the provided URL does not conform to the expected image format, such as lacking the necessary file extensions like .png, .jpeg, .jpg, and so on. As a consequence, the program encounters difficulties in processing the image, leading to a lack of returned results. To address this issue, a potential solution involves implementing a proxy mechanism to download and locally store the image before initiating the processing stage. This approach would effectively mitigate the problem of encountering non-conforming image formats, ensuring that only valid images are processed.


## Run Locally

Clone the project

```bash
  git clone https://github.com/LoneCuriosity/TAS_v2
```

Copy the img.js into the API directory within the Next.js Project.

```bash
  pages > api > subfolder > img.js
```

Go to

```bash
  http://website.com/api/subfolder/img.js?url=image.png&width=512&height=512
```


## 🛠 Skills
Next.js, Node.js


## Tech Stack

- JIMP
- Next.js
- Node.js
- JSON

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ramongarciajr.tech/)

## 🔗 Demo
[(https://ramongarciajr.tech/api/e2/img?ImgURL=https://upload.wikimedia.org/wikipedia/commons/thumb/b/b6/Image_created_with_a_mobile_phone.png/800px-Image_created_with_a_mobile_phone.png&width=512&height=512](https://ramongarciajr.tech/api/e2/img?ImgURL=https://upload.wikimedia.org/wikipedia/commons/thumb/b/b6/Image_created_with_a_mobile_phone.png/800px-Image_created_with_a_mobile_phone.png&width=512&height=512)

## Authors

- [@LoneCursioty](https://www.github.com/LoneCursioty)

