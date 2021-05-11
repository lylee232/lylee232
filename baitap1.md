//Write a script to ask user about their name, and then say hi to them
let Input = prompt('Xin chào, tên của bạn là ');
alert('Chào'+ ' ' + Input + ' Hãy thực hiện dãn cách xã hội nghiêm túc ');

//Write a script that ask 2 things from users, their first name and last name, then greet them with their full name
let input1 = prompt('Nhập họ của bạn ');
let input2 = prompt('Nhập tên của bạn ');
alert('Chào'+' '+input1+' '+input2);

//Write a script that calculates the area of a square
let input3 = Number(prompt('Cạnh hình vuông là '));
alert('Diện tích hình vuông là  '+input3**2);

//Write a script that calculates the area of a circle

let input4 = Number(prompt('Bán kính hình tròn là '));
alert('Diện tích hình tròn là '+ ' ' +input4**2*3.14);

//Write a script that converts Celsius (0C) into Fahrenheit (0F)
let input5 = Number(prompt('0C là'));
alert('Đổi sang 0F là'+ ' ' + (input5*1.8+32));
