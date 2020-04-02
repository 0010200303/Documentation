# ScreenBase
namespace: TaleWorlds.Engine.Screens

You can create a custom screen by inheriting from ScreenBase and add your widgets.

Here is a skeleton of what your inherited class should look like:

```csharp
public class MyScreen : ScreenBase
{

}
```

And you can push it with:
```csharp
public class MyScreen : ScreenBase
{
  ScreenBase myScreen = new MyScreen();
  ScreenManager.PushScreen(MyScreen);
}
```
