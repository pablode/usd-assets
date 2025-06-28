## Interior Map Shader

https://github.com/user-attachments/assets/d11ecde6-74ef-4de5-9f6d-a1d54f84193b

interior\_map.mtlx can be XML-included and provides the `<interiormap>` node with following inputs:
  * _cubemap_ (filename): Equiangular map projected inside cube.
  * _texcoord_ (vector2): Texture coordinates of the surface geometry.
  * _rotation_ (float): Rotation of the cube map texture.
  * _depth_ (float): Distance to cube far plane.

Creator: Pablo Delgado

License: CC0 (Public domain)

Remarks:
- MaterialX 1.38.9+ required
- logic inspired by [Three Interior Mapping](https://github.com/mohsenheydari/three-interior-mapping)
- env map sampling from [MaterialX example](https://github.com/AcademySoftwareFoundation/MaterialX/blob/9d94a81b2ffce87f4e4bfb1630f96a15878db1ff/resources/Lights/environment_map.mtlx)
