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
# Warmup Iteration   1: 4.888 ops/ms
# Warmup Iteration   2: 12.708 ops/ms
# Warmup Iteration   3: 12.763 ops/ms
Iteration   1: 12.904 ops/ms
Iteration   2: 13.215 ops/ms
Iteration   3: 13.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.080 ±(99.9%) 2.920 ops/ms [Average]
  (min, avg, max) = (12.904, 13.080, 13.215), stdev = 0.160
  CI (99.9%): [10.160, 16.001] (assumes normal distribution)


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
# Warmup Iteration   1: 8.189 ops/ms
# Warmup Iteration   2: 13.403 ops/ms
# Warmup Iteration   3: 13.318 ops/ms
Iteration   1: 13.562 ops/ms
Iteration   2: 13.632 ops/ms
Iteration   3: 13.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.551 ±(99.9%) 1.592 ops/ms [Average]
  (min, avg, max) = (13.459, 13.551, 13.632), stdev = 0.087
  CI (99.9%): [11.959, 15.143] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.879 ops/ms
# Warmup Iteration   2: 12.817 ops/ms
# Warmup Iteration   3: 13.046 ops/ms
Iteration   1: 13.261 ops/ms
Iteration   2: 13.271 ops/ms
Iteration   3: 13.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.258 ±(99.9%) 0.251 ops/ms [Average]
  (min, avg, max) = (13.243, 13.258, 13.271), stdev = 0.014
  CI (99.9%): [13.007, 13.510] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.010 ops/ms
# Warmup Iteration   2: 10.725 ops/ms
# Warmup Iteration   3: 10.908 ops/ms
Iteration   1: 10.996 ops/ms
Iteration   2: 10.981 ops/ms
Iteration   3: 10.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.965 ±(99.9%) 0.763 ops/ms [Average]
  (min, avg, max) = (10.917, 10.965, 10.996), stdev = 0.042
  CI (99.9%): [10.202, 11.727] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.772 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.004 ms/op
Iteration   1: 2.468 ±(99.9%) 0.006 ms/op
Iteration   2: 2.461 ±(99.9%) 0.004 ms/op
Iteration   3: 2.440 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.456 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (2.440, 2.456, 2.468), stdev = 0.014
  CI (99.9%): [2.194, 2.718] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.504 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.387 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.353 ±(99.9%) 0.005 ms/op
Iteration   1: 2.404 ±(99.9%) 0.004 ms/op
Iteration   2: 2.359 ±(99.9%) 0.004 ms/op
Iteration   3: 2.358 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.374 ±(99.9%) 0.476 ms/op [Average]
  (min, avg, max) = (2.358, 2.374, 2.404), stdev = 0.026
  CI (99.9%): [1.898, 2.849] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.625 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.004 ms/op
Iteration   1: 2.444 ±(99.9%) 0.004 ms/op
Iteration   2: 2.432 ±(99.9%) 0.004 ms/op
Iteration   3: 2.401 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.426 ±(99.9%) 0.404 ms/op [Average]
  (min, avg, max) = (2.401, 2.426, 2.444), stdev = 0.022
  CI (99.9%): [2.022, 2.830] (assumes normal distribution)


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
# Warmup Iteration   1: 4.502 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.991 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.926 ±(99.9%) 0.004 ms/op
Iteration   1: 2.922 ±(99.9%) 0.004 ms/op
Iteration   2: 2.904 ±(99.9%) 0.005 ms/op
Iteration   3: 2.933 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.920 ±(99.9%) 0.267 ms/op [Average]
  (min, avg, max) = (2.904, 2.920, 2.933), stdev = 0.015
  CI (99.9%): [2.652, 3.187] (assumes normal distribution)


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.880 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   3.609 ms/op
                 createUser·p0.999:  10.871 ms/op
                 createUser·p0.9999: 14.568 ms/op
                 createUser·p1.00:   15.679 ms/op

Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.572 ms/op
                 createUser·p0.999:  6.429 ms/op
                 createUser·p0.9999: 11.698 ms/op
                 createUser·p1.00:   12.632 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   4.055 ms/op
                 createUser·p0.999:  8.532 ms/op
                 createUser·p0.9999: 10.666 ms/op
                 createUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387414
  mean =      2.475 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 189510 
    [ 2.500,  3.750) = 194052 
    [ 3.750,  5.000) = 2785 
    [ 5.000,  6.250) = 524 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 120 
    [10.000, 11.250) = 163 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      9.404 ms/op
     p(99.9900) =     13.013 ms/op
     p(99.9990) =     15.090 ms/op
     p(99.9999) =     15.679 ms/op
    p(100.0000) =     15.679 ms/op


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
# Warmup Iteration   1: 3.664 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.395 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.411 ±(99.9%) 0.005 ms/op
Iteration   1: 2.387 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.415 ms/op
                 existUser·p0.999:  4.976 ms/op
                 existUser·p0.9999: 13.337 ms/op
                 existUser·p1.00:   13.500 ms/op

Iteration   2: 2.382 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.967 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.879 ms/op
                 existUser·p0.95:   2.978 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  8.009 ms/op
                 existUser·p0.9999: 14.987 ms/op
                 existUser·p1.00:   15.876 ms/op

Iteration   3: 2.402 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  9.355 ms/op
                 existUser·p0.9999: 12.247 ms/op
                 existUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 401165
  mean =      2.391 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 205596 
    [ 2.500,  3.750) = 192635 
    [ 3.750,  5.000) = 2107 
    [ 5.000,  6.250) = 291 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      2.904 ms/op
     p(95.0000) =      3.011 ms/op
     p(99.0000) =      3.543 ms/op
     p(99.9000) =      7.969 ms/op
     p(99.9900) =     13.369 ms/op
     p(99.9990) =     15.695 ms/op
     p(99.9999) =     15.876 ms/op
    p(100.0000) =     15.876 ms/op


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
# Warmup Iteration   1: 3.794 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.006 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.772 ms/op
                 getUser·p0.999:  7.598 ms/op
                 getUser·p0.9999: 14.221 ms/op
                 getUser·p1.00:   15.122 ms/op

Iteration   2: 2.472 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  9.138 ms/op
                 getUser·p0.9999: 16.473 ms/op
                 getUser·p1.00:   17.367 ms/op

Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.633 ms/op
                 getUser·p0.999:  6.341 ms/op
                 getUser·p0.9999: 10.876 ms/op
                 getUser·p1.00:   11.158 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389987
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 196289 
    [ 2.500,  3.750) = 189084 
    [ 3.750,  5.000) = 3515 
    [ 5.000,  6.250) = 548 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 82 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      8.331 ms/op
     p(99.9900) =     14.287 ms/op
     p(99.9990) =     16.918 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 4.727 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.009 ms/op
Iteration   1: 2.982 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.810 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  9.060 ms/op
                 listUser·p0.9999: 13.926 ms/op
                 listUser·p1.00:   15.155 ms/op

Iteration   2: 2.956 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.798 ms/op
                 listUser·p0.9999: 11.143 ms/op
                 listUser·p1.00:   11.911 ms/op

Iteration   3: 2.947 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.690 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.366 ms/op
                 listUser·p0.999:  9.929 ms/op
                 listUser·p0.9999: 12.219 ms/op
                 listUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323844
  mean =      2.962 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 175 
    [ 1.250,  2.500) = 102097 
    [ 2.500,  3.750) = 184553 
    [ 3.750,  5.000) = 29929 
    [ 5.000,  6.250) = 5766 
    [ 6.250,  7.500) = 673 
    [ 7.500,  8.750) = 168 
    [ 8.750, 10.000) = 250 
    [10.000, 11.250) = 137 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     12.580 ms/op
     p(99.9990) =     14.082 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.080 ± 2.920  ops/ms
ClientPb.existUser                       thrpt       3  13.551 ± 1.592  ops/ms
ClientPb.getUser                         thrpt       3  13.258 ± 0.251  ops/ms
ClientPb.listUser                        thrpt       3  10.965 ± 0.763  ops/ms
ClientPb.createUser                       avgt       3   2.456 ± 0.262   ms/op
ClientPb.existUser                        avgt       3   2.374 ± 0.476   ms/op
ClientPb.getUser                          avgt       3   2.426 ± 0.404   ms/op
ClientPb.listUser                         avgt       3   2.920 ± 0.267   ms/op
ClientPb.createUser                     sample  387414   2.475 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.786           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.404           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.013           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.679           ms/op
ClientPb.existUser                      sample  401165   2.391 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.666           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.462           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.904           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.969           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.369           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.876           ms/op
ClientPb.getUser                        sample  389987   2.459 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.684           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.331           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.287           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.367           ms/op
ClientPb.listUser                       sample  323844   2.962 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.690           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.568           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.580           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.155           ms/op
