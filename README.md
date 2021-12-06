<div id="top"></div>

[![Paper link][modified-shield]][paper-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]




<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/sekilab/VehicleOrientationDataset">
    <img src="media/logo.png" alt="Logo" width="auto" height="175">
  </a>

  <h3 align="center">The Vehicle Orientation Dataset</h3>

  <p align="center">
    The vehicle orientation dataset contains more than one million annotations of vehicles with orientation in more than 200,000 images. It reduces the need of a secondary neural network to classify orientation by simultaneously providing both vehicle class and direction.
    <br />
    <a href="#"><strong>Read paper»</strong></a>
    <br />
    <br />
    ·
    <a href="https://github.com/sekilab/VehicleOrientationDataset/issues">Report Bug</a>
    ·
    <a href="https://github.com/sekilab/VehicleOrientationDataset/issues">Request Feature</a>
  </p>
</div>

## Annotations style

<img src="media/sample_annotations.png" width="auto" height="auto">

All vehicles in the vehicle orientation dataset are labeled with both vehicle class (five categories) and its orientation (three types).

The five classes of vehicles are:
- Car
- Bus
- Truck
- Motorcycle
- Bicycle

The three types of orientations are:

- Front
- Back
- Side

So the vehicle orientation dataset has a total of 15 classes of vehicles with orientation such car_back, car_front, car_side, bus_back, bus_front, etc.

Annotations per class in the vehicle orientation dataset follows the long-tail distribution as commonly seen in other vehicle detection data sets.

<!-- Download dataset -->
## Download Dataset


The vehicle orientation dataset is hosted on AWS S3 (Asia-pacific, Tokyo) bucket. Since the overall size of the dataset is quite big (~100GB), we have split the vehicle orientation dataset into five parts for convenience of users. Part 1 to Part 4 together contain 200,000 images (50,000 x 4) and Part 5 has 13,714 images. <br>

### Download links

- [Part-1, 50,000 images](https://sekilab-students.s3.ap-northeast-1.amazonaws.com/2021/vehicle-orientation-dataset/vehicle-orientation-1.zip)
- [Part-2, 50,000 images](https://sekilab-students.s3.ap-northeast-1.amazonaws.com/2021/vehicle-orientation-dataset/vehicle-orientation-2.zip)
- [Part-3, 50,000 images](https://sekilab-students.s3.ap-northeast-1.amazonaws.com/2021/vehicle-orientation-dataset/vehicle-orientation-3.zip)
- [Part-4, 50,000 images](https://sekilab-students.s3.ap-northeast-1.amazonaws.com/2021/vehicle-orientation-dataset/vehicle-orientation-4.zip)
- [Part-5, 13,714 images](https://sekilab-students.s3.ap-northeast-1.amazonaws.com/2021/vehicle-orientation-dataset/vehicle-orientation-5.zip)




<p align="right">(<a href="#top">back to top</a>)</p>




<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

For any question and support, please create an issue on GitHub or write to the author here:

Ashutosh Kumar  - ashutosh[at]iis.u-tokyo.ac.jp

<p align="right">(<a href="#top">back to top</a>)</p>

## Citation
We will update this section as soon as our paper is published online.


<!-- ACKNOWLEDGMENTS -->
<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/sekilab/VehicleOrientationDataset
[contributors-url]: https://github.com/sekilab/VehicleOrientationDataset/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/sekilab/VehicleOrientationDataset
[forks-url]: https://github.com/sekilab/VehicleOrientationDataset/network/members
[stars-shield]: https://img.shields.io/github/stars/sekilab/VehicleOrientationDataset
[stars-url]: https://github.com/sekilab/VehicleOrientationDataset/stargazers
[issues-shield]: https://img.shields.io/github/issues/sekilab/VehicleOrientationDataset
[issues-url]: https://github.com/sekilab/VehicleOrientationDataset/issues
[license-shield]: https://img.shields.io/github/license/sekilab/VehicleOrientationDataset
[license-url]: https://github.com/sekilab/VehicleOrientationDataset/blob/main/LICENSE.txt
[modified-shield]: https://img.shields.io/github/last-commit/sekilab/VehicleOrientationDataset/main
[paper-url]: https://github.com/sekilab/VehicleOrientationDataset/commits/main
[product-screenshot]: media/sample_annotations.png