# About

This is a sample project from Brad Traversy's Youtube channel. You can find it by [here](https://youtu.be/ontX4zfVqK8)

### Why won't this code work as is?

This code won't work as is because it requires a Maps API key to utilize Google Maps. You'll find a key in the early commits but it has since been deleted, both from the code and from Google's cloud platform.

### I just want to see the code working!

All that is needed is a Maps API key. You can easily generate one for free from you Google Cloud Platform account. Everyone has one of these if you use Google services. You can access your's from this [link](console.cloud.google.com).

Once you have enable the Maps Javascript API and generated your key, paste the key into the bootstrapURLKeys={{ key: '' }} property of the GoogleMapReact item with the Map.js component.
