# XamarinFormsHello2
Xamarin.Forms Hello sample with XAML

## Pickuped code
### XamarinFormsHello/XamarinFormsHello/App.cs
```
public class App : Application
{
    public App()
    {
        // The root page of your application
        MainPage = new Page1();
    }
    ....
```

### XamarinFormsHello/XamarinFormsHello/Page1.xaml
```
<?xml version="1.0" encoding="utf-8" ?>
<ContentPage xmlns="http://xamarin.com/schemas/2014/forms"
             xmlns:x="http://schemas.microsoft.com/winfx/2009/xaml"
             x:Class="XamarinFormsHello.Page1">
    <Label Text="{Binding MainText}" VerticalOptions="Center" HorizontalOptions="Center" />
</ContentPage>
```


## Screenshot
![screenshot](https://github.com/xamarin-samples/XamarinFormsHello/raw/master/screenshots/screenshot.png)
