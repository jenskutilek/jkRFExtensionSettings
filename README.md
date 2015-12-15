# jkRFExtensionSettings

Helper module to manage RoboFont extension settings.



### Example

This code:

```
def test():
    my_settings = SettingsWindow("de.kutilek.test", "My Settings")
    my_settings.add("mySlider", 0.0, "My Slider")
    my_settings.add("myCheckbox", True)
    my_settings.show()
```

will open this settings dialog:

<img src="https://raw.githubusercontent.com/jenskutilek/jkRFExtensionSettings/master/images/sample.png" width="412" height="206" alt="">

The values of the slider and checkbox will be stored under `de.kutilek.test.mySlider` and `de.kutilek.test.myCheckbox` respectively.