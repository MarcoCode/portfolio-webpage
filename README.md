## Portfolio Project - Responsive website

### In order to see the Polymer Ripple effect on images please start a simple Webserver and visit localhost:8000 in your browser

 - I.e. using Ruby:

```ruby
  ruby -run -ehttpd . -p8000
```
- For a list of oneliner Webservers please visit this gist by Willurd:

[Webserver - oneliners](https://gist.github.com/willurd/5720255)

#### Build instructions

- "grunt" alone creates a new, completed images directory
- "grunt clean" removes the images directory
- "grunt responsive_images" re-processes images without removing    the old ones
