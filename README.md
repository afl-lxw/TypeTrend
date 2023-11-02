# APP

## UUID

```shell
xcrun simctl list devices
```

```js
== Devices ==
-- iOS 14.4 --
-- iOS 16.4 --
    iPhone SE (3rd generation) (A4C23D8C-71DD-4DAE-ABB5-42FBF645EB78) (Shutdown) 
    iPhone 14 (A4B7F7AA-E933-4A85-849C-B8985E90BFFE) (Booted) 
    iPhone 14 Plus (217ED32D-C9EC-4A07-AF5B-4CA62FAFA06B) (Shutdown) 
    iPhone 14 Pro (052C9754-2D51-4C72-951A-3FFB92553401) (Shutdown) 
    iPhone 14 Pro Max (51366F08-371B-4538-A23B-0ADF02BDB152) (Shutdown) 
    iPad Air (5th generation) (74145023-880B-4FDE-A2CC-693A1701C637) (Shutdown) 
    iPad (10th generation) (8E2F0FFC-8F39-4534-BA09-774AB4AD8E0B) (Shutdown) 
    iPad mini (6th generation) (19FC9553-7F6C-4D63-82EE-9D0466615125) (Shutdown) 
    iPad Pro (11-inch) (4th generation) (67C491FE-5DE6-4F31-BDAD-152029130085) (Shutdown) 
    iPad Pro (12.9-inch) (6th generation) (10E8CC59-1896-413D-A38F-998367CC4BAE) (Shutdown) 
-- iOS 17.0 --
-- iOS 17.0 --
    iPhone SE (3rd generation) (37112076-3B11-4511-B940-4CF20AA9EAA0) (Shutdown) 
    iPhone 15 (2E11B4D1-21C3-44BA-BD15-99BF79786224) (Booted) 
    iPhone 15 Plus (2157AB7D-3D8D-4717-9466-B8B8E546B813) (Shutdown) 
    iPhone 15 Pro (4EDF4363-550D-4CE7-9A1B-0A5450DF2666) (Shutdown) 
    iPhone 15 Pro Max (8CF48AA8-3F42-40E5-AB5F-91CBCCC59C5E) (Shutdown) 
    iPad Air (5th generation) (03DB6942-0C6D-4054-8C0F-1681249E26BC) (Shutdown) 
    iPad (10th generation) (352BA367-2BB3-43C1-BA55-C7E9BE4D15F6) (Shutdown) 
    iPad mini (6th generation) (4060E1E4-2A36-48F3-A969-2A355F5FC14A) (Shutdown) 
    iPad Pro (11-inch) (4th generation) (E3FC85C9-FEA9-4F62-9F04-5B6DCEF63C2E) (Shutdown) 
    iPad Pro (12.9-inch) (6th generation) (4B5BC28C-0C32-4B43-9ED5-2659E14A3AE8) (Shutdown) 
```

运行 React Native 应用程序：

在您的 React Native 项目目录中，使用 react-native run-ios 命令，并在后面添加 --simulator 标志，后面跟随您选择的模拟器的名称或 UDID。例如：

```bash
react-native run-ios --simulator="iPhone 11"
```

或者，通过 UDID：

```bash
react-native run-ios --simulator="D2E23967-5498-47BB-AC9F-68F7E3B0639A"
```

这将启动指定的模拟器，并在其上运行 React Native 应用程序。
