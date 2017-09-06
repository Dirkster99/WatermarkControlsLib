# WatermarkControlsLib
Provides MVVM/WPF conform textbox and combobox control implementations for dark and light modern UIs

The controls afre based on a refactored version from the WPF Tool Kit at: http://wpftoolkit.codeplex.com/

# TextBox with Watermark
![](https://github.com/Dirkster99/Docu/blob/master/WatermarkControlsLib/screenshot.png)

# ComboBox with Watermark
![](https://github.com/Dirkster99/Docu/blob/master/WatermarkControlsLib/screenshot1.png)
![](https://github.com/Dirkster99/Docu/blob/master/WatermarkControlsLib/screenshot2.png)
![](https://github.com/Dirkster99/Docu/blob/master/WatermarkControlsLib/screenshot3.png)


## Theming

Load *Light* or *Dark* brush resources in you resource dictionary to take advantage of existing definitions.

```XAML
    <ResourceDictionary.MergedDictionaries>
        <ResourceDictionary Source="/WatermarkControlsLib;component/Themes/DarkBrushs.xaml" />
    </ResourceDictionary.MergedDictionaries>
```

```XAML
    <ResourceDictionary.MergedDictionaries>
        <ResourceDictionary Source="/WatermarkControlsLib;component/Themes/LightBrushs.xaml" />
    </ResourceDictionary.MergedDictionaries>
```

These definitions do not theme all controls used within this library. You should use a standard theming library, such as:
- [MahApps.Metro](https://github.com/MahApps/MahApps.Metro),
- [MLib](https://github.com/Dirkster99/MLib), or
- [MUI](https://github.com/firstfloorsoftware/mui)
