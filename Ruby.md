標準入力を受け取る  
message = gets.chomp  
puts message  

入力が２つある時は、もう一度記述することで２個目を表示することができる
message = gets.chomp  
puts message  
message = gets.chomp  
puts message  

# 整数データを受け取って表示しよう

number = gets.to_i
puts number
