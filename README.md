# CodeWars

## func 123->[3,2,1]
### My func
```Swift
  func digitize(_ num:Int) -> [Int] {
    Array(String(num)).map{Int(String($0))!}.reversed()
}
```
### Best examples
```Swift
    String(num).characters.flatMap { Int(String($0)) }.reversed()
    String(num).map{ $0.wholeNumberValue! }.reversed()
    String(num).characters.reversed().map{Int(String($0))!}
```
