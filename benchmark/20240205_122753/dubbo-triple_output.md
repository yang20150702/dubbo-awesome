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
# Warmup Iteration   1: 4.532 ops/ms
# Warmup Iteration   2: 11.783 ops/ms
# Warmup Iteration   3: 12.055 ops/ms
Iteration   1: 12.380 ops/ms
Iteration   2: 12.379 ops/ms
Iteration   3: 12.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.418 ±(99.9%) 1.244 ops/ms [Average]
  (min, avg, max) = (12.379, 12.418, 12.497), stdev = 0.068
  CI (99.9%): [11.174, 13.663] (assumes normal distribution)


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
# Warmup Iteration   1: 8.043 ops/ms
# Warmup Iteration   2: 12.772 ops/ms
# Warmup Iteration   3: 12.868 ops/ms
Iteration   1: 13.028 ops/ms
Iteration   2: 13.002 ops/ms
Iteration   3: 12.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.994 ±(99.9%) 0.706 ops/ms [Average]
  (min, avg, max) = (12.952, 12.994, 13.028), stdev = 0.039
  CI (99.9%): [12.288, 13.700] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.534 ops/ms
# Warmup Iteration   2: 12.336 ops/ms
# Warmup Iteration   3: 12.662 ops/ms
Iteration   1: 12.702 ops/ms
Iteration   2: 12.674 ops/ms
Iteration   3: 12.485 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.620 ±(99.9%) 2.148 ops/ms [Average]
  (min, avg, max) = (12.485, 12.620, 12.702), stdev = 0.118
  CI (99.9%): [10.472, 14.769] (assumes normal distribution)


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
# Warmup Iteration   1: 6.392 ops/ms
# Warmup Iteration   2: 10.300 ops/ms
# Warmup Iteration   3: 10.410 ops/ms
Iteration   1: 10.480 ops/ms
Iteration   2: 10.519 ops/ms
Iteration   3: 10.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.517 ±(99.9%) 0.660 ops/ms [Average]
  (min, avg, max) = (10.480, 10.517, 10.552), stdev = 0.036
  CI (99.9%): [9.858, 11.177] (assumes normal distribution)


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
# Warmup Iteration   1: 4.026 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.563 ±(99.9%) 0.003 ms/op
Iteration   1: 2.543 ±(99.9%) 0.004 ms/op
Iteration   2: 2.538 ±(99.9%) 0.004 ms/op
Iteration   3: 2.580 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.554 ±(99.9%) 0.421 ms/op [Average]
  (min, avg, max) = (2.538, 2.554, 2.580), stdev = 0.023
  CI (99.9%): [2.133, 2.975] (assumes normal distribution)


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
# Warmup Iteration   1: 3.833 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.004 ms/op
Iteration   1: 2.476 ±(99.9%) 0.004 ms/op
Iteration   2: 2.461 ±(99.9%) 0.003 ms/op
Iteration   3: 2.499 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.478 ±(99.9%) 0.347 ms/op [Average]
  (min, avg, max) = (2.461, 2.478, 2.499), stdev = 0.019
  CI (99.9%): [2.132, 2.825] (assumes normal distribution)


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
# Warmup Iteration   1: 3.760 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.003 ms/op
Iteration   1: 2.539 ±(99.9%) 0.004 ms/op
Iteration   2: 2.504 ±(99.9%) 0.004 ms/op
Iteration   3: 2.526 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.523 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (2.504, 2.523, 2.539), stdev = 0.018
  CI (99.9%): [2.201, 2.845] (assumes normal distribution)


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
# Warmup Iteration   1: 4.559 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.005 ms/op
Iteration   1: 3.020 ±(99.9%) 0.005 ms/op
Iteration   2: 3.034 ±(99.9%) 0.006 ms/op
Iteration   3: 2.993 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.016 ±(99.9%) 0.384 ms/op [Average]
  (min, avg, max) = (2.993, 3.016, 3.034), stdev = 0.021
  CI (99.9%): [2.632, 3.400] (assumes normal distribution)


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
# Warmup Iteration   1: 4.271 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.759 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.615 ±(99.9%) 0.006 ms/op
Iteration   1: 2.601 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.846 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.174 ms/op
                 createUser·p0.95:   3.310 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  11.993 ms/op
                 createUser·p0.9999: 14.069 ms/op
                 createUser·p1.00:   14.385 ms/op

Iteration   2: 2.571 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.128 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  9.067 ms/op
                 createUser·p0.9999: 13.386 ms/op
                 createUser·p1.00:   14.139 ms/op

Iteration   3: 2.597 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   3.903 ms/op
                 createUser·p0.999:  8.697 ms/op
                 createUser·p0.9999: 10.875 ms/op
                 createUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 370368
  mean =      2.590 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 175407 
    [ 2.500,  3.750) = 190691 
    [ 3.750,  5.000) = 3472 
    [ 5.000,  6.250) = 328 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      2.646 ms/op
     p(90.0000) =      3.154 ms/op
     p(95.0000) =      3.273 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      8.782 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     14.316 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 3.798 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  6.237 ms/op
                 existUser·p0.9999: 12.911 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   2: 2.489 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.982 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  6.250 ms/op
                 existUser·p0.9999: 22.451 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  6.023 ms/op
                 existUser·p0.9999: 11.764 ms/op
                 existUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386063
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 189410 
    [ 2.500,  5.000) = 195987 
    [ 5.000,  7.500) = 345 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      6.168 ms/op
     p(99.9900) =     14.025 ms/op
     p(99.9990) =     22.549 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 3.890 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.006 ms/op
Iteration   1: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.035 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  5.751 ms/op
                 getUser·p0.9999: 13.835 ms/op
                 getUser·p1.00:   14.696 ms/op

Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.038 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.944 ms/op
                 getUser·p0.999:  9.537 ms/op
                 getUser·p0.9999: 13.909 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.996 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.920 ms/op
                 getUser·p0.999:  8.607 ms/op
                 getUser·p0.9999: 12.565 ms/op
                 getUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381298
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 187226 
    [ 2.500,  3.750) = 189612 
    [ 3.750,  5.000) = 3476 
    [ 5.000,  6.250) = 542 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.996 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      6.341 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     14.561 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 4.588 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.009 ms/op
Iteration   1: 3.074 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.928 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 11.059 ms/op
                 listUser·p1.00:   12.911 ms/op

Iteration   2: 3.044 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.855 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.798 ms/op
                 listUser·p0.9999: 12.370 ms/op
                 listUser·p1.00:   13.091 ms/op

Iteration   3: 3.064 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.861 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.077 ms/op
                 listUser·p0.9999: 11.183 ms/op
                 listUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313382
  mean =      3.061 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 122 
    [ 1.250,  2.500) = 82732 
    [ 2.500,  3.750) = 187699 
    [ 3.750,  5.000) = 35101 
    [ 5.000,  6.250) = 6510 
    [ 6.250,  7.500) = 586 
    [ 7.500,  8.750) = 190 
    [ 8.750, 10.000) = 252 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     12.086 ms/op
     p(99.9990) =     12.841 ms/op
     p(99.9999) =     13.091 ms/op
    p(100.0000) =     13.091 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.418 ± 1.244  ops/ms
ClientPb.existUser                       thrpt       3  12.994 ± 0.706  ops/ms
ClientPb.getUser                         thrpt       3  12.620 ± 2.148  ops/ms
ClientPb.listUser                        thrpt       3  10.517 ± 0.660  ops/ms
ClientPb.createUser                       avgt       3   2.554 ± 0.421   ms/op
ClientPb.existUser                        avgt       3   2.478 ± 0.347   ms/op
ClientPb.getUser                          avgt       3   2.523 ± 0.322   ms/op
ClientPb.listUser                         avgt       3   3.016 ± 0.384   ms/op
ClientPb.createUser                     sample  370368   2.590 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.846           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.646           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.782           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.500           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.385           ms/op
ClientPb.existUser                      sample  386063   2.485 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.793           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.168           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.025           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.708           ms/op
ClientPb.getUser                        sample  381298   2.515 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.996           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.341           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.763           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.696           ms/op
ClientPb.listUser                       sample  313382   3.061 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.855           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.388           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.086           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.091           ms/op
