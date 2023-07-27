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
# Warmup Iteration   1: 1.700 ops/ms
# Warmup Iteration   2: 3.136 ops/ms
# Warmup Iteration   3: 6.504 ops/ms
Iteration   1: 7.436 ops/ms
Iteration   2: 7.865 ops/ms
Iteration   3: 8.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.779 ±(99.9%) 5.656 ops/ms [Average]
  (min, avg, max) = (7.436, 7.779, 8.038), stdev = 0.310
  CI (99.9%): [2.123, 13.436] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.128 ops/ms
# Warmup Iteration   2: 7.068 ops/ms
# Warmup Iteration   3: 8.102 ops/ms
Iteration   1: 8.333 ops/ms
Iteration   2: 8.409 ops/ms
Iteration   3: 8.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.434 ±(99.9%) 2.097 ops/ms [Average]
  (min, avg, max) = (8.333, 8.434, 8.559), stdev = 0.115
  CI (99.9%): [6.337, 10.531] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.264 ops/ms
# Warmup Iteration   2: 6.416 ops/ms
# Warmup Iteration   3: 7.324 ops/ms
Iteration   1: 7.823 ops/ms
Iteration   2: 7.902 ops/ms
Iteration   3: 8.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.917 ±(99.9%) 1.858 ops/ms [Average]
  (min, avg, max) = (7.823, 7.917, 8.025), stdev = 0.102
  CI (99.9%): [6.059, 9.775] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.025 ops/ms
# Warmup Iteration   2: 5.647 ops/ms
# Warmup Iteration   3: 6.360 ops/ms
Iteration   1: 6.545 ops/ms
Iteration   2: 6.748 ops/ms
Iteration   3: 6.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.607 ±(99.9%) 2.234 ops/ms [Average]
  (min, avg, max) = (6.528, 6.607, 6.748), stdev = 0.122
  CI (99.9%): [4.373, 8.841] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 13.930 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.689 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.340 ±(99.9%) 0.005 ms/op
Iteration   1: 3.928 ±(99.9%) 0.013 ms/op
Iteration   2: 3.962 ±(99.9%) 0.015 ms/op
Iteration   3: 4.043 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.978 ±(99.9%) 1.072 ms/op [Average]
  (min, avg, max) = (3.928, 3.978, 4.043), stdev = 0.059
  CI (99.9%): [2.905, 5.050] (assumes normal distribution)


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
# Warmup Iteration   1: 12.276 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.815 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.004 ms/op
Iteration   1: 3.847 ±(99.9%) 0.010 ms/op
Iteration   2: 4.007 ±(99.9%) 0.006 ms/op
Iteration   3: 3.885 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.913 ±(99.9%) 1.518 ms/op [Average]
  (min, avg, max) = (3.847, 3.913, 4.007), stdev = 0.083
  CI (99.9%): [2.396, 5.431] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.633 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.169 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.267 ±(99.9%) 0.006 ms/op
Iteration   1: 4.355 ±(99.9%) 0.005 ms/op
Iteration   2: 4.223 ±(99.9%) 0.008 ms/op
Iteration   3: 4.057 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.211 ±(99.9%) 2.724 ms/op [Average]
  (min, avg, max) = (4.057, 4.211, 4.355), stdev = 0.149
  CI (99.9%): [1.487, 6.936] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.326 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.241 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.895 ±(99.9%) 0.009 ms/op
Iteration   1: 4.730 ±(99.9%) 0.009 ms/op
Iteration   2: 4.610 ±(99.9%) 0.013 ms/op
Iteration   3: 4.534 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.625 ±(99.9%) 1.803 ms/op [Average]
  (min, avg, max) = (4.534, 4.625, 4.730), stdev = 0.099
  CI (99.9%): [2.822, 6.427] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.226 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 5.486 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.397 ±(99.9%) 0.018 ms/op
Iteration   1: 3.985 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.782 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   5.243 ms/op
                 createUser·p0.99:   7.856 ms/op
                 createUser·p0.999:  24.059 ms/op
                 createUser·p0.9999: 29.360 ms/op
                 createUser·p1.00:   31.785 ms/op

Iteration   2: 4.029 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.808 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   6.693 ms/op
                 createUser·p0.999:  12.190 ms/op
                 createUser·p0.9999: 30.771 ms/op
                 createUser·p1.00:   32.113 ms/op

Iteration   3: 4.013 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.808 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   6.923 ms/op
                 createUser·p0.999:  29.393 ms/op
                 createUser·p0.9999: 34.474 ms/op
                 createUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239274
  mean =      4.009 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 589 
    [ 2.500,  5.000) = 224512 
    [ 5.000,  7.500) = 12055 
    [ 7.500, 10.000) = 1502 
    [10.000, 12.500) = 300 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 48 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.782 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     24.180 ms/op
     p(99.9900) =     34.079 ms/op
     p(99.9990) =     35.036 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.436 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.377 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.011 ms/op
Iteration   1: 3.964 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.481 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   4.989 ms/op
                 existUser·p0.99:   7.740 ms/op
                 existUser·p0.999:  22.643 ms/op
                 existUser·p0.9999: 30.212 ms/op
                 existUser·p1.00:   31.457 ms/op

Iteration   2: 3.920 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.377 ms/op
                 existUser·p0.50:   3.854 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   6.783 ms/op
                 existUser·p0.999:  11.194 ms/op
                 existUser·p0.9999: 32.402 ms/op
                 existUser·p1.00:   33.817 ms/op

Iteration   3: 3.975 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.905 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.202 ms/op
                 existUser·p0.99:   6.816 ms/op
                 existUser·p0.999:  11.815 ms/op
                 existUser·p0.9999: 30.994 ms/op
                 existUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 242750
  mean =      3.953 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 316 
    [ 2.500,  5.000) = 229924 
    [ 5.000,  7.500) = 10688 
    [ 7.500, 10.000) = 1365 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 69 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.377 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     12.304 ms/op
     p(99.9900) =     31.850 ms/op
     p(99.9990) =     32.801 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.842 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 4.841 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.050 ±(99.9%) 0.012 ms/op
Iteration   1: 4.210 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.595 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   4.817 ms/op
                 getUser·p0.95:   6.169 ms/op
                 getUser·p0.99:   9.142 ms/op
                 getUser·p0.999:  23.331 ms/op
                 getUser·p0.9999: 31.529 ms/op
                 getUser·p1.00:   32.997 ms/op

Iteration   2: 4.095 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.300 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   6.489 ms/op
                 getUser·p0.999:  11.463 ms/op
                 getUser·p0.9999: 26.385 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   3: 3.948 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.733 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   6.660 ms/op
                 getUser·p0.999:  24.314 ms/op
                 getUser·p0.9999: 29.520 ms/op
                 getUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235132
  mean =      4.081 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 221394 
    [ 5.000,  7.500) = 10996 
    [ 7.500, 10.000) = 1687 
    [10.000, 12.500) = 557 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      7.698 ms/op
     p(99.9000) =     23.305 ms/op
     p(99.9900) =     29.949 ms/op
     p(99.9990) =     32.030 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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
# Warmup Iteration   1: 15.064 ±(99.9%) 0.235 ms/op
# Warmup Iteration   2: 5.644 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.849 ±(99.9%) 0.017 ms/op
Iteration   1: 4.794 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.507 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  24.478 ms/op
                 listUser·p0.9999: 26.618 ms/op
                 listUser·p1.00:   27.263 ms/op

Iteration   2: 4.586 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.748 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   8.552 ms/op
                 listUser·p0.999:  17.145 ms/op
                 listUser·p0.9999: 22.808 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   3: 4.786 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.601 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.826 ms/op
                 listUser·p0.99:   8.868 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 21.091 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203332
  mean =      4.720 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 176490 
    [ 5.000,  7.500) = 22381 
    [ 7.500, 10.000) = 3078 
    [10.000, 12.500) = 813 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.507 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     20.840 ms/op
     p(99.9900) =     26.051 ms/op
     p(99.9990) =     27.055 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.779 ± 5.656  ops/ms
ClientPb.existUser                       thrpt       3   8.434 ± 2.097  ops/ms
ClientPb.getUser                         thrpt       3   7.917 ± 1.858  ops/ms
ClientPb.listUser                        thrpt       3   6.607 ± 2.234  ops/ms
ClientPb.createUser                       avgt       3   3.978 ± 1.072   ms/op
ClientPb.existUser                        avgt       3   3.913 ± 1.518   ms/op
ClientPb.getUser                          avgt       3   4.211 ± 2.724   ms/op
ClientPb.listUser                         avgt       3   4.625 ± 1.803   ms/op
ClientPb.createUser                     sample  239274   4.009 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.782           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.669           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.128           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.225           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.180           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.079           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.979           ms/op
ClientPb.existUser                      sample  242750   3.953 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.377           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.530           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.030           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.070           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.304           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.850           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.817           ms/op
ClientPb.getUser                        sample  235132   4.081 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.300           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.661           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.145           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.698           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.305           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.949           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.997           ms/op
ClientPb.listUser                       sample  203332   4.720 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.507           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.104           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.175           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.840           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.051           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.263           ms/op
