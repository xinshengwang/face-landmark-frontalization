# face-landmark-frontalization

In this code, two ways to make the face 3d landmarks frontal. The facial landmarks are detected with face_alignment.

### register the landmark to a frontal standard face landmark.

```
register_to_std_face.ipynb
```
* The standard face landmark

![Standard face landmark](https://user-images.githubusercontent.com/35858599/111261464-d118b700-8622-11eb-9603-9c335e8bdfad.png)

* The original landmark (left) and the frontalized landmark (right)
 
![Origial](https://user-images.githubusercontent.com/35858599/111260935-f35e0500-8621-11eb-8380-3b74250676ec.png)![registered_face](https://user-images.githubusercontent.com/35858599/111261505-dd047900-8622-11eb-94cb-3eb2977b855d.png)


### based on pitch, yaw, roll

```
Based_on_Rotation_Angle.ipynb
```

* The frontalized landmark

![based_on_rot](https://user-images.githubusercontent.com/35858599/111261966-a1b67a00-8623-11eb-9710-1aa11d9cddb9.png)

