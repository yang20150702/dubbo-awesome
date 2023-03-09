# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.551 ops/ms
# Warmup Iteration   2: 6.314 ops/ms
# Warmup Iteration   3: 9.247 ops/ms
Iteration   1: 10.099 ops/ms
Iteration   2: 10.026 ops/ms
Iteration   3: 9.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.961 ±(99.9%) 3.272 ops/ms [Average]
  (min, avg, max) = (9.758, 9.961, 10.099), stdev = 0.179
  CI (99.9%): [6.689, 13.233] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.521 ops/ms
# Warmup Iteration   2: 8.927 ops/ms
# Warmup Iteration   3: 10.048 ops/ms
Iteration   1: 10.261 ops/ms
Iteration   2: 9.917 ops/ms
Iteration   3: 10.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.213 ±(99.9%) 5.017 ops/ms [Average]
  (min, avg, max) = (9.917, 10.213, 10.461), stdev = 0.275
  CI (99.9%): [5.195, 15.230] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.382 ops/ms
# Warmup Iteration   2: 9.001 ops/ms
# Warmup Iteration   3: 9.615 ops/ms
Iteration   1: 10.321 ops/ms
Iteration   2: 10.120 ops/ms
Iteration   3: 9.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.144 ±(99.9%) 3.037 ops/ms [Average]
  (min, avg, max) = (9.991, 10.144, 10.321), stdev = 0.166
  CI (99.9%): [7.107, 13.181] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.215 ops/ms
# Warmup Iteration   2: 7.542 ops/ms
# Warmup Iteration   3: 8.529 ops/ms
Iteration   1: 8.510 ops/ms
Iteration   2: 8.828 ops/ms
Iteration   3: 8.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.739 ±(99.9%) 3.651 ops/ms [Average]
  (min, avg, max) = (8.510, 8.739, 8.879), stdev = 0.200
  CI (99.9%): [5.089, 12.390] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.609 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.515 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.249 ±(99.9%) 0.003 ms/op
Iteration   1: 3.197 ±(99.9%) 0.004 ms/op
Iteration   2: 3.202 ±(99.9%) 0.005 ms/op
Iteration   3: 3.227 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.208 ±(99.9%) 0.300 ms/op [Average]
  (min, avg, max) = (3.197, 3.208, 3.227), stdev = 0.016
  CI (99.9%): [2.908, 3.509] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.658 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.285 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.005 ms/op
Iteration   1: 3.079 ±(99.9%) 0.006 ms/op
Iteration   2: 2.961 ±(99.9%) 0.006 ms/op
Iteration   3: 3.057 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.033 ±(99.9%) 1.141 ms/op [Average]
  (min, avg, max) = (2.961, 3.033, 3.079), stdev = 0.063
  CI (99.9%): [1.892, 4.173] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.520 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.482 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.004 ms/op
Iteration   1: 3.159 ±(99.9%) 0.007 ms/op
Iteration   2: 3.141 ±(99.9%) 0.003 ms/op
Iteration   3: 3.222 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.174 ±(99.9%) 0.782 ms/op [Average]
  (min, avg, max) = (3.141, 3.174, 3.222), stdev = 0.043
  CI (99.9%): [2.393, 3.956] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.118 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.006 ms/op
Iteration   1: 3.704 ±(99.9%) 0.006 ms/op
Iteration   2: 3.771 ±(99.9%) 0.004 ms/op
Iteration   3: 3.602 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.692 ±(99.9%) 1.545 ms/op [Average]
  (min, avg, max) = (3.602, 3.692, 3.771), stdev = 0.085
  CI (99.9%): [2.147, 5.237] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.877 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.855 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.293 ±(99.9%) 0.009 ms/op
Iteration   1: 3.096 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.314 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  18.106 ms/op
                 createUser·p0.9999: 21.056 ms/op
                 createUser·p1.00:   22.675 ms/op

Iteration   2: 3.154 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.151 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  10.207 ms/op
                 createUser·p0.9999: 21.234 ms/op
                 createUser·p1.00:   22.610 ms/op

Iteration   3: 3.261 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  13.735 ms/op
                 createUser·p0.9999: 22.217 ms/op
                 createUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302724
  mean =      3.169 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18985 
    [ 2.500,  5.000) = 278251 
    [ 5.000,  7.500) = 4539 
    [ 7.500, 10.000) = 607 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     15.288 ms/op
     p(99.9900) =     21.299 ms/op
     p(99.9990) =     22.674 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.066 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.324 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.007 ms/op
Iteration   1: 3.047 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  7.934 ms/op
                 existUser·p0.9999: 22.021 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   2: 3.119 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.325 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  12.108 ms/op
                 existUser·p0.9999: 22.388 ms/op
                 existUser·p1.00:   23.527 ms/op

Iteration   3: 3.030 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.534 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   5.770 ms/op
                 existUser·p0.999:  14.640 ms/op
                 existUser·p0.9999: 21.463 ms/op
                 existUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312889
  mean =      3.065 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14128 
    [ 2.500,  5.000) = 293006 
    [ 5.000,  7.500) = 4843 
    [ 7.500, 10.000) = 438 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     12.419 ms/op
     p(99.9900) =     21.912 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.097 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.008 ms/op
Iteration   1: 3.345 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  17.544 ms/op
                 getUser·p0.9999: 23.327 ms/op
                 getUser·p1.00:   23.986 ms/op

Iteration   2: 3.246 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  11.158 ms/op
                 getUser·p0.9999: 28.058 ms/op
                 getUser·p1.00:   29.032 ms/op

Iteration   3: 3.112 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  9.034 ms/op
                 getUser·p0.9999: 25.621 ms/op
                 getUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297024
  mean =      3.231 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9213 
    [ 2.500,  5.000) = 281253 
    [ 5.000,  7.500) = 5718 
    [ 7.500, 10.000) = 426 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     26.637 ms/op
     p(99.9990) =     28.715 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.959 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.772 ±(99.9%) 0.011 ms/op
Iteration   1: 3.726 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.810 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.406 ms/op
                 listUser·p0.999:  14.567 ms/op
                 listUser·p0.9999: 21.405 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   2: 3.780 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  13.390 ms/op
                 listUser·p0.9999: 19.333 ms/op
                 listUser·p1.00:   19.562 ms/op

Iteration   3: 3.789 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.507 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.919 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 17.957 ms/op
                 listUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255083
  mean =      3.765 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 247205 
    [ 5.000,  7.500) = 6103 
    [ 7.500, 10.000) = 1120 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.507 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     14.417 ms/op
     p(99.9900) =     19.333 ms/op
     p(99.9990) =     21.787 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.961 ± 3.272  ops/ms
ClientPb.existUser                       thrpt       3  10.213 ± 5.017  ops/ms
ClientPb.getUser                         thrpt       3  10.144 ± 3.037  ops/ms
ClientPb.listUser                        thrpt       3   8.739 ± 3.651  ops/ms
ClientPb.createUser                       avgt       3   3.208 ± 0.300   ms/op
ClientPb.existUser                        avgt       3   3.033 ± 1.141   ms/op
ClientPb.getUser                          avgt       3   3.174 ± 0.782   ms/op
ClientPb.listUser                         avgt       3   3.692 ± 1.545   ms/op
ClientPb.createUser                     sample  302724   3.169 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.151           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.527           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.464           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.288           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.299           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.938           ms/op
ClientPb.existUser                      sample  312889   3.065 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.059           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.342           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.538           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.419           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.912           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.527           ms/op
ClientPb.getUser                        sample  297024   3.231 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.862           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.768           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.141           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.759           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.433           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.637           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.917           ms/op
ClientPb.listUser                       sample  255083   3.765 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.507           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.116           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.636           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.417           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.333           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.889           ms/op
