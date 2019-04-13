# count

**重要な点について**

viewcontroller.swift

```
import UIKit

class ViewController: UIViewController {
//ここに命令を書いていく！
}
```
***

```
@IBOutlet var label: UILabel!
```
=>ストーリーボード上で「label」という名前のUILabel部品を使用すること


***

```
var number : Int = 0
```
=>Int (整数)という型の変数の名前「number」を使用する。初期値は0に設定

***エラーが出やすい点***

教科書ではここで「関連付け」を初めて行う。
メンバーの中には、コードさえかければ作動すると考えている人もいるかもしれない。
これから先は関連付けが頻繁に出てくるため、ここで仕組みを理解してもらえるように重点的に教えていきたい。
