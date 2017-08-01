# My- First-repository-

//: Playground - noun: a place where people can play

import UIKit

var str = "Hello, playground"


class Person {
var age = 15
var name = "TINKU"

func updatedAgeName( updatedAge:Int, updatedName:String ) {
age = updatedAge
name = updatedName
}
func increaseAge( increaseBy: Int) -> Int{
age += increaseBy

return age
}
class func getAverageAge() -> Int {
return 50
}


}

var a = Person()
a.updatedAgeName(updatedAge: 25, updatedName: "TINKU")


a.name
a.age
a.increaseAge(increaseBy: 10)


Person.getAverageAge() // This is a property directly related to class  and known as class function

//generating a Random number

arc4random_uniform(500) //here 500 is intiger it is variable it can be any number this is not a function related to instance of class or instance of object its a part of UIKIT library



//lets make a program related to random number and conect it to string


var random = arc4random_uniform(190)
print("tinku\(random)")


// dealing with arrays
// a class that helps manage a collection of values and most commanly used in computer language

var p:[String] = ["hippio","is a Tough","animal"]

print(p[0],p[1],p[2])
// p[0] is hippo similarly p[1] and p[2] are is a tough and animal arrays begin with 0
// inserting strings in between the array is below

p.insert("and Big", at: 2)

p.count//this gives the number of strings

p.append("Mouse")// adds as a last string
p += ["snake"]// both are similar



//using if statement "if elseif and endif"
/*

var k = 10
var l = 5

(if k > l {

}
else if{

}
else{

})

*/


let pi = 3.141
print("pi is equal to \(pi)") // usage of print

//: Playground - noun: a place where people can play

import UIKit

var str = "Hello, playground"

class Person{

var Name: String = "Initial Name"
init(){

}
func Walk(){
print("I'm Walking")
}
}

var a = Person()
a.Name = "Alice"
a.Walk()


class Superhuman : Person {  //subclass

var nameName: String = "sun"

override init(){
super.init()
super.Name = "Super Duper"
}

func fly(){
print("He Can Fly")
}
override func Walk() {
print("I am walking really fast")

super.Walk()
}
}

var b = Superhuman()

b.Walk()
a.Walk()

b.Name  // this has four values but a has only one.

//generating a Random number

arc4random_uniform(500) //here 500 is intiger it is variable it can be any number
















