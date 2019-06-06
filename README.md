# FormSerialisor
Saving the state (serializing) a Windows Form.&nbsp;
**Original author** : https://www.codeproject.com/Articles/86503/Saving-the-state-serializing-a-Windows-Form

&nbsp;
### How to use :
*To use this code in your own project, all you need to do is drop the FormSerialisor.cs file into your project, and then add the following line at the top of any class where you wish to use the code:*
```
using FormSerialisation;
```

*To serialize :*
```
FormSerialisor.Serialise(this, Application.StartupPath + @"\serialise.xml");
```

*To deserialise :*
```
FormSerialisor.Deserialise(this, Application.StartupPath + @"\serialise.xml");
```

More info on [original page](https://www.codeproject.com/Articles/86503/Saving-the-state-serializing-a-Windows-Form).

&nbsp;
### Adding :
*DateTimePicker* serialisor and deserialisor.