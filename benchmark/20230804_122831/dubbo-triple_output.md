# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.981 ops/ms
# Warmup Iteration   2: 2.136 ops/ms
# Warmup Iteration   3: 4.720 ops/ms
Iteration   1: 5.077 ops/ms
Iteration   2: 5.294 ops/ms
Iteration   3: 5.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.297 ±(99.9%) 4.034 ops/ms [Average]
  (min, avg, max) = (5.077, 5.297, 5.519), stdev = 0.221
  CI (99.9%): [1.263, 9.331] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:18
# Fork: 1 of 1
# Warmup Iteration   1: 1.365 ops/ms
# Warmup Iteration   2: 4.038 ops/ms
# Warmup Iteration   3: 5.300 ops/ms
Iteration   1: 5.508 ops/ms
Iteration   2: 5.712 ops/ms
Iteration   3: 5.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.670 ±(99.9%) 2.646 ops/ms [Average]
  (min, avg, max) = (5.508, 5.670, 5.788), stdev = 0.145
  CI (99.9%): [3.024, 8.316] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.421 ops/ms
# Warmup Iteration   2: 3.951 ops/ms
# Warmup Iteration   3: 5.249 ops/ms
Iteration   1: 5.248 ops/ms
Iteration   2: 5.406 ops/ms
Iteration   3: 5.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.255 ±(99.9%) 2.689 ops/ms [Average]
  (min, avg, max) = (5.112, 5.255, 5.406), stdev = 0.147
  CI (99.9%): [2.566, 7.945] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.244 ops/ms
# Warmup Iteration   2: 3.221 ops/ms
# Warmup Iteration   3: 4.284 ops/ms
Iteration   1: 4.423 ops/ms
Iteration   2: 4.575 ops/ms
Iteration   3: 4.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.536 ±(99.9%) 1.800 ops/ms [Average]
  (min, avg, max) = (4.423, 4.536, 4.608), stdev = 0.099
  CI (99.9%): [2.735, 6.336] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 20.291 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 7.554 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.409 ±(99.9%) 0.008 ms/op
Iteration   1: 6.183 ±(99.9%) 0.013 ms/op
Iteration   2: 6.022 ±(99.9%) 0.017 ms/op
Iteration   3: 5.948 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.051 ±(99.9%) 2.186 ms/op [Average]
  (min, avg, max) = (5.948, 6.051, 6.183), stdev = 0.120
  CI (99.9%): [3.865, 8.237] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.737 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 7.138 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.727 ±(99.9%) 0.012 ms/op
Iteration   1: 5.558 ±(99.9%) 0.024 ms/op
Iteration   2: 5.601 ±(99.9%) 0.014 ms/op
Iteration   3: 5.651 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.604 ±(99.9%) 0.848 ms/op [Average]
  (min, avg, max) = (5.558, 5.604, 5.651), stdev = 0.046
  CI (99.9%): [4.755, 6.452] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 19.372 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 7.732 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.034 ±(99.9%) 0.011 ms/op
Iteration   1: 6.032 ±(99.9%) 0.011 ms/op
Iteration   2: 5.996 ±(99.9%) 0.013 ms/op
Iteration   3: 5.764 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.931 ±(99.9%) 2.652 ms/op [Average]
  (min, avg, max) = (5.764, 5.931, 6.032), stdev = 0.145
  CI (99.9%): [3.279, 8.583] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 23.769 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 9.045 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 7.257 ±(99.9%) 0.013 ms/op
Iteration   1: 7.095 ±(99.9%) 0.015 ms/op
Iteration   2: 6.913 ±(99.9%) 0.010 ms/op
Iteration   3: 6.720 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.909 ±(99.9%) 3.428 ms/op [Average]
  (min, avg, max) = (6.720, 6.909, 7.095), stdev = 0.188
  CI (99.9%): [3.481, 10.338] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 21.405 ±(99.9%) 0.405 ms/op
# Warmup Iteration   2: 8.123 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.480 ±(99.9%) 0.032 ms/op
Iteration   1: 5.965 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.952 ms/op
                 createUser·p0.50:   5.677 ms/op
                 createUser·p0.90:   7.348 ms/op
                 createUser·p0.95:   8.118 ms/op
                 createUser·p0.99:   10.946 ms/op
                 createUser·p0.999:  16.702 ms/op
                 createUser·p0.9999: 27.591 ms/op
                 createUser·p1.00:   28.803 ms/op

Iteration   2: 6.186 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.474 ms/op
                 createUser·p0.50:   5.898 ms/op
                 createUser·p0.90:   7.610 ms/op
                 createUser·p0.95:   8.864 ms/op
                 createUser·p0.99:   12.304 ms/op
                 createUser·p0.999:  28.796 ms/op
                 createUser·p0.9999: 34.909 ms/op
                 createUser·p1.00:   35.848 ms/op

Iteration   3: 5.986 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   2.449 ms/op
                 createUser·p0.50:   5.603 ms/op
                 createUser·p0.90:   7.340 ms/op
                 createUser·p0.95:   8.536 ms/op
                 createUser·p0.99:   12.419 ms/op
                 createUser·p0.999:  32.397 ms/op
                 createUser·p0.9999: 41.646 ms/op
                 createUser·p1.00:   43.713 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 158650
  mean =      6.044 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 25561 
    [ 5.000, 10.000) = 129493 
    [10.000, 15.000) = 3102 
    [15.000, 20.000) = 246 
    [20.000, 25.000) = 18 
    [25.000, 30.000) = 80 
    [30.000, 35.000) = 118 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.952 ms/op
     p(50.0000) =      5.718 ms/op
     p(90.0000) =      7.430 ms/op
     p(95.0000) =      8.487 ms/op
     p(99.0000) =     11.813 ms/op
     p(99.9000) =     29.819 ms/op
     p(99.9900) =     36.700 ms/op
     p(99.9990) =     43.674 ms/op
     p(99.9999) =     43.713 ms/op
    p(100.0000) =     43.713 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 19.401 ±(99.9%) 0.352 ms/op
# Warmup Iteration   2: 7.198 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.800 ±(99.9%) 0.021 ms/op
Iteration   1: 5.684 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.650 ms/op
                 existUser·p0.50:   5.341 ms/op
                 existUser·p0.90:   6.996 ms/op
                 existUser·p0.95:   8.241 ms/op
                 existUser·p0.99:   11.508 ms/op
                 existUser·p0.999:  27.737 ms/op
                 existUser·p0.9999: 30.085 ms/op
                 existUser·p1.00:   30.867 ms/op

Iteration   2: 5.675 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.666 ms/op
                 existUser·p0.50:   5.341 ms/op
                 existUser·p0.90:   7.029 ms/op
                 existUser·p0.95:   8.086 ms/op
                 existUser·p0.99:   11.256 ms/op
                 existUser·p0.999:  27.251 ms/op
                 existUser·p0.9999: 29.655 ms/op
                 existUser·p1.00:   30.605 ms/op

Iteration   3: 5.498 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.593 ms/op
                 existUser·p0.50:   5.169 ms/op
                 existUser·p0.90:   6.701 ms/op
                 existUser·p0.95:   7.692 ms/op
                 existUser·p0.99:   10.830 ms/op
                 existUser·p0.999:  16.777 ms/op
                 existUser·p0.9999: 30.918 ms/op
                 existUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 170778
  mean =      5.618 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 53601 
    [ 5.000,  7.500) = 105722 
    [ 7.500, 10.000) = 8367 
    [10.000, 12.500) = 2081 
    [12.500, 15.000) = 607 
    [15.000, 17.500) = 172 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 118 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.593 ms/op
     p(50.0000) =      5.284 ms/op
     p(90.0000) =      6.906 ms/op
     p(95.0000) =      7.979 ms/op
     p(99.0000) =     11.190 ms/op
     p(99.9000) =     19.956 ms/op
     p(99.9900) =     30.603 ms/op
     p(99.9990) =     31.314 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 20.402 ±(99.9%) 0.336 ms/op
# Warmup Iteration   2: 7.660 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 5.989 ±(99.9%) 0.022 ms/op
Iteration   1: 6.127 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.773 ms/op
                 getUser·p0.50:   5.743 ms/op
                 getUser·p0.90:   7.569 ms/op
                 getUser·p0.95:   9.257 ms/op
                 getUser·p0.99:   12.583 ms/op
                 getUser·p0.999:  25.018 ms/op
                 getUser·p0.9999: 30.034 ms/op
                 getUser·p1.00:   30.638 ms/op

Iteration   2: 5.968 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.830 ms/op
                 getUser·p0.50:   5.595 ms/op
                 getUser·p0.90:   7.234 ms/op
                 getUser·p0.95:   8.667 ms/op
                 getUser·p0.99:   13.157 ms/op
                 getUser·p0.999:  24.242 ms/op
                 getUser·p0.9999: 31.216 ms/op
                 getUser·p1.00:   32.014 ms/op

Iteration   3: 5.999 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.884 ms/op
                 getUser·p0.50:   5.718 ms/op
                 getUser·p0.90:   7.225 ms/op
                 getUser·p0.95:   8.249 ms/op
                 getUser·p0.99:   11.551 ms/op
                 getUser·p0.999:  25.877 ms/op
                 getUser·p0.9999: 31.370 ms/op
                 getUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 159044
  mean =      6.031 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 23845 
    [ 5.000,  7.500) = 120948 
    [ 7.500, 10.000) = 9882 
    [10.000, 12.500) = 2799 
    [12.500, 15.000) = 909 
    [15.000, 17.500) = 351 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.884 ms/op
     p(50.0000) =      5.685 ms/op
     p(90.0000) =      7.332 ms/op
     p(95.0000) =      8.815 ms/op
     p(99.0000) =     12.468 ms/op
     p(99.9000) =     25.030 ms/op
     p(99.9900) =     31.005 ms/op
     p(99.9990) =     33.051 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.353 ±(99.9%) 0.355 ms/op
# Warmup Iteration   2: 9.131 ±(99.9%) 0.076 ms/op
# Warmup Iteration   3: 7.202 ±(99.9%) 0.035 ms/op
Iteration   1: 6.727 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.720 ms/op
                 listUser·p0.50:   6.316 ms/op
                 listUser·p0.90:   8.053 ms/op
                 listUser·p0.95:   9.732 ms/op
                 listUser·p0.99:   12.976 ms/op
                 listUser·p0.999:  30.245 ms/op
                 listUser·p0.9999: 32.721 ms/op
                 listUser·p1.00:   33.620 ms/op

Iteration   2: 6.959 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.416 ms/op
                 listUser·p0.50:   6.545 ms/op
                 listUser·p0.90:   8.520 ms/op
                 listUser·p0.95:   9.519 ms/op
                 listUser·p0.99:   12.747 ms/op
                 listUser·p0.999:  32.571 ms/op
                 listUser·p0.9999: 35.141 ms/op
                 listUser·p1.00:   36.700 ms/op

Iteration   3: 7.073 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.076 ms/op
                 listUser·p0.50:   6.726 ms/op
                 listUser·p0.90:   8.471 ms/op
                 listUser·p0.95:   9.814 ms/op
                 listUser·p0.99:   13.140 ms/op
                 listUser·p0.999:  31.500 ms/op
                 listUser·p0.9999: 37.608 ms/op
                 listUser·p1.00:   38.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 138832
  mean =      6.916 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 2303 
    [ 5.000,  7.500) = 107809 
    [ 7.500, 10.000) = 22702 
    [10.000, 12.500) = 4349 
    [12.500, 15.000) = 1093 
    [15.000, 17.500) = 272 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 118 
    [32.500, 35.000) = 53 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      2.720 ms/op
     p(50.0000) =      6.529 ms/op
     p(90.0000) =      8.405 ms/op
     p(95.0000) =      9.683 ms/op
     p(99.0000) =     12.943 ms/op
     p(99.9000) =     31.403 ms/op
     p(99.9900) =     36.118 ms/op
     p(99.9990) =     38.207 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.297 ± 4.034  ops/ms
ClientPb.existUser                       thrpt       3   5.670 ± 2.646  ops/ms
ClientPb.getUser                         thrpt       3   5.255 ± 2.689  ops/ms
ClientPb.listUser                        thrpt       3   4.536 ± 1.800  ops/ms
ClientPb.createUser                       avgt       3   6.051 ± 2.186   ms/op
ClientPb.existUser                        avgt       3   5.604 ± 0.848   ms/op
ClientPb.getUser                          avgt       3   5.931 ± 2.652   ms/op
ClientPb.listUser                         avgt       3   6.909 ± 3.428   ms/op
ClientPb.createUser                     sample  158650   6.044 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.952           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.718           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.430           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.487           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.813           ms/op
ClientPb.createUser:createUser·p0.999   sample          29.819           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.700           ms/op
ClientPb.createUser:createUser·p1.00    sample          43.713           ms/op
ClientPb.existUser                      sample  170778   5.618 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.593           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.284           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.906           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.979           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.190           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.956           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.603           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.523           ms/op
ClientPb.getUser                        sample  159044   6.031 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.884           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.685           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.332           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.815           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.468           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.030           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.005           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.554           ms/op
ClientPb.listUser                       sample  138832   6.916 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.720           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.529           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.405           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.683           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.943           ms/op
ClientPb.listUser:listUser·p0.999       sample          31.403           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.118           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.207           ms/op
