## AUDIOMODE\_CHANGED

Navigator EQ notification that the output's audio mode has changed to either Tone Control or Equalizer for the output. This is an optional notification and should be used only if your device has audio modes. 


### Name

`AUDIOMODE_CHANGED`


| Parameter       | Type | Description                                                                                                                                          |
| --------------- | ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| OutputBindingID | INT  | Output Binding ID                                                                                                                                    |
|                 | INT  | 1 = TONE\_CONTROL: This is sent when a Tone Control value is changed. 2 = EQUALIZER: This is sent when a EQ value is changed such as Treble or Bass. |


### Returns

`None`

