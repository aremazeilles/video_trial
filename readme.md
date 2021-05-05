# Reading video trial with Markdown

Here it is

![The video](video.mp4)

_I don´t know how to do it under markdown_

Using he animated gif:

![The animation](video.gif)

Following [gitlab doc](https://about.gitlab.com/handbook/markdown-guide/#videos):

<figure class="video_container">
  <video controls="true" allowfullscreen="true">
    <source src="video.mp4" type="video/mp4">
  </video>
</figure>


Trying to handle image dimension:

<video width="640" height="480" controls>
  <source src="video.mp4" type="video/mp4">
</video>