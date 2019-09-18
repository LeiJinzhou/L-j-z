import Cocoa
 class Person {
 let name: String = "雷金洲"
 let gender: String = "男"
 let height: Int = 169
}
let output = Person() 
print(output.name)
print(output.gender)
print(output.height)
func eat() -> String {
  return "eat"
}
func talk() -> String {
  return "talk"
func walk() -> String {
  return "walk"
}
print("one of my abilities is",eat())
print("one of my abilities is",talk())
print("one of my abilities is",walk())
