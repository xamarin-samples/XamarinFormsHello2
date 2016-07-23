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
    <StackLayout VerticalOptions="Center">
        <Label Text="Hello" HorizontalOptions="Center" BackgroundColor="#800" />
        <Label Text="Xamarin" HorizontalOptions="Start" BackgroundColor="#080" />
        <Label Text="World" HorizontalOptions="End" BackgroundColor="#008" />
        <Label BackgroundColor="#ff8" HorizontalOptions="Center" TextColor="#000">
            <Label.Text>
Here
is
multi
line.
            </Label.Text>
        </Label>
    </StackLayout>
</ContentPage>
```


## Screenshot
![screenshot](https://github.com/xamarin-samples/XamarinFormsHello2/raw/master/screenshots/screenshot.png)
