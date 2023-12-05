# QRCode *for MAUI apps*

[![NuGet](https://img.shields.io/nuget/v/Maui.QrCode.svg?label=NuGet)](https://www.nuget.org/packages/Maui.QrCode/)]

A QRCode MAUI view based on SkiaSharp and Xam.Forms.QRCode [!(https://github.com/dotnet-ad/Xam.Forms.QRCode)].


## Install

[NuGet](https://www.nuget.org/packages/Maui.QrCode/).

## Quickstart

```csharp
<?xml version="1.0" encoding="utf-8"?>
<ContentPage 
    ...
    xmlns:qr="clr-namespace:Maui.QrCode;assembly=Maui.QrCode">

    <qr:QrCode 
            Content="https://github.com/mono/SkiaSharp"
            Color="Maroon" 
            Level="H" 
            WidthRequest="400" 
            HeightRequest="400" 
            VerticalOptions="Center" 
            HorizontalOptions="Center" />
    
</ContentPage>
```

## Thanks
* [http://aloisdeniel.github.io]: all logic algorithms are from here. This is just a fork to MAUI
* [codebude/QRCoder](https://github.com/codebude/QRCoder) : all QRCode generation algorithms

## Contributions

Contributions are welcome! If you find a bug please report it and if you want a feature please report it.

If you want to contribute code please file an issue and create a branch off of the current dev branch and file a pull request.

## License

MIT © [Ondřej Novotný]()


