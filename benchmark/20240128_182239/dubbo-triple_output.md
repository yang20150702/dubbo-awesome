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
# Warmup Iteration   1: 4.287 ops/ms
# Warmup Iteration   2: 11.727 ops/ms
# Warmup Iteration   3: 12.168 ops/ms
Iteration   1: 12.524 ops/ms
Iteration   2: 12.379 ops/ms
Iteration   3: 12.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.412 ±(99.9%) 1.831 ops/ms [Average]
  (min, avg, max) = (12.332, 12.412, 12.524), stdev = 0.100
  CI (99.9%): [10.581, 14.243] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.165 ops/ms
# Warmup Iteration   2: 13.126 ops/ms
# Warmup Iteration   3: 13.064 ops/ms
Iteration   1: 12.964 ops/ms
Iteration   2: 13.052 ops/ms
Iteration   3: 13.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.031 ±(99.9%) 1.094 ops/ms [Average]
  (min, avg, max) = (12.964, 13.031, 13.078), stdev = 0.060
  CI (99.9%): [11.938, 14.125] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.540 ops/ms
# Warmup Iteration   2: 12.510 ops/ms
# Warmup Iteration   3: 12.833 ops/ms
Iteration   1: 12.961 ops/ms
Iteration   2: 12.717 ops/ms
Iteration   3: 12.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.828 ±(99.9%) 2.252 ops/ms [Average]
  (min, avg, max) = (12.717, 12.828, 12.961), stdev = 0.123
  CI (99.9%): [10.576, 15.080] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.774 ops/ms
# Warmup Iteration   2: 10.384 ops/ms
# Warmup Iteration   3: 10.526 ops/ms
Iteration   1: 10.447 ops/ms
Iteration   2: 10.516 ops/ms
Iteration   3: 10.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.493 ±(99.9%) 0.737 ops/ms [Average]
  (min, avg, max) = (10.447, 10.493, 10.518), stdev = 0.040
  CI (99.9%): [9.756, 11.231] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.000 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.566 ±(99.9%) 0.004 ms/op
Iteration   1: 2.592 ±(99.9%) 0.004 ms/op
Iteration   2: 2.583 ±(99.9%) 0.004 ms/op
Iteration   3: 2.559 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.578 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (2.559, 2.578, 2.592), stdev = 0.017
  CI (99.9%): [2.269, 2.887] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.751 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.003 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.492 ±(99.9%) 0.003 ms/op
Iteration   3: 2.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.488 ±(99.9%) 0.176 ms/op [Average]
  (min, avg, max) = (2.477, 2.488, 2.495), stdev = 0.010
  CI (99.9%): [2.312, 2.664] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.846 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.656 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.592 ±(99.9%) 0.005 ms/op
Iteration   1: 2.555 ±(99.9%) 0.004 ms/op
Iteration   2: 2.556 ±(99.9%) 0.003 ms/op
Iteration   3: 2.576 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.562 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (2.555, 2.562, 2.576), stdev = 0.012
  CI (99.9%): [2.348, 2.777] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.618 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.005 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
Iteration   3: 3.021 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.021 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (3.009, 3.021, 3.033), stdev = 0.012
  CI (99.9%): [2.803, 3.240] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.114 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.708 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
Iteration   1: 2.545 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  11.016 ms/op
                 createUser·p0.9999: 13.966 ms/op
                 createUser·p1.00:   14.909 ms/op

Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.006 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.543 ms/op
                 createUser·p0.999:  8.929 ms/op
                 createUser·p0.9999: 11.518 ms/op
                 createUser·p1.00:   11.993 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.981 ms/op
                 createUser·p0.999:  8.634 ms/op
                 createUser·p0.9999: 14.120 ms/op
                 createUser·p1.00:   14.320 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379047
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 183468 
    [ 2.500,  3.750) = 191780 
    [ 3.750,  5.000) = 2925 
    [ 5.000,  6.250) = 318 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 102 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      8.666 ms/op
     p(99.9900) =     13.866 ms/op
     p(99.9990) =     14.402 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.976 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  10.230 ms/op
                 existUser·p0.9999: 13.435 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.041 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.715 ms/op
                 existUser·p0.999:  6.041 ms/op
                 existUser·p0.9999: 12.272 ms/op
                 existUser·p1.00:   12.698 ms/op

Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.475 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  9.067 ms/op
                 existUser·p0.9999: 19.792 ms/op
                 existUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384342
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 188307 
    [ 2.500,  5.000) = 195248 
    [ 5.000,  7.500) = 434 
    [ 7.500, 10.000) = 73 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.475 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.633 ms/op
     p(99.9000) =      6.250 ms/op
     p(99.9900) =     13.615 ms/op
     p(99.9990) =     19.999 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.005 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.006 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.674 ms/op
                 getUser·p0.999:  9.196 ms/op
                 getUser·p0.9999: 13.716 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.946 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.994 ms/op
                 getUser·p0.999:  9.003 ms/op
                 getUser·p0.9999: 14.029 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  8.560 ms/op
                 getUser·p0.9999: 10.965 ms/op
                 getUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383504
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 189390 
    [ 2.500,  3.750) = 190008 
    [ 3.750,  5.000) = 3166 
    [ 5.000,  6.250) = 474 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 122 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     13.505 ms/op
     p(99.9990) =     14.290 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.748 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.008 ms/op
Iteration   1: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  8.847 ms/op
                 listUser·p0.9999: 10.448 ms/op
                 listUser·p1.00:   12.861 ms/op

Iteration   2: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.847 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  10.142 ms/op
                 listUser·p0.9999: 11.518 ms/op
                 listUser·p1.00:   11.665 ms/op

Iteration   3: 3.047 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.940 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 11.461 ms/op
                 listUser·p1.00:   13.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317339
  mean =      3.022 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 89341 
    [ 2.500,  3.750) = 187901 
    [ 3.750,  5.000) = 32672 
    [ 5.000,  6.250) = 5919 
    [ 6.250,  7.500) = 731 
    [ 7.500,  8.750) = 204 
    [ 8.750, 10.000) = 224 
    [10.000, 11.250) = 171 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.366 ms/op
     p(99.9900) =     11.436 ms/op
     p(99.9990) =     12.553 ms/op
     p(99.9999) =     13.468 ms/op
    p(100.0000) =     13.468 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.412 ± 1.831  ops/ms
ClientPb.existUser                       thrpt       3  13.031 ± 1.094  ops/ms
ClientPb.getUser                         thrpt       3  12.828 ± 2.252  ops/ms
ClientPb.listUser                        thrpt       3  10.493 ± 0.737  ops/ms
ClientPb.createUser                       avgt       3   2.578 ± 0.309   ms/op
ClientPb.existUser                        avgt       3   2.488 ± 0.176   ms/op
ClientPb.getUser                          avgt       3   2.562 ± 0.214   ms/op
ClientPb.listUser                         avgt       3   3.021 ± 0.219   ms/op
ClientPb.createUser                     sample  379047   2.530 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.906           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.666           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.866           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.909           ms/op
ClientPb.existUser                      sample  384342   2.496 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.475           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.250           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.615           ms/op
ClientPb.existUser:existUser·p1.00      sample          20.939           ms/op
ClientPb.getUser                        sample  383504   2.501 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.881           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.569           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.505           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.320           ms/op
ClientPb.listUser                       sample  317339   3.022 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.847           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.366           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.436           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.468           ms/op
