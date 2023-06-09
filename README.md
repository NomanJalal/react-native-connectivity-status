
# react-native-internet-status-view
A callout that's similiar to what facebook messengers shows during internet connectivity status change.


![Animated gif showing the animation when the internet is disconnected and reconnected ](https://raw.githubusercontent.com/ismdcf/react-native-internet-status-view/master/misc/internet_status_view.gif)

Supports react native 0.22^  iOS and Android (Tested on 0.37).

## Installation

```bash
$ npm i react-native-internet-status-view --save
```

## Usage

Place the component on where it wants to be appeared (mostly just below the root view )

```jsx
<View style={styles.container}>
  <InternetStatusView
    textToDisplay="Sorry You're Not Connected to the Internet"
  />
  ....... Rest Of Your View
</View>
```

## Accepted Props

| Prop | Description | Default Value |
|---|:---|:---:|
|**`textToDisplay`**| `String` The message you want the user to see. | No Internet Connection |
|**`style`**| `object` The style of the outer text container | {{justifyContent: 'center',alignSelf: 'stretch',backgroundColor:"#e74c3c",height:25}}  |

## Contributions Are Welcomed To Make This Component a Cool One 

## License

[`ISC`](http://opensource.org/licenses/ISC) License
