消費税計算システム

border ="---------------------"

number_tortal = 0
tax1_tortal = 0
tax2_tortal = 0

for num in 1..10 do
  puts border
  puts "金額を入力してください"
  number = gets.chomp.to_i  
  tax1 = number * 1.08
  tax2 = number * 1.1
  puts "入力欄#{number}円，消費税8%の場合#{tax1}円，消費税10%の場合#{tax2}円"
  number_tortal += number
  tax1_tortal += tax1
  tax2_tortal += tax2
end

puts "税抜きの合計#{number_tortal}円，消費税8%の場合の合計#{tax1_tortal}円，消費税10%の場合の合計#{tax2_tortal}円"
