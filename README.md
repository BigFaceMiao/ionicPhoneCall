Ionic App Base
=====================

config.xml

```bash
<access origin="tel:*" launch-external="yes" />
<access origin="mailto:*" launch-external="yes" />
<access origin="geo:*" launch-external="yes" />
<access origin="maps:*" launch-external="yes" />
```

html

```bash
<a href="tel:10086">10086</a>
```
或者
```bash
<a ng-href="tel:10086">10086</a>
```

然后运行

```bash
cordova plugin add cordova-plugin-whitelist
```

之后ionic正常编译就行


