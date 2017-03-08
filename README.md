#Parallax Hover React Component
This is a fork of https://github.com/tylerk/react-parallax-hover
It has two differences with it:
* It has no shadow when not being hovered
* It has a gray border with rounded corners when not being hovered

### Install
`npm install --save react-parallax-hover-with-borders`

### Run the example locally
```
git clone https://github.com/kebirek/react-parallax-hover
cd react-parallax-hover
npm install
npm start
```

### Usage
```
import ParallaxHover from 'react-parallax-hover';

<ParallaxHover width='500' height='500'>
    <img ref='image' src='...' />
    <div ref='text'>Some text</div>
</ParallaxHover>
```
