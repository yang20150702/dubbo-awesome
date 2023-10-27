# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.927 ops/ms
# Warmup Iteration   2: 2.074 ops/ms
# Warmup Iteration   3: 4.388 ops/ms
Iteration   1: 5.125 ops/ms
Iteration   2: 5.655 ops/ms
Iteration   3: 5.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.484 ±(99.9%) 5.681 ops/ms [Average]
  (min, avg, max) = (5.125, 5.484, 5.673), stdev = 0.311
  CI (99.9%): [≈ 0, 11.165] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.475 ops/ms
# Warmup Iteration   2: 4.429 ops/ms
# Warmup Iteration   3: 5.362 ops/ms
Iteration   1: 5.625 ops/ms
Iteration   2: 5.825 ops/ms
Iteration   3: 5.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.748 ±(99.9%) 1.962 ops/ms [Average]
  (min, avg, max) = (5.625, 5.748, 5.825), stdev = 0.108
  CI (99.9%): [3.786, 7.710] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.337 ops/ms
# Warmup Iteration   2: 4.040 ops/ms
# Warmup Iteration   3: 5.375 ops/ms
Iteration   1: 5.453 ops/ms
Iteration   2: 5.594 ops/ms
Iteration   3: 5.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.492 ±(99.9%) 1.622 ops/ms [Average]
  (min, avg, max) = (5.429, 5.492, 5.594), stdev = 0.089
  CI (99.9%): [3.870, 7.114] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.446 ops/ms
# Warmup Iteration   2: 3.490 ops/ms
# Warmup Iteration   3: 4.622 ops/ms
Iteration   1: 4.615 ops/ms
Iteration   2: 4.588 ops/ms
Iteration   3: 4.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.589 ±(99.9%) 0.461 ops/ms [Average]
  (min, avg, max) = (4.564, 4.589, 4.615), stdev = 0.025
  CI (99.9%): [4.128, 5.050] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:55
# Fork: 1 of 1
# Warmup Iteration   1: 21.233 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 7.285 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.157 ±(99.9%) 0.009 ms/op
Iteration   1: 6.133 ±(99.9%) 0.012 ms/op
Iteration   2: 5.681 ±(99.9%) 0.017 ms/op
Iteration   3: 5.807 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.874 ±(99.9%) 4.252 ms/op [Average]
  (min, avg, max) = (5.681, 5.874, 6.133), stdev = 0.233
  CI (99.9%): [1.622, 10.126] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:48
# Fork: 1 of 1
# Warmup Iteration   1: 16.511 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 6.375 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.636 ±(99.9%) 0.008 ms/op
Iteration   1: 5.589 ±(99.9%) 0.009 ms/op
Iteration   2: 5.825 ±(99.9%) 0.009 ms/op
Iteration   3: 5.581 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.665 ±(99.9%) 2.527 ms/op [Average]
  (min, avg, max) = (5.581, 5.665, 5.825), stdev = 0.139
  CI (99.9%): [3.138, 8.192] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:41
# Fork: 1 of 1
# Warmup Iteration   1: 19.233 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 7.312 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.962 ±(99.9%) 0.007 ms/op
Iteration   1: 5.957 ±(99.9%) 0.014 ms/op
Iteration   2: 6.258 ±(99.9%) 0.008 ms/op
Iteration   3: 5.802 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.006 ±(99.9%) 4.231 ms/op [Average]
  (min, avg, max) = (5.802, 6.006, 6.258), stdev = 0.232
  CI (99.9%): [1.775, 10.236] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:34
# Fork: 1 of 1
# Warmup Iteration   1: 23.519 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 9.063 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.909 ±(99.9%) 0.015 ms/op
Iteration   1: 6.828 ±(99.9%) 0.011 ms/op
Iteration   2: 6.889 ±(99.9%) 0.012 ms/op
Iteration   3: 6.948 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.888 ±(99.9%) 1.096 ms/op [Average]
  (min, avg, max) = (6.828, 6.888, 6.948), stdev = 0.060
  CI (99.9%): [5.792, 7.985] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:28
# Fork: 1 of 1
# Warmup Iteration   1: 18.020 ±(99.9%) 0.387 ms/op
# Warmup Iteration   2: 6.987 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.061 ±(99.9%) 0.028 ms/op
Iteration   1: 5.670 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.228 ms/op
                 createUser·p0.50:   5.358 ms/op
                 createUser·p0.90:   7.021 ms/op
                 createUser·p0.95:   8.045 ms/op
                 createUser·p0.99:   10.879 ms/op
                 createUser·p0.999:  26.300 ms/op
                 createUser·p0.9999: 31.043 ms/op
                 createUser·p1.00:   31.785 ms/op

Iteration   2: 5.952 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.535 ms/op
                 createUser·p0.50:   5.636 ms/op
                 createUser·p0.90:   7.496 ms/op
                 createUser·p0.95:   8.471 ms/op
                 createUser·p0.99:   11.960 ms/op
                 createUser·p0.999:  28.025 ms/op
                 createUser·p0.9999: 32.993 ms/op
                 createUser·p1.00:   34.210 ms/op

Iteration   3: 5.703 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.290 ms/op
                 createUser·p0.50:   5.399 ms/op
                 createUser·p0.90:   7.086 ms/op
                 createUser·p0.95:   8.020 ms/op
                 createUser·p0.99:   11.108 ms/op
                 createUser·p0.999:  22.226 ms/op
                 createUser·p0.9999: 36.202 ms/op
                 createUser·p1.00:   38.142 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 166210
  mean =      5.772 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 47478 
    [ 5.000,  7.500) = 105390 
    [ 7.500, 10.000) = 10221 
    [10.000, 12.500) = 2203 
    [12.500, 15.000) = 420 
    [15.000, 17.500) = 208 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      2.228 ms/op
     p(50.0000) =      5.456 ms/op
     p(90.0000) =      7.217 ms/op
     p(95.0000) =      8.184 ms/op
     p(99.0000) =     11.174 ms/op
     p(99.9000) =     26.142 ms/op
     p(99.9900) =     35.389 ms/op
     p(99.9990) =     38.142 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 19.814 ±(99.9%) 0.306 ms/op
# Warmup Iteration   2: 7.576 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 5.930 ±(99.9%) 0.024 ms/op
Iteration   1: 5.773 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.138 ms/op
                 existUser·p0.50:   5.333 ms/op
                 existUser·p0.90:   7.600 ms/op
                 existUser·p0.95:   8.880 ms/op
                 existUser·p0.99:   11.929 ms/op
                 existUser·p0.999:  28.745 ms/op
                 existUser·p0.9999: 31.281 ms/op
                 existUser·p1.00:   33.948 ms/op

Iteration   2: 5.669 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.956 ms/op
                 existUser·p0.50:   5.308 ms/op
                 existUser·p0.90:   7.193 ms/op
                 existUser·p0.95:   8.389 ms/op
                 existUser·p0.99:   11.452 ms/op
                 existUser·p0.999:  14.886 ms/op
                 existUser·p0.9999: 31.452 ms/op
                 existUser·p1.00:   32.637 ms/op

Iteration   3: 5.674 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.384 ms/op
                 existUser·p0.50:   5.358 ms/op
                 existUser·p0.90:   7.012 ms/op
                 existUser·p0.95:   8.045 ms/op
                 existUser·p0.99:   11.125 ms/op
                 existUser·p0.999:  17.727 ms/op
                 existUser·p0.9999: 32.813 ms/op
                 existUser·p1.00:   33.325 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 168191
  mean =      5.705 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 54301 
    [ 5.000,  7.500) = 99548 
    [ 7.500, 10.000) = 10669 
    [10.000, 12.500) = 2708 
    [12.500, 15.000) = 669 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.956 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      7.242 ms/op
     p(95.0000) =      8.487 ms/op
     p(99.0000) =     11.485 ms/op
     p(99.9000) =     18.993 ms/op
     p(99.9900) =     31.895 ms/op
     p(99.9990) =     33.724 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:14
# Fork: 1 of 1
# Warmup Iteration   1: 17.911 ±(99.9%) 0.295 ms/op
# Warmup Iteration   2: 7.035 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.058 ±(99.9%) 0.030 ms/op
Iteration   1: 5.988 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   2.261 ms/op
                 getUser·p0.50:   5.505 ms/op
                 getUser·p0.90:   7.479 ms/op
                 getUser·p0.95:   9.486 ms/op
                 getUser·p0.99:   15.696 ms/op
                 getUser·p0.999:  26.024 ms/op
                 getUser·p0.9999: 28.693 ms/op
                 getUser·p1.00:   29.524 ms/op

Iteration   2: 6.052 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   2.212 ms/op
                 getUser·p0.50:   5.612 ms/op
                 getUser·p0.90:   7.725 ms/op
                 getUser·p0.95:   9.388 ms/op
                 getUser·p0.99:   13.484 ms/op
                 getUser·p0.999:  27.006 ms/op
                 getUser·p0.9999: 32.637 ms/op
                 getUser·p1.00:   33.227 ms/op

Iteration   3: 5.832 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.888 ms/op
                 getUser·p0.50:   5.513 ms/op
                 getUser·p0.90:   7.037 ms/op
                 getUser·p0.95:   8.208 ms/op
                 getUser·p0.99:   11.829 ms/op
                 getUser·p0.999:  30.048 ms/op
                 getUser·p0.9999: 36.537 ms/op
                 getUser·p1.00:   37.880 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 161197
  mean =      5.956 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 35956 
    [ 5.000,  7.500) = 109966 
    [ 7.500, 10.000) = 9807 
    [10.000, 12.500) = 3174 
    [12.500, 15.000) = 1102 
    [15.000, 17.500) = 613 
    [17.500, 20.000) = 264 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      2.212 ms/op
     p(50.0000) =      5.546 ms/op
     p(90.0000) =      7.397 ms/op
     p(95.0000) =      8.946 ms/op
     p(99.0000) =     13.615 ms/op
     p(99.9000) =     26.890 ms/op
     p(99.9900) =     35.227 ms/op
     p(99.9990) =     37.238 ms/op
     p(99.9999) =     37.880 ms/op
    p(100.0000) =     37.880 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 22.415 ±(99.9%) 0.419 ms/op
# Warmup Iteration   2: 8.464 ±(99.9%) 0.067 ms/op
# Warmup Iteration   3: 7.190 ±(99.9%) 0.033 ms/op
Iteration   1: 6.750 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.707 ms/op
                 listUser·p0.50:   6.341 ms/op
                 listUser·p0.90:   8.389 ms/op
                 listUser·p0.95:   9.798 ms/op
                 listUser·p0.99:   12.943 ms/op
                 listUser·p0.999:  30.900 ms/op
                 listUser·p0.9999: 34.399 ms/op
                 listUser·p1.00:   35.586 ms/op

Iteration   2: 6.948 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   3.052 ms/op
                 listUser·p0.50:   6.529 ms/op
                 listUser·p0.90:   8.667 ms/op
                 listUser·p0.95:   10.060 ms/op
                 listUser·p0.99:   13.697 ms/op
                 listUser·p0.999:  34.009 ms/op
                 listUser·p0.9999: 38.301 ms/op
                 listUser·p1.00:   41.746 ms/op

Iteration   3: 6.819 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.666 ms/op
                 listUser·p0.50:   6.447 ms/op
                 listUser·p0.90:   8.471 ms/op
                 listUser·p0.95:   9.568 ms/op
                 listUser·p0.99:   12.222 ms/op
                 listUser·p0.999:  30.347 ms/op
                 listUser·p0.9999: 34.660 ms/op
                 listUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 140340
  mean =      6.838 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2988 
    [ 5.000, 10.000) = 131024 
    [10.000, 15.000) = 5592 
    [15.000, 20.000) = 402 
    [20.000, 25.000) = 46 
    [25.000, 30.000) = 96 
    [30.000, 35.000) = 152 
    [35.000, 40.000) = 39 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.666 ms/op
     p(50.0000) =      6.431 ms/op
     p(90.0000) =      8.520 ms/op
     p(95.0000) =      9.781 ms/op
     p(99.0000) =     13.009 ms/op
     p(99.9000) =     31.687 ms/op
     p(99.9900) =     36.368 ms/op
     p(99.9990) =     40.874 ms/op
     p(99.9999) =     41.746 ms/op
    p(100.0000) =     41.746 ms/op


# Run complete. Total time: 00:13:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.484 ± 5.681  ops/ms
ClientPb.existUser                       thrpt       3   5.748 ± 1.962  ops/ms
ClientPb.getUser                         thrpt       3   5.492 ± 1.622  ops/ms
ClientPb.listUser                        thrpt       3   4.589 ± 0.461  ops/ms
ClientPb.createUser                       avgt       3   5.874 ± 4.252   ms/op
ClientPb.existUser                        avgt       3   5.665 ± 2.527   ms/op
ClientPb.getUser                          avgt       3   6.006 ± 4.231   ms/op
ClientPb.listUser                         avgt       3   6.888 ± 1.096   ms/op
ClientPb.createUser                     sample  166210   5.772 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.228           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.456           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.217           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.184           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.174           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.142           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.389           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.142           ms/op
ClientPb.existUser                      sample  168191   5.705 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.956           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.333           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.242           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.487           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.485           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.993           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.895           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.948           ms/op
ClientPb.getUser                        sample  161197   5.956 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.212           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.546           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.397           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.946           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.615           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.890           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.227           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.880           ms/op
ClientPb.listUser                       sample  140340   6.838 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.666           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.431           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.520           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.781           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.009           ms/op
ClientPb.listUser:listUser·p0.999       sample          31.687           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.368           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.746           ms/op
