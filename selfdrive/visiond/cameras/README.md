In the whole visiond folder I added a bunch of TODOs. Just search for them-
## Important

If you have a OnePlus phone 4 or newer, feel free to check on the internet for the excact camera specs and them like so to the camera_qcom.c file:

```

 [CAMERA_ID_<Add sensor name>] = {
    .frame_width = <>,
    .frame_height = <>,
    .frame_stride = <>,
    .bayer = true,
    .bayer_flip = 0,
    .hdr = false
  },

```

If you are done add send me a pull request and I will merge them. 

Good luck :) 

