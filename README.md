# XamarinFormsHello
Xamarin.Forms Hello sample

## Pickuped code
XamarinFormsHello/XamarinFormsHello/App.cs
```
public class App : Application
{
    public App()
    {
        // The root page of your application
        MainPage = new ContentPage
        {
            Content = new StackLayout
            {
                VerticalOptions = LayoutOptions.Center,
                Children = {
                    new Label {
                        HorizontalTextAlignment = TextAlignment.Center,
                        Text = "Hello Hello\nHello"
                    },
                    new Label {
                        HorizontalTextAlignment = TextAlignment.Start,
                        Text = "Xamarin\nWorld"
                    },
                    new Label {
                        HorizontalTextAlignment = TextAlignment.End,
                        Text = "with\nVisual Studio"
                    },
                }
            }
        };
    }
    ....
```

## Screenshot
![screenshot](https://github.com/xamarin-samples/XamarinFormsHello/raw/master/screenshots/screenshot.png)
