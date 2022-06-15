# **Image Processing API**
#### _by Amir Tadros_

---
This API resizes images when accessed through the "/convert" endpoint. If the required image size already exists, the server sends the cached image. Otherwise, it processes the image and retuns the required size to the user.

The designed endpoint runs on _localhost:8000_ and takes 3 parameters that must be entered
- name: a string
- width: a number (in pixels)
- height: a number (in pixels)

**example**
```
localhost:8000/convert?name=summer03&width=300&height=150
```

## <ins>Required scripts</ins>
to run prettier and lint
```
npm run format
```


To run the build followed by Jasmine
```
npm run test
```

To start the server
```
npm run start
```

## **Please note**
The ZIP file does not contain the node_modules folder, so please run the _npm install_ command.