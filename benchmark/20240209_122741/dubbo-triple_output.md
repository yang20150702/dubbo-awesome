# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.910 ops/ms
# Warmup Iteration   2: 11.658 ops/ms
# Warmup Iteration   3: 12.262 ops/ms
Iteration   1: 12.314 ops/ms
Iteration   2: 12.386 ops/ms
Iteration   3: 12.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.399 ±(99.9%) 1.697 ops/ms [Average]
  (min, avg, max) = (12.314, 12.399, 12.498), stdev = 0.093
  CI (99.9%): [10.702, 14.096] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.560 ops/ms
# Warmup Iteration   2: 12.893 ops/ms
# Warmup Iteration   3: 12.908 ops/ms
Iteration   1: 12.919 ops/ms
Iteration   2: 12.972 ops/ms
Iteration   3: 13.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.978 ±(99.9%) 1.123 ops/ms [Average]
  (min, avg, max) = (12.919, 12.978, 13.042), stdev = 0.062
  CI (99.9%): [11.855, 14.101] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.489 ops/ms
# Warmup Iteration   2: 12.587 ops/ms
# Warmup Iteration   3: 12.782 ops/ms
Iteration   1: 12.950 ops/ms
Iteration   2: 12.779 ops/ms
Iteration   3: 12.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.848 ±(99.9%) 1.645 ops/ms [Average]
  (min, avg, max) = (12.779, 12.848, 12.950), stdev = 0.090
  CI (99.9%): [11.203, 14.493] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.774 ops/ms
# Warmup Iteration   2: 10.464 ops/ms
# Warmup Iteration   3: 10.608 ops/ms
Iteration   1: 10.592 ops/ms
Iteration   2: 10.633 ops/ms
Iteration   3: 10.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.616 ±(99.9%) 0.382 ops/ms [Average]
  (min, avg, max) = (10.592, 10.616, 10.633), stdev = 0.021
  CI (99.9%): [10.233, 10.998] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.996 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.003 ms/op
Iteration   1: 2.505 ±(99.9%) 0.004 ms/op
Iteration   2: 2.540 ±(99.9%) 0.003 ms/op
Iteration   3: 2.502 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.516 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (2.502, 2.516, 2.540), stdev = 0.021
  CI (99.9%): [2.133, 2.899] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.622 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
Iteration   1: 2.417 ±(99.9%) 0.004 ms/op
Iteration   2: 2.416 ±(99.9%) 0.003 ms/op
Iteration   3: 2.415 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.416 ±(99.9%) 0.020 ms/op [Average]
  (min, avg, max) = (2.415, 2.416, 2.417), stdev = 0.001
  CI (99.9%): [2.396, 2.436] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.972 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.643 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.520 ±(99.9%) 0.004 ms/op
Iteration   2: 2.504 ±(99.9%) 0.004 ms/op
Iteration   3: 2.529 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.518 ±(99.9%) 0.227 ms/op [Average]
  (min, avg, max) = (2.504, 2.518, 2.529), stdev = 0.012
  CI (99.9%): [2.291, 2.744] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.518 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.005 ms/op
Iteration   1: 3.004 ±(99.9%) 0.005 ms/op
Iteration   2: 3.002 ±(99.9%) 0.005 ms/op
Iteration   3: 2.996 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.000 ±(99.9%) 0.076 ms/op [Average]
  (min, avg, max) = (2.996, 3.000, 3.004), stdev = 0.004
  CI (99.9%): [2.924, 3.076] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.247 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.705 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.570 ±(99.9%) 0.006 ms/op
Iteration   1: 2.543 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  12.059 ms/op
                 createUser·p0.9999: 13.933 ms/op
                 createUser·p1.00:   14.483 ms/op

Iteration   2: 2.571 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.879 ms/op
                 createUser·p0.999:  7.193 ms/op
                 createUser·p0.9999: 12.290 ms/op
                 createUser·p1.00:   13.353 ms/op

Iteration   3: 2.572 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  9.026 ms/op
                 createUser·p0.9999: 13.772 ms/op
                 createUser·p1.00:   15.139 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374350
  mean =      2.562 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 178139 
    [ 2.500,  3.750) = 191825 
    [ 3.750,  5.000) = 3423 
    [ 5.000,  6.250) = 458 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 122 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     13.624 ms/op
     p(99.9990) =     14.828 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.651 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  6.230 ms/op
                 existUser·p0.9999: 18.021 ms/op
                 existUser·p1.00:   18.907 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.149 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  5.663 ms/op
                 existUser·p0.9999: 12.486 ms/op
                 existUser·p1.00:   13.255 ms/op

Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.970 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   4.025 ms/op
                 existUser·p0.999:  9.030 ms/op
                 existUser·p0.9999: 16.955 ms/op
                 existUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387884
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 25 
    [ 1.250,  2.500) = 190940 
    [ 2.500,  3.750) = 193447 
    [ 3.750,  5.000) = 2516 
    [ 5.000,  6.250) = 575 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      6.193 ms/op
     p(99.9900) =     17.039 ms/op
     p(99.9990) =     18.460 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.947 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  6.265 ms/op
                 getUser·p0.9999: 15.024 ms/op
                 getUser·p1.00:   15.827 ms/op

Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  7.421 ms/op
                 getUser·p0.9999: 15.684 ms/op
                 getUser·p1.00:   16.531 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.528 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.883 ms/op
                 getUser·p0.999:  7.888 ms/op
                 getUser·p0.9999: 12.406 ms/op
                 getUser·p1.00:   12.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386199
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 191158 
    [ 2.500,  3.750) = 189370 
    [ 3.750,  5.000) = 4703 
    [ 5.000,  6.250) = 440 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      7.415 ms/op
     p(99.9900) =     14.981 ms/op
     p(99.9990) =     16.231 ms/op
     p(99.9999) =     16.531 ms/op
    p(100.0000) =     16.531 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.633 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.008 ms/op
Iteration   1: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  8.962 ms/op
                 listUser·p0.9999: 10.522 ms/op
                 listUser·p1.00:   11.928 ms/op

Iteration   2: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.001 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 10.851 ms/op
                 listUser·p1.00:   11.715 ms/op

Iteration   3: 3.041 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  9.828 ms/op
                 listUser·p0.9999: 11.821 ms/op
                 listUser·p1.00:   13.926 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316845
  mean =      3.027 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 86917 
    [ 2.500,  3.750) = 191218 
    [ 3.750,  5.000) = 31655 
    [ 5.000,  6.250) = 5706 
    [ 6.250,  7.500) = 593 
    [ 7.500,  8.750) = 198 
    [ 8.750, 10.000) = 280 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     11.572 ms/op
     p(99.9990) =     12.383 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.399 ± 1.697  ops/ms
ClientPb.existUser                       thrpt       3  12.978 ± 1.123  ops/ms
ClientPb.getUser                         thrpt       3  12.848 ± 1.645  ops/ms
ClientPb.listUser                        thrpt       3  10.616 ± 0.382  ops/ms
ClientPb.createUser                       avgt       3   2.516 ± 0.383   ms/op
ClientPb.existUser                        avgt       3   2.416 ± 0.020   ms/op
ClientPb.getUser                          avgt       3   2.518 ± 0.227   ms/op
ClientPb.listUser                         avgt       3   3.000 ± 0.076   ms/op
ClientPb.createUser                     sample  374350   2.562 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.874           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.236           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.126           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.624           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.139           ms/op
ClientPb.existUser                      sample  387884   2.473 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.705           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.193           ms/op
ClientPb.existUser:existUser·p0.9999    sample          17.039           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.907           ms/op
ClientPb.getUser                        sample  386199   2.483 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.528           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.415           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.981           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.531           ms/op
ClientPb.listUser                       sample  316845   3.027 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.867           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.322           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.572           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.926           ms/op
