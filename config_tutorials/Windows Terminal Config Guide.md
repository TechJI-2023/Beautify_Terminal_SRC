# Windows Terminal Config Guide

After everything with oh-my-posh is setup, your terminal may look something like this:

![neko_theme](../pic/neko_theme.jpg)

(This theme `neko` is provided by oh-my-posh, but I myself don't recommend using it in daily work. It's just too cute to be serious.)

Then you may want to go further and customize your own terminal. Here are some instructions.

You can go to this [link](https://zhuanlan.zhihu.com/p/435998754) for detailed instructions in Chinese.

## Background Image

Add to your `settings.json`:

```json
"profiles":
{
    "defaults":
    {
        "backgroundImage": "your_path/background.jpg",
        "backgroundImageOpacity": 0.5,
        "backgroundImageStretchMode": "uniformToFill"
    }
}
```

## Color Scheme

Change it in settings or `settings.json`:

```json
"profiles":
{
    "defaults":
    {
        "colorScheme": "One Half Dark"
    }
}
```

## Transparency

Strongly recommended by @zzjc1234, you can add this to your `settings.json`:

```json
"profiles":
{
    "defaults":
    {
        "opacity": 80
    }
}
```

If you want your background be blurred, you can add:

```json
"profiles":
{
    "defaults":
    {
        "useAcrylic": true,
    }
}
```

## More Colors

Add to your `settings.json`:

```json
"profiles":
{
    "defaults":
    {
        "tabColor":"#E6FF00",
        "foreground":"#E6FF00",
        "background":"#000000",
    }
}
```

## Font

Add to your `settings.json`:

```json
"profiles":
{
    "defaults":
    {
        "font":
        {
            "face": "FiraCode Nerd Font Mono",
            "size": 12
        }
    }
}
```
