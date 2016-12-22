#React-native-easy-loading
适用iOS、Android

## 有问题反馈
在使用中有任何问题，欢迎反馈给我，也可以用以下联系方式跟我交流

* 邮件(Netxy#vip.qq.com, 把#换成@)
* QQ: 850265689

## 使用

```javascript

import { Loading, EasyLoading } from 'react-native-easy-loading';

class App extends Component {
    componentDidMount() {
        EasyLoading.show('加载中...', 5000);
    }
    render() {
        return (
            <Loading color={'#F00'} textStyle={{color:'#F00'}}/>
        );
    }
}
```