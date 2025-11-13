The project is under construction

Nothing to say more

## Spec :

- react native version to use : 3.5.3

## Commands React Native

```pwsh
cd my-app
npm run android
npm run ios
npm run web
```

## Run app on android

```
npm run adroid //but it will not work
```

It will not work because you don't have this driver (https://developer.samsung.com/android-usb-driver) it's (Samsung Android USB Driver for Windows v1.9.0.0 (35.5mb) | Apr10,2025)

Then you can connect your phone with a cable to the PC
Sadly for my Galaxy A55 5G I got "Something went wrong" while I wanted to try out the project on it, can't tell what did go wrong

Solution was found and the cause of the problem too

The problem : The phone wasn't on the same network as the computer, they need to be on the same network to access (ceff-5 wifi is not connected to the network as the pcs)
Solution : While phone is pluged, use the -- --tunnel flag while being as : `npm run android -- --tunnel`
