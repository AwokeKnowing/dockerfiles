This docker image is part of Open Visual Cloud software stacks. Optimized for Media Analytics. Included what are in media delivery GStreamer image, inferencing engine and video analytics plugins. Also included Intel hardware accelaration software stack such as media SDK, media driver, opencl, gmmlib and libva. The docker image can be used in the FROM field of a downstream Dockerfile. 

## Supported tags and respective Dockerfile links
 - [vcac-a-ubuntu-1804-analytics-gst](https://github.com/OpenVisualCloud/Dockerfiles/blob/master/VCAC-A/ubuntu-18.04/analytics/gst/Dockerfile)

## Quick reference
- #### Supported platform and OS
Intel&reg; VCAC-A platform, Ubuntu 18.04

- #### Included components:
[GStreamer](https://github.com/OpenVisualCloud/Dockerfiles/blob/master/doc/gst.md)	


- #### Where to get help:
- [Open Visual Cloud Dockerfiles Github](https://github.com/OpenVisualCloud/Dockerfiles)
- [Getting Started With Open Visual Cloud Docker Files](https://01.org/openvisualcloud/documents/get-started-docker)
- [the Docker Community Forums](https://forums.docker.com)
- [the Docker Community Slack](https://www.docker.com/docker-community)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/docker)

-  #### Where to file issues:
[OpenVisualCloud Dockerfiles Issues](https://github.com/OpenVisualCloud/Dockerfiles/issues)

- #### Maintained by:
[OpenVisualCloud Dockerfiles Community](https://github.com/OpenVisualCloud/Dockerfiles/graphs/contributors)


## License
This docker installs third party components licensed under various open source licenses.  The terms under which those components may be used and distributed can be found with the license document that is provided with those components.  Please familiarize yourself with those terms to ensure your distribution of those components complies with the terms of those licenses.


| Components | License |
| ----- | ----- |
|Ubuntu| [Various](https://hub.docker.com/_/ubuntu) |
|libogg|BSD 3-clause "New" or "Revised" License|
|libvorbis|BSD 3-clause "New" or "Revised" License|
|Opus Interactive Audio Codec|BSD 3-clause "New" or "Revised" License|
|libvpx|BSD 3-clause "New" or "Revised" License|
|Aomedia AV1 Codec Library|BSD 2-clause "Simplified" License|
|x264|GNU General Public License v2.0 or later|
|x265|GNU General Public License v2.0 or later|
|dav1d|BSD 2-clause "Simplified" License|
|Intel Graphics Memory Management Library| MIT License|
|Intel libva| MIT License
|Intel media-driver | MIT License|
|Intel media SDK|MIT License|
|intel-opencl | MIT License|
|gstreamer|GNU Lesser General Public License v2.1 or later|
|gst orc|GNU Lesser General Public License v2.1 or later|
|gst plugin base|GNU Lesser General Public License v2.1 or later|
|gst plugin good|GNU Lesser General Public License v2.1 or later|
|gst plugin bad|GNU Lesser General Public License v2.1 or later|
|gst plugin ugly|GNU Lesser General Public License v2.1 or later|
|gst plugin libav|GNU Library General Public License Version 2|
|gst plugin vaapi|GNU Lesser General Public License v2.1 or later|
|opencv|BSD 3-clause "New" or "Revised" License|
|OpenVINO|End User License Agreement for the Intel(R) Software Development Products|
|gst plugin gva|MIT License|


More license information can be found in [components source package](https://github.com/OpenVisualCloud/Dockerfiles-Resources).   
As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses and potential fees for all software contained within. We will have no indemnity or warranty coverage from suppliers.
