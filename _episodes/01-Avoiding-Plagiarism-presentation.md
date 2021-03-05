{% assign url_prefix = site.baseurl | append: "/assets/videos" %}

<video width="800" height="450" controls>
 <source src="{{url_prefix}}/drupal-tripal-explainer.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>


video {
  border: 1px solid aae4f7;
  -webkit-box-shadow: 5px 5px 15px 5px rgba(0,0,0,0.31);
  box-shadow: 5px 5px 15px 5px rgba(0,0,0,0.31);
}
