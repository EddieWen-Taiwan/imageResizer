# imageResizer

An easy and handy tool to help you resize images.

### Setup

install node_modules

```bash
# $ npm install
$ yarn
```

### Usage

Just one command, you can resize one image or many image files under a folder.

```bash
$ node src/index.js <path/to/file> <width> <height>
```

_Eigher of "width" and "height" is optional, the image would be resize but in the same ratio._

### Example

```bash
$ node src/index.js examples/ 350 280

# height is optional
$ node src/index.js examples/octocat.png 120

# auto width and keep ratio
$ node src/index.js examples/octocat.jpg auto 260
```
