#Suma de dos matrices

#! /usr/bin/ruby	

x = [[2,4,2],[1,6,0],[4,2,3]]  #matriz x
y = [[0,2,3],[5,3,0],[2,2,2]]  #matriz y
z = Array.new		        #matriz z

m,n = x.size, x[1].size

for i in 0...m do
  z[i]=Array.new
    for j in 0...n do
      z[i][j] = 0
    end
end

for i in 0...m do
  for j in 0...n do
    z[i][j]= x[i][j] + y[i][j]
  end
end

puts "\n La Matriz x es ="
x.each do |fila|
  puts fila.join(" ")
end

puts "\n La Matriz y es ="
y.each do |fila|
  puts fila.join(" ")
end

puts "\n La Suma de la Matriz x y y es ="
z.each do |fila|
  puts fila.join(" ")
end