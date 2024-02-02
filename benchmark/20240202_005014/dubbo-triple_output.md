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
# Warmup Iteration   1: 4.827 ops/ms
# Warmup Iteration   2: 11.954 ops/ms
# Warmup Iteration   3: 12.317 ops/ms
Iteration   1: 12.379 ops/ms
Iteration   2: 12.624 ops/ms
Iteration   3: 12.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.552 ±(99.9%) 2.762 ops/ms [Average]
  (min, avg, max) = (12.379, 12.552, 12.655), stdev = 0.151
  CI (99.9%): [9.791, 15.314] (assumes normal distribution)


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
# Warmup Iteration   1: 8.232 ops/ms
# Warmup Iteration   2: 13.047 ops/ms
# Warmup Iteration   3: 13.252 ops/ms
Iteration   1: 13.170 ops/ms
Iteration   2: 13.138 ops/ms
Iteration   3: 13.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.124 ±(99.9%) 0.988 ops/ms [Average]
  (min, avg, max) = (13.064, 13.124, 13.170), stdev = 0.054
  CI (99.9%): [12.136, 14.112] (assumes normal distribution)


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
# Warmup Iteration   1: 8.190 ops/ms
# Warmup Iteration   2: 12.676 ops/ms
# Warmup Iteration   3: 12.777 ops/ms
Iteration   1: 12.947 ops/ms
Iteration   2: 12.869 ops/ms
Iteration   3: 12.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.900 ±(99.9%) 0.768 ops/ms [Average]
  (min, avg, max) = (12.869, 12.900, 12.947), stdev = 0.042
  CI (99.9%): [12.131, 13.668] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.600 ops/ms
# Warmup Iteration   2: 10.512 ops/ms
# Warmup Iteration   3: 10.548 ops/ms
Iteration   1: 10.577 ops/ms
Iteration   2: 10.563 ops/ms
Iteration   3: 10.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.564 ±(99.9%) 0.218 ops/ms [Average]
  (min, avg, max) = (10.553, 10.564, 10.577), stdev = 0.012
  CI (99.9%): [10.346, 10.783] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.914 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.004 ms/op
Iteration   1: 2.505 ±(99.9%) 0.003 ms/op
Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
Iteration   3: 2.485 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.498 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (2.485, 2.498, 2.506), stdev = 0.012
  CI (99.9%): [2.280, 2.717] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.782 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.004 ms/op
Iteration   1: 2.452 ±(99.9%) 0.004 ms/op
Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
Iteration   3: 2.436 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.444 ±(99.9%) 0.148 ms/op [Average]
  (min, avg, max) = (2.436, 2.444, 2.452), stdev = 0.008
  CI (99.9%): [2.296, 2.592] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.873 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.003 ms/op
Iteration   1: 2.463 ±(99.9%) 0.004 ms/op
Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
Iteration   3: 2.453 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.459 ±(99.9%) 0.097 ms/op [Average]
  (min, avg, max) = (2.453, 2.459, 2.463), stdev = 0.005
  CI (99.9%): [2.362, 2.556] (assumes normal distribution)


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
# Warmup Iteration   1: 4.668 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.006 ms/op
Iteration   1: 2.992 ±(99.9%) 0.006 ms/op
Iteration   2: 2.989 ±(99.9%) 0.005 ms/op
Iteration   3: 3.030 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.004 ±(99.9%) 0.421 ms/op [Average]
  (min, avg, max) = (2.989, 3.004, 3.030), stdev = 0.023
  CI (99.9%): [2.583, 3.425] (assumes normal distribution)


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
# Warmup Iteration   1: 4.235 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
Iteration   1: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.576 ms/op
                 createUser·p0.999:  11.286 ms/op
                 createUser·p0.9999: 13.451 ms/op
                 createUser·p1.00:   14.533 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.570 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.580 ms/op
                 createUser·p0.999:  9.033 ms/op
                 createUser·p0.9999: 12.144 ms/op
                 createUser·p1.00:   15.548 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.983 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  8.733 ms/op
                 createUser·p0.9999: 11.998 ms/op
                 createUser·p1.00:   13.451 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382419
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 185755 
    [ 2.500,  3.750) = 193202 
    [ 3.750,  5.000) = 2532 
    [ 5.000,  6.250) = 380 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 75 
    [ 8.750, 10.000) = 122 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 124 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      8.742 ms/op
     p(99.9900) =     12.989 ms/op
     p(99.9990) =     14.587 ms/op
     p(99.9999) =     15.548 ms/op
    p(100.0000) =     15.548 ms/op


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
# Warmup Iteration   1: 3.724 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.499 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
Iteration   1: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  5.676 ms/op
                 existUser·p0.9999: 13.712 ms/op
                 existUser·p1.00:   14.434 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  6.029 ms/op
                 existUser·p0.9999: 13.697 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.891 ms/op
                 existUser·p0.999:  8.618 ms/op
                 existUser·p0.9999: 11.552 ms/op
                 existUser·p1.00:   11.895 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390303
  mean =      2.457 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 193238 
    [ 2.500,  3.750) = 193520 
    [ 3.750,  5.000) = 2483 
    [ 5.000,  6.250) = 555 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      6.887 ms/op
     p(99.9900) =     13.533 ms/op
     p(99.9990) =     14.172 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


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
# Warmup Iteration   1: 3.865 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.592 ms/op
                 getUser·p0.999:  6.529 ms/op
                 getUser·p0.9999: 13.535 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.025 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  8.869 ms/op
                 getUser·p0.9999: 12.850 ms/op
                 getUser·p1.00:   13.500 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.010 ms/op
                 getUser·p0.999:  9.048 ms/op
                 getUser·p0.9999: 11.636 ms/op
                 getUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383784
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 188015 
    [ 2.500,  3.750) = 190325 
    [ 3.750,  5.000) = 4300 
    [ 5.000,  6.250) = 657 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.998 ms/op
     p(99.9000) =      8.825 ms/op
     p(99.9900) =     13.009 ms/op
     p(99.9990) =     14.322 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 4.631 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.009 ms/op
Iteration   1: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.921 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.110 ms/op
                 listUser·p0.9999: 11.653 ms/op
                 listUser·p1.00:   12.812 ms/op

Iteration   2: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.784 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.346 ms/op
                 listUser·p0.9999: 10.846 ms/op
                 listUser·p1.00:   12.091 ms/op

Iteration   3: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.004 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 10.668 ms/op
                 listUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318268
  mean =      3.013 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 122 
    [ 1.250,  2.500) = 93700 
    [ 2.500,  3.750) = 184033 
    [ 3.750,  5.000) = 32808 
    [ 5.000,  6.250) = 6315 
    [ 6.250,  7.500) = 640 
    [ 7.500,  8.750) = 196 
    [ 8.750, 10.000) = 304 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     11.013 ms/op
     p(99.9990) =     12.738 ms/op
     p(99.9999) =     12.812 ms/op
    p(100.0000) =     12.812 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.552 ± 2.762  ops/ms
ClientPb.existUser                       thrpt       3  13.124 ± 0.988  ops/ms
ClientPb.getUser                         thrpt       3  12.900 ± 0.768  ops/ms
ClientPb.listUser                        thrpt       3  10.564 ± 0.218  ops/ms
ClientPb.createUser                       avgt       3   2.498 ± 0.219   ms/op
ClientPb.existUser                        avgt       3   2.444 ± 0.148   ms/op
ClientPb.getUser                          avgt       3   2.459 ± 0.097   ms/op
ClientPb.listUser                         avgt       3   3.004 ± 0.421   ms/op
ClientPb.createUser                     sample  382419   2.509 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.570           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.742           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.989           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.548           ms/op
ClientPb.existUser                      sample  390303   2.457 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.726           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.887           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.533           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.434           ms/op
ClientPb.getUser                        sample  383784   2.499 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.963           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.825           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.009           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.369           ms/op
ClientPb.listUser                       sample  318268   3.013 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.784           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.013           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.812           ms/op
