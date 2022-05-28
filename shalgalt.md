1.const, let,var тогтмол өөрчлөхгүй утга болон өөрчлөгдөг утгуудыг зарлаж өгөх
Immutable өөрлөгдөхгүй  Анхдагч утгуудыг өөрчлөх боломжгүй 
Mutable өөрчлөгддөг 
2.let x,y,z

x = 5;          // Statement 1
y = 6;          // Statement 2
z = x + y;      // Statement 3

3. Утга бүр нь төрлөөс гадна үнэн эсвэл худал гэж нэрлэгддэг утгаасаа Boolean утгатай байдаг. Булийн бус утгыг хэрхэн үнэн эсвэл худал утга болгон хөрвүүлэхийг тодорхойлдог
Falsy
Falsy нь
False ,0,‘’,””,``,Null,Undefined,Nan
If(3=2){false};
Document.querySelector(“.active”).innerHtml=null;
A=document.getElementById(d).textContent
Console.log(a);
// undefined	
Truthy
‘0’,‘false’,[],{},Function(){},If(value){ },Valu is truthy
Else{
const cars = [
  "Saab",
  "Volvo",
  "BMW"
]; 
const person = {
  firstName: "John",
  lastName: "Doe",
  age: 50,
  eyeColor: "blue"
};
match=()=>{}
Худаа үед яах ёстой нь харагдах}
4.
А.Math.floor -шал болгох өгөгдсөн тооны хамгийн бага бүхэл тоо
Б.Math.random*10 10  
В.0*9 хүртэлх тоо + 6хүртэлх бүхэл тоо 6-аас 15 хооронд гарна.
5.
myElement = document.getElementById("name");Id гаар барьж авах
myElements = document.getElementsByTagName("p") tagName аар барьж авах
myElements = document.getElementsByClassName("name") class name аар барьж авах
myElements = document.querySelector(".name");.name class барьж авах
myElements = document.querySelectorAll(".name");Бүх name class барьж авах
6. Төрлийн албадлага 
Ил болон далд
Boolen string true false number хүчээр өөр болгох
Number(“23”);
If(23<=44)true false
X=”1”;
Y=”2”
Eval(x+y);
