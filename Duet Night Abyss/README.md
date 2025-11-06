Copy `Engine.ini` file to this location \
```Duet Night Abyss\DNA Game\EM\Saved\Config\WindowsNoEditor```\
```Duet Night Abyss\EMLauncher\Saved\Config\WindowsNoEditor```

 You may need to paste the config again becuase the game will sometimes reset the `Engine.ini` file every hotfix/update, or just set the file as Read Only

# GameUserSettings.ini
```
[ScalabilityGroups]
sg.ResolutionQuality=75.000000
sg.ViewDistanceQuality=0
sg.AntiAliasingQuality=0
sg.ShadowQuality=0
sg.PostProcessQuality=0
sg.TextureQuality=0
sg.EffectsQuality=0
sg.FoliageQuality=0
sg.ShadingQuality=0
```
Set `sg.ResolutionQuality` to the same as your `r.ScreenPercentage` and `r.SecondaryScreenPercentage.GameViewport` from `Engine.ini`

# Launch Options
<pre>
-dx11 Launch the game with DX11
-dx12 Launch the game with DX12
</pre>




