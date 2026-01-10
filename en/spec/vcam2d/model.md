# Model Specifications (VCam2D)

VCam2D controls Live2D Cubism models using the following Live2D parameters.

## Parameter List

### Body Movement

| Parameter ID    | Value Range | Description                  |
| --------------- | ----------- | ---------------------------- |
| ParamBodyAngleX | -10 ~ 10    | Body X-axis rotation (pitch) |
| ParamBodyAngleY | -10 ~ 10    | Body Y-axis rotation (yaw)   |
| ParamBodyAngleZ | -10 ~ 10    | Body Z-axis rotation (roll)  |

### Head Movement

| Parameter ID | Value Range | Description                  |
| ------------ | ----------- | ---------------------------- |
| ParamAngleX  | -30 ~ 30    | Head X-axis rotation (pitch) |
| ParamAngleY  | -30 ~ 30    | Head Y-axis rotation (yaw)   |
| ParamAngleZ  | -30 ~ 30    | Head Z-axis rotation (roll)  |

### Eye Movement

| Parameter ID   | Value Range | Description                               |
| -------------- | ----------- | ----------------------------------------- |
| ParamEyeLOpen  | 0.0 ~ 1.0   | Left eye openness (0.0=closed, 1.0=open)  |
| ParamEyeROpen  | 0.0 ~ 1.0   | Right eye openness (0.0=closed, 1.0=open) |
| ParamEyeBallX  | -1.0 ~ 1.0  | Gaze X direction (left-right)             |
| ParamEyeBallY  | -1.0 ~ 1.0  | Gaze Y direction (up-down)                |
| ParamEyeLSmile | 0.0 ~ 1.0   | Left eye smile expression                 |
| ParamEyeRSmile | 0.0 ~ 1.0   | Right eye smile expression                |

### Mouth Movement

| Parameter ID    | Fallback ID | Value Range | Description     |
| --------------- | ----------- | ----------- | --------------- |
| ParamMouthOpenY | ParamA      | 0.0 ~ 1.0   | Mouth openness  |
| ParamA          | -           | 0.0 ~ 1.0   | Vowel shape "A" |
| ParamI          | -           | 0.0 ~ 1.0   | Vowel shape "I" |
| ParamU          | -           | 0.0 ~ 1.0   | Vowel shape "U" |
| ParamE          | -           | 0.0 ~ 1.0   | Vowel shape "E" |
| ParamO          | -           | 0.0 ~ 1.0   | Vowel shape "O" |

### Other Expressions

| Parameter ID | Value Range | Description            |
| ------------ | ----------- | ---------------------- |
| ParamBreath  | 0.0 ~ 1.0   | Breathing motion       |
| ParamCheek   | 0.0 ~ 1.0   | Cheek blush expression |

## Additional Information

For more information about Live2D Cubism standard parameters, please refer to the official documentation:

- [Live2D Cubism Standard Parameter List](https://docs.live2d.com/cubism-editor-manual/standard-parameter-list/)

If you encounter models that cannot be loaded or do not work correctly, please contact us through the inquiry form.
