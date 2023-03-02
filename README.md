# Challenge-F
num = 21
use_synth :piano
87.times do
  play num
  sleep 0.5
  num = num + 1
end

num = 108
use_synth :organ_tonewheel
87.times do
  play num
  sleep 0.25
  num = num - 1
end

num = 21
use_synth :piano
87.times do
  play num
  sleep 0.125
  num = num + 1
end
