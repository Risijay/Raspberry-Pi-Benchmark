# rpibenchmark
This program is a fork of Aikoncwd's rpi-benchmark
<br>
Original Author: AikonCWD
<br>
Original Code: https://github.com/aikoncwd/rpi-benchmark
<br>
This code has been slightly modified to stress the pi even more.
# What will the benchmark show?
This benchmark will show when your PI will thermal throttle and what taskes cause it to thermal throttle.
<br>
It will also see how your pi performs and how long it takes to attempt and complete specific tasks

# How to run the Benchmark
Its super easy!
<br>
copy and paste this code into your terminal:
<br>
curl -L https://raw.githubusercontent.com/risijay/rpi-benchmark/master/rpibenchmark.sh | sudo bash
<br>
# Information
This program will run 4 tests:
1. CPU test
2. Threads test
3. Memory test
4. HDParm test
# What will happen?
At the end of the test (depending on your cooling solution) your pi will Thermal Throttle.
<br>
(our tests show that the bear pi will throttle after the threads test)
<br>
This test will show how your pi performs and what tasks it can handle
# Recomendations
We highly recommend any type of cooling for your pi. It can be as simple as a fan or a small heatsink but always for the best results you should cool your pi.
<br>
Since the pi will hit 80° Celsius which is where it starts to throttle.
