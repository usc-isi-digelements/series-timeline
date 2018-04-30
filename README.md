# series-timeline

A Polymer Element that runs a time-series query and shows the response data in a timeline.

### Example
```html
<series-timeline
  data-type="measurement"
  id-field="measure"
  series-id="ABC123"
  transform-config="{}"
  transform-function="[[transformQueryResponseIntoTimelineData]]"
  type-field="type">
</series-timeline>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

