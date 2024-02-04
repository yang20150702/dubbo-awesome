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
# Warmup Iteration   1: 4.438 ops/ms
# Warmup Iteration   2: 11.804 ops/ms
# Warmup Iteration   3: 12.555 ops/ms
Iteration   1: 12.591 ops/ms
Iteration   2: 12.550 ops/ms
Iteration   3: 12.795 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.645 ±(99.9%) 2.392 ops/ms [Average]
  (min, avg, max) = (12.550, 12.645, 12.795), stdev = 0.131
  CI (99.9%): [10.253, 15.037] (assumes normal distribution)


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
# Warmup Iteration   1: 7.910 ops/ms
# Warmup Iteration   2: 13.023 ops/ms
# Warmup Iteration   3: 13.084 ops/ms
Iteration   1: 13.026 ops/ms
Iteration   2: 12.938 ops/ms
Iteration   3: 12.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.937 ±(99.9%) 1.634 ops/ms [Average]
  (min, avg, max) = (12.847, 12.937, 13.026), stdev = 0.090
  CI (99.9%): [11.303, 14.571] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.697 ops/ms
# Warmup Iteration   2: 12.722 ops/ms
# Warmup Iteration   3: 12.852 ops/ms
Iteration   1: 12.875 ops/ms
Iteration   2: 12.777 ops/ms
Iteration   3: 12.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.756 ±(99.9%) 2.369 ops/ms [Average]
  (min, avg, max) = (12.617, 12.756, 12.875), stdev = 0.130
  CI (99.9%): [10.387, 15.125] (assumes normal distribution)


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
# Warmup Iteration   1: 6.532 ops/ms
# Warmup Iteration   2: 10.406 ops/ms
# Warmup Iteration   3: 10.769 ops/ms
Iteration   1: 10.729 ops/ms
Iteration   2: 10.717 ops/ms
Iteration   3: 10.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.709 ±(99.9%) 0.439 ops/ms [Average]
  (min, avg, max) = (10.682, 10.709, 10.729), stdev = 0.024
  CI (99.9%): [10.271, 11.148] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.955 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.596 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.004 ms/op
Iteration   1: 2.534 ±(99.9%) 0.004 ms/op
Iteration   2: 2.518 ±(99.9%) 0.004 ms/op
Iteration   3: 2.500 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.518 ±(99.9%) 0.307 ms/op [Average]
  (min, avg, max) = (2.500, 2.518, 2.534), stdev = 0.017
  CI (99.9%): [2.211, 2.825] (assumes normal distribution)


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
# Warmup Iteration   1: 3.773 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.004 ms/op
Iteration   1: 2.454 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.003 ms/op
Iteration   3: 2.484 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.472 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (2.454, 2.472, 2.484), stdev = 0.016
  CI (99.9%): [2.186, 2.759] (assumes normal distribution)


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
# Warmup Iteration   1: 3.849 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.004 ms/op
Iteration   1: 2.514 ±(99.9%) 0.005 ms/op
Iteration   2: 2.469 ±(99.9%) 0.004 ms/op
Iteration   3: 2.520 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.501 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (2.469, 2.501, 2.520), stdev = 0.028
  CI (99.9%): [1.997, 3.006] (assumes normal distribution)


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
# Warmup Iteration   1: 4.612 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
Iteration   1: 3.031 ±(99.9%) 0.005 ms/op
Iteration   2: 2.998 ±(99.9%) 0.006 ms/op
Iteration   3: 2.974 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.001 ±(99.9%) 0.526 ms/op [Average]
  (min, avg, max) = (2.974, 3.001, 3.031), stdev = 0.029
  CI (99.9%): [2.475, 3.527] (assumes normal distribution)


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
# Warmup Iteration   1: 4.309 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.648 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
Iteration   1: 2.543 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  11.051 ms/op
                 createUser·p0.9999: 13.720 ms/op
                 createUser·p1.00:   14.156 ms/op

Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.821 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.539 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 10.681 ms/op
                 createUser·p1.00:   11.485 ms/op

Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  9.896 ms/op
                 createUser·p0.9999: 14.462 ms/op
                 createUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378543
  mean =      2.534 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 181681 
    [ 2.500,  3.750) = 193178 
    [ 3.750,  5.000) = 2835 
    [ 5.000,  6.250) = 309 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 129 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     14.032 ms/op
     p(99.9990) =     15.340 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 3.600 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
Iteration   1: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.424 ms/op
                 existUser·p0.999:  5.833 ms/op
                 existUser·p0.9999: 13.369 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  7.704 ms/op
                 existUser·p0.9999: 12.917 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.963 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  5.774 ms/op
                 existUser·p0.9999: 11.822 ms/op
                 existUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387983
  mean =      2.471 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 191507 
    [ 2.500,  3.750) = 193930 
    [ 3.750,  5.000) = 1902 
    [ 5.000,  6.250) = 220 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.486 ms/op
     p(99.9000) =      6.300 ms/op
     p(99.9900) =     13.206 ms/op
     p(99.9990) =     13.926 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


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
# Warmup Iteration   1: 4.070 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.587 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.568 ±(99.9%) 0.006 ms/op
Iteration   1: 2.548 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.744 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   3.863 ms/op
                 getUser·p0.999:  12.468 ms/op
                 getUser·p0.9999: 14.252 ms/op
                 getUser·p1.00:   14.795 ms/op

Iteration   2: 2.566 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  9.490 ms/op
                 getUser·p0.9999: 14.002 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  8.719 ms/op
                 getUser·p0.9999: 11.960 ms/op
                 getUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376897
  mean =      2.545 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 183479 
    [ 2.500,  3.750) = 188240 
    [ 3.750,  5.000) = 3944 
    [ 5.000,  6.250) = 767 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 130 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.969 ms/op
     p(99.9000) =      8.876 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     14.651 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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
# Warmup Iteration   1: 4.627 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.009 ms/op
Iteration   1: 3.074 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.830 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   5.808 ms/op
                 listUser·p0.999:  9.519 ms/op
                 listUser·p0.9999: 11.747 ms/op
                 listUser·p1.00:   12.976 ms/op

Iteration   2: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.008 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.781 ms/op
                 listUser·p0.9999: 11.377 ms/op
                 listUser·p1.00:   12.812 ms/op

Iteration   3: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  10.158 ms/op
                 listUser·p0.9999: 13.005 ms/op
                 listUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316078
  mean =      3.034 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 138 
    [ 1.250,  2.500) = 89393 
    [ 2.500,  3.750) = 185430 
    [ 3.750,  5.000) = 33020 
    [ 5.000,  6.250) = 6725 
    [ 6.250,  7.500) = 679 
    [ 7.500,  8.750) = 132 
    [ 8.750, 10.000) = 271 
    [10.000, 11.250) = 168 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.781 ms/op
     p(99.9900) =     12.583 ms/op
     p(99.9990) =     13.447 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.645 ± 2.392  ops/ms
ClientPb.existUser                       thrpt       3  12.937 ± 1.634  ops/ms
ClientPb.getUser                         thrpt       3  12.756 ± 2.369  ops/ms
ClientPb.listUser                        thrpt       3  10.709 ± 0.439  ops/ms
ClientPb.createUser                       avgt       3   2.518 ± 0.307   ms/op
ClientPb.existUser                        avgt       3   2.472 ± 0.286   ms/op
ClientPb.getUser                          avgt       3   2.501 ± 0.504   ms/op
ClientPb.listUser                         avgt       3   3.001 ± 0.526   ms/op
ClientPb.createUser                     sample  378543   2.534 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.821           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.044           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.032           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.792           ms/op
ClientPb.existUser                      sample  387983   2.471 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.673           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.300           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.206           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.976           ms/op
ClientPb.getUser                        sample  376897   2.545 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.744           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.876           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.713           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.795           ms/op
ClientPb.listUser                       sample  316078   3.034 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.830           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.781           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.583           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.057           ms/op
