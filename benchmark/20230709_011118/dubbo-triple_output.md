# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.868 ops/ms
# Warmup Iteration   2: 4.587 ops/ms
# Warmup Iteration   3: 8.385 ops/ms
Iteration   1: 8.644 ops/ms
Iteration   2: 8.920 ops/ms
Iteration   3: 9.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.015 ±(99.9%) 7.767 ops/ms [Average]
  (min, avg, max) = (8.644, 9.015, 9.480), stdev = 0.426
  CI (99.9%): [1.248, 16.782] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.042 ops/ms
# Warmup Iteration   2: 8.044 ops/ms
# Warmup Iteration   3: 9.307 ops/ms
Iteration   1: 9.550 ops/ms
Iteration   2: 9.660 ops/ms
Iteration   3: 9.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.553 ±(99.9%) 1.942 ops/ms [Average]
  (min, avg, max) = (9.448, 9.553, 9.660), stdev = 0.106
  CI (99.9%): [7.611, 11.495] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.036 ops/ms
# Warmup Iteration   2: 8.268 ops/ms
# Warmup Iteration   3: 8.734 ops/ms
Iteration   1: 9.375 ops/ms
Iteration   2: 9.418 ops/ms
Iteration   3: 9.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.312 ±(99.9%) 2.720 ops/ms [Average]
  (min, avg, max) = (9.141, 9.312, 9.418), stdev = 0.149
  CI (99.9%): [6.592, 12.032] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.528 ops/ms
# Warmup Iteration   2: 7.111 ops/ms
# Warmup Iteration   3: 7.832 ops/ms
Iteration   1: 7.900 ops/ms
Iteration   2: 7.782 ops/ms
Iteration   3: 7.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.844 ±(99.9%) 1.083 ops/ms [Average]
  (min, avg, max) = (7.782, 7.844, 7.900), stdev = 0.059
  CI (99.9%): [6.761, 8.928] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.278 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.806 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.665 ±(99.9%) 0.008 ms/op
Iteration   1: 3.704 ±(99.9%) 0.004 ms/op
Iteration   2: 3.490 ±(99.9%) 0.003 ms/op
Iteration   3: 3.442 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.546 ±(99.9%) 2.541 ms/op [Average]
  (min, avg, max) = (3.442, 3.546, 3.704), stdev = 0.139
  CI (99.9%): [1.004, 6.087] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.831 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.550 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.006 ms/op
Iteration   1: 3.330 ±(99.9%) 0.009 ms/op
Iteration   2: 3.255 ±(99.9%) 0.005 ms/op
Iteration   3: 3.297 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.294 ±(99.9%) 0.684 ms/op [Average]
  (min, avg, max) = (3.255, 3.294, 3.330), stdev = 0.037
  CI (99.9%): [2.610, 3.978] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.877 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.845 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.599 ±(99.9%) 0.007 ms/op
Iteration   1: 3.550 ±(99.9%) 0.005 ms/op
Iteration   2: 3.342 ±(99.9%) 0.006 ms/op
Iteration   3: 3.622 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.505 ±(99.9%) 2.652 ms/op [Average]
  (min, avg, max) = (3.342, 3.505, 3.622), stdev = 0.145
  CI (99.9%): [0.853, 6.157] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.009 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.758 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.129 ±(99.9%) 0.011 ms/op
Iteration   1: 4.123 ±(99.9%) 0.007 ms/op
Iteration   2: 3.977 ±(99.9%) 0.011 ms/op
Iteration   3: 4.020 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.040 ±(99.9%) 1.372 ms/op [Average]
  (min, avg, max) = (3.977, 4.040, 4.123), stdev = 0.075
  CI (99.9%): [2.668, 5.412] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.889 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.012 ms/op
Iteration   1: 3.491 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.544 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  9.241 ms/op
                 createUser·p0.9999: 22.567 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   2: 3.624 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.221 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.144 ms/op
                 createUser·p0.999:  23.490 ms/op
                 createUser·p0.9999: 27.787 ms/op
                 createUser·p1.00:   28.836 ms/op

Iteration   3: 3.505 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.448 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  24.601 ms/op
                 createUser·p0.9999: 29.647 ms/op
                 createUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270971
  mean =      3.539 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4795 
    [ 2.500,  5.000) = 258891 
    [ 5.000,  7.500) = 6303 
    [ 7.500, 10.000) = 659 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     11.092 ms/op
     p(99.9900) =     28.734 ms/op
     p(99.9990) =     30.096 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.268 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.275 ±(99.9%) 0.008 ms/op
Iteration   1: 3.223 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.616 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   5.363 ms/op
                 existUser·p0.999:  10.578 ms/op
                 existUser·p0.9999: 24.580 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   2: 3.364 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.341 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  11.091 ms/op
                 existUser·p0.9999: 24.215 ms/op
                 existUser·p1.00:   25.199 ms/op

Iteration   3: 3.339 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.280 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   6.250 ms/op
                 existUser·p0.999:  19.051 ms/op
                 existUser·p0.9999: 26.621 ms/op
                 existUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290314
  mean =      3.307 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11567 
    [ 2.500,  5.000) = 273147 
    [ 5.000,  7.500) = 4659 
    [ 7.500, 10.000) = 556 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 169 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     11.715 ms/op
     p(99.9900) =     26.114 ms/op
     p(99.9990) =     26.968 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.166 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.776 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.740 ±(99.9%) 0.013 ms/op
Iteration   1: 3.750 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.753 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   5.161 ms/op
                 getUser·p0.95:   5.759 ms/op
                 getUser·p0.99:   7.832 ms/op
                 getUser·p0.999:  17.260 ms/op
                 getUser·p0.9999: 29.029 ms/op
                 getUser·p1.00:   29.852 ms/op

Iteration   2: 3.534 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.497 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  22.120 ms/op
                 getUser·p0.9999: 24.838 ms/op
                 getUser·p1.00:   25.494 ms/op

Iteration   3: 3.508 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.661 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  23.338 ms/op
                 getUser·p0.9999: 31.949 ms/op
                 getUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 266846
  mean =      3.594 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6392 
    [ 2.500,  5.000) = 243373 
    [ 5.000,  7.500) = 15132 
    [ 7.500, 10.000) = 1398 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     17.347 ms/op
     p(99.9900) =     29.862 ms/op
     p(99.9990) =     32.134 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.209 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.480 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.077 ±(99.9%) 0.014 ms/op
Iteration   1: 4.146 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.501 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  17.436 ms/op
                 listUser·p0.9999: 21.940 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   2: 4.049 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.105 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.717 ms/op
                 listUser·p0.999:  16.007 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   3: 4.049 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  14.762 ms/op
                 listUser·p0.9999: 17.344 ms/op
                 listUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235275
  mean =      4.081 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 224237 
    [ 5.000,  7.500) = 8539 
    [ 7.500, 10.000) = 1681 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 211 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.501 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     15.691 ms/op
     p(99.9900) =     20.544 ms/op
     p(99.9990) =     22.259 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.015 ± 7.767  ops/ms
ClientPb.existUser                       thrpt       3   9.553 ± 1.942  ops/ms
ClientPb.getUser                         thrpt       3   9.312 ± 2.720  ops/ms
ClientPb.listUser                        thrpt       3   7.844 ± 1.083  ops/ms
ClientPb.createUser                       avgt       3   3.546 ± 2.541   ms/op
ClientPb.existUser                        avgt       3   3.294 ± 0.684   ms/op
ClientPb.getUser                          avgt       3   3.505 ± 2.652   ms/op
ClientPb.listUser                         avgt       3   4.040 ± 1.372   ms/op
ClientPb.createUser                     sample  270971   3.539 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.221           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.416           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.096           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.563           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.062           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.092           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.734           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.310           ms/op
ClientPb.existUser                      sample  290314   3.307 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.280           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.677           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.715           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.114           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.001           ms/op
ClientPb.getUser                        sample  266846   3.594 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.497           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.428           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.178           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.153           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.021           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.347           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.862           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.309           ms/op
ClientPb.listUser                       sample  235275   4.081 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.501           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.594           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.691           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.544           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.708           ms/op
