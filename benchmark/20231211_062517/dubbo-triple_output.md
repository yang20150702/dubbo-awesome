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
# Warmup Iteration   1: 4.898 ops/ms
# Warmup Iteration   2: 12.059 ops/ms
# Warmup Iteration   3: 12.373 ops/ms
Iteration   1: 12.658 ops/ms
Iteration   2: 12.760 ops/ms
Iteration   3: 12.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.683 ±(99.9%) 1.256 ops/ms [Average]
  (min, avg, max) = (12.629, 12.683, 12.760), stdev = 0.069
  CI (99.9%): [11.426, 13.939] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.220 ops/ms
# Warmup Iteration   2: 13.107 ops/ms
# Warmup Iteration   3: 13.112 ops/ms
Iteration   1: 13.189 ops/ms
Iteration   2: 13.257 ops/ms
Iteration   3: 13.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.206 ±(99.9%) 0.805 ops/ms [Average]
  (min, avg, max) = (13.174, 13.206, 13.257), stdev = 0.044
  CI (99.9%): [12.401, 14.012] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.570 ops/ms
# Warmup Iteration   2: 12.744 ops/ms
# Warmup Iteration   3: 12.582 ops/ms
Iteration   1: 12.704 ops/ms
Iteration   2: 12.850 ops/ms
Iteration   3: 12.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.785 ±(99.9%) 1.357 ops/ms [Average]
  (min, avg, max) = (12.704, 12.785, 12.850), stdev = 0.074
  CI (99.9%): [11.429, 14.142] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.687 ops/ms
# Warmup Iteration   2: 10.376 ops/ms
# Warmup Iteration   3: 10.528 ops/ms
Iteration   1: 10.512 ops/ms
Iteration   2: 10.591 ops/ms
Iteration   3: 10.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.534 ±(99.9%) 0.917 ops/ms [Average]
  (min, avg, max) = (10.498, 10.534, 10.591), stdev = 0.050
  CI (99.9%): [9.617, 11.450] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.069 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
Iteration   1: 2.485 ±(99.9%) 0.004 ms/op
Iteration   2: 2.550 ±(99.9%) 0.004 ms/op
Iteration   3: 2.491 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.509 ±(99.9%) 0.652 ms/op [Average]
  (min, avg, max) = (2.485, 2.509, 2.550), stdev = 0.036
  CI (99.9%): [1.857, 3.160] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.611 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.004 ms/op
Iteration   1: 2.458 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
Iteration   3: 2.430 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.453 ±(99.9%) 0.376 ms/op [Average]
  (min, avg, max) = (2.430, 2.453, 2.470), stdev = 0.021
  CI (99.9%): [2.077, 2.829] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.772 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.493 ±(99.9%) 0.003 ms/op
Iteration   3: 2.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.493 ±(99.9%) 0.162 ms/op [Average]
  (min, avg, max) = (2.484, 2.493, 2.502), stdev = 0.009
  CI (99.9%): [2.331, 2.655] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.742 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
Iteration   1: 2.970 ±(99.9%) 0.006 ms/op
Iteration   2: 2.974 ±(99.9%) 0.004 ms/op
Iteration   3: 2.992 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.979 ±(99.9%) 0.212 ms/op [Average]
  (min, avg, max) = (2.970, 2.979, 2.992), stdev = 0.012
  CI (99.9%): [2.767, 3.191] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.170 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.661 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.006 ms/op
Iteration   1: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  11.321 ms/op
                 createUser·p0.9999: 14.052 ms/op
                 createUser·p1.00:   14.451 ms/op

Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.165 ms/op
                 createUser·p0.99:   3.635 ms/op
                 createUser·p0.999:  9.945 ms/op
                 createUser·p0.9999: 12.403 ms/op
                 createUser·p1.00:   12.878 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.816 ms/op
                 createUser·p0.999:  9.519 ms/op
                 createUser·p0.9999: 11.282 ms/op
                 createUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381136
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 181863 
    [ 2.500,  3.750) = 195487 
    [ 3.750,  5.000) = 2972 
    [ 5.000,  6.250) = 290 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      9.533 ms/op
     p(99.9900) =     13.173 ms/op
     p(99.9990) =     14.326 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.731 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  7.284 ms/op
                 existUser·p0.9999: 14.041 ms/op
                 existUser·p1.00:   15.811 ms/op

Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.016 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  6.202 ms/op
                 existUser·p0.9999: 12.928 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.963 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  8.955 ms/op
                 existUser·p0.9999: 11.699 ms/op
                 existUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388444
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 191949 
    [ 2.500,  3.750) = 193640 
    [ 3.750,  5.000) = 2087 
    [ 5.000,  6.250) = 293 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.555 ms/op
     p(99.9000) =      7.075 ms/op
     p(99.9900) =     13.189 ms/op
     p(99.9990) =     14.664 ms/op
     p(99.9999) =     15.811 ms/op
    p(100.0000) =     15.811 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.881 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.587 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
Iteration   1: 2.503 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  11.269 ms/op
                 getUser·p0.9999: 15.376 ms/op
                 getUser·p1.00:   15.712 ms/op

Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.596 ms/op
                 getUser·p0.999:  6.728 ms/op
                 getUser·p0.9999: 13.781 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   3: 2.546 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  8.641 ms/op
                 getUser·p0.9999: 12.692 ms/op
                 getUser·p1.00:   13.500 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382220
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 187813 
    [ 2.500,  3.750) = 189376 
    [ 3.750,  5.000) = 3431 
    [ 5.000,  6.250) = 1088 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.931 ms/op
     p(99.9000) =      8.634 ms/op
     p(99.9900) =     14.427 ms/op
     p(99.9990) =     15.633 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.561 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.008 ms/op
Iteration   1: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  8.684 ms/op
                 listUser·p0.9999: 11.835 ms/op
                 listUser·p1.00:   12.763 ms/op

Iteration   2: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  10.166 ms/op
                 listUser·p0.9999: 11.514 ms/op
                 listUser·p1.00:   12.780 ms/op

Iteration   3: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  8.761 ms/op
                 listUser·p0.9999: 10.451 ms/op
                 listUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318709
  mean =      3.009 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 90695 
    [ 2.500,  3.750) = 189227 
    [ 3.750,  5.000) = 31999 
    [ 5.000,  6.250) = 5478 
    [ 6.250,  7.500) = 587 
    [ 7.500,  8.750) = 224 
    [ 8.750, 10.000) = 192 
    [10.000, 11.250) = 125 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.294 ms/op
     p(99.9900) =     11.541 ms/op
     p(99.9990) =     12.739 ms/op
     p(99.9999) =     12.780 ms/op
    p(100.0000) =     12.780 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.683 ± 1.256  ops/ms
ClientPb.existUser                       thrpt       3  13.206 ± 0.805  ops/ms
ClientPb.getUser                         thrpt       3  12.785 ± 1.357  ops/ms
ClientPb.listUser                        thrpt       3  10.534 ± 0.917  ops/ms
ClientPb.createUser                       avgt       3   2.509 ± 0.652   ms/op
ClientPb.existUser                        avgt       3   2.453 ± 0.376   ms/op
ClientPb.getUser                          avgt       3   2.493 ± 0.162   ms/op
ClientPb.listUser                         avgt       3   2.979 ± 0.212   ms/op
ClientPb.createUser                     sample  381136   2.516 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.920           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.533           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.173           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.219           ms/op
ClientPb.existUser                      sample  388444   2.469 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.862           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.075           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.189           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.811           ms/op
ClientPb.getUser                        sample  382220   2.509 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.741           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.931           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.634           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.427           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.712           ms/op
ClientPb.listUser                       sample  318709   3.009 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.902           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.294           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.541           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.780           ms/op
