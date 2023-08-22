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
# Warmup Iteration   1: 1.565 ops/ms
# Warmup Iteration   2: 3.683 ops/ms
# Warmup Iteration   3: 7.065 ops/ms
Iteration   1: 7.436 ops/ms
Iteration   2: 7.959 ops/ms
Iteration   3: 8.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.849 ±(99.9%) 6.770 ops/ms [Average]
  (min, avg, max) = (7.436, 7.849, 8.153), stdev = 0.371
  CI (99.9%): [1.079, 14.619] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.384 ops/ms
# Warmup Iteration   2: 6.605 ops/ms
# Warmup Iteration   3: 7.782 ops/ms
Iteration   1: 8.101 ops/ms
Iteration   2: 8.416 ops/ms
Iteration   3: 8.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.222 ±(99.9%) 3.103 ops/ms [Average]
  (min, avg, max) = (8.101, 8.222, 8.416), stdev = 0.170
  CI (99.9%): [5.119, 11.325] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.143 ops/ms
# Warmup Iteration   2: 5.782 ops/ms
# Warmup Iteration   3: 7.919 ops/ms
Iteration   1: 7.661 ops/ms
Iteration   2: 7.925 ops/ms
Iteration   3: 7.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.778 ±(99.9%) 2.457 ops/ms [Average]
  (min, avg, max) = (7.661, 7.778, 7.925), stdev = 0.135
  CI (99.9%): [5.321, 10.236] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.112 ops/ms
# Warmup Iteration   2: 5.530 ops/ms
# Warmup Iteration   3: 6.409 ops/ms
Iteration   1: 6.759 ops/ms
Iteration   2: 6.836 ops/ms
Iteration   3: 6.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.739 ±(99.9%) 1.975 ops/ms [Average]
  (min, avg, max) = (6.622, 6.739, 6.836), stdev = 0.108
  CI (99.9%): [4.764, 8.714] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 12.403 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.705 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.297 ±(99.9%) 0.006 ms/op
Iteration   1: 4.020 ±(99.9%) 0.003 ms/op
Iteration   2: 4.120 ±(99.9%) 0.009 ms/op
Iteration   3: 4.193 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.111 ±(99.9%) 1.584 ms/op [Average]
  (min, avg, max) = (4.020, 4.111, 4.193), stdev = 0.087
  CI (99.9%): [2.527, 5.695] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 11.698 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.384 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.005 ms/op
Iteration   1: 4.066 ±(99.9%) 0.010 ms/op
Iteration   2: 3.981 ±(99.9%) 0.006 ms/op
Iteration   3: 3.993 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.013 ±(99.9%) 0.845 ms/op [Average]
  (min, avg, max) = (3.981, 4.013, 4.066), stdev = 0.046
  CI (99.9%): [3.168, 4.858] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.657 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.676 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.220 ±(99.9%) 0.003 ms/op
Iteration   1: 4.074 ±(99.9%) 0.003 ms/op
Iteration   2: 3.963 ±(99.9%) 0.005 ms/op
Iteration   3: 4.011 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.016 ±(99.9%) 1.018 ms/op [Average]
  (min, avg, max) = (3.963, 4.016, 4.074), stdev = 0.056
  CI (99.9%): [2.998, 5.035] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.989 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.582 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.817 ±(99.9%) 0.009 ms/op
Iteration   1: 4.772 ±(99.9%) 0.014 ms/op
Iteration   2: 4.679 ±(99.9%) 0.015 ms/op
Iteration   3: 4.554 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.668 ±(99.9%) 1.999 ms/op [Average]
  (min, avg, max) = (4.554, 4.668, 4.772), stdev = 0.110
  CI (99.9%): [2.670, 6.667] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.917 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.861 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.533 ±(99.9%) 0.020 ms/op
Iteration   1: 4.030 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.892 ms/op
                 createUser·p0.50:   3.920 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   5.259 ms/op
                 createUser·p0.99:   7.733 ms/op
                 createUser·p0.999:  23.457 ms/op
                 createUser·p0.9999: 34.931 ms/op
                 createUser·p1.00:   36.831 ms/op

Iteration   2: 4.134 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.921 ms/op
                 createUser·p0.50:   3.965 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   5.186 ms/op
                 createUser·p0.99:   7.913 ms/op
                 createUser·p0.999:  12.780 ms/op
                 createUser·p0.9999: 28.901 ms/op
                 createUser·p1.00:   29.721 ms/op

Iteration   3: 4.106 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.624 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.792 ms/op
                 createUser·p0.95:   5.620 ms/op
                 createUser·p0.99:   8.354 ms/op
                 createUser·p0.999:  28.770 ms/op
                 createUser·p0.9999: 35.914 ms/op
                 createUser·p1.00:   39.125 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234718
  mean =      4.090 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 375 
    [ 2.500,  5.000) = 218120 
    [ 5.000,  7.500) = 12888 
    [ 7.500, 10.000) = 2455 
    [10.000, 12.500) = 477 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 42 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.624 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      8.077 ms/op
     p(99.9000) =     23.626 ms/op
     p(99.9900) =     35.065 ms/op
     p(99.9990) =     36.940 ms/op
     p(99.9999) =     39.125 ms/op
    p(100.0000) =     39.125 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 12.158 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.600 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.014 ms/op
Iteration   1: 4.157 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.050 ms/op
                 existUser·p0.50:   3.932 ms/op
                 existUser·p0.90:   4.948 ms/op
                 existUser·p0.95:   5.792 ms/op
                 existUser·p0.99:   8.667 ms/op
                 existUser·p0.999:  14.062 ms/op
                 existUser·p0.9999: 29.413 ms/op
                 existUser·p1.00:   30.343 ms/op

Iteration   2: 4.023 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.782 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.637 ms/op
                 existUser·p0.95:   5.530 ms/op
                 existUser·p0.99:   7.856 ms/op
                 existUser·p0.999:  14.926 ms/op
                 existUser·p0.9999: 34.809 ms/op
                 existUser·p1.00:   36.766 ms/op

Iteration   3: 3.942 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.403 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   5.276 ms/op
                 existUser·p0.99:   8.700 ms/op
                 existUser·p0.999:  27.492 ms/op
                 existUser·p0.9999: 32.604 ms/op
                 existUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 237640
  mean =      4.039 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 298 
    [ 2.500,  5.000) = 219764 
    [ 5.000,  7.500) = 14005 
    [ 7.500, 10.000) = 2370 
    [10.000, 12.500) = 761 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 96 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 36 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      8.307 ms/op
     p(99.9000) =     15.244 ms/op
     p(99.9900) =     33.882 ms/op
     p(99.9990) =     36.511 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


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
# Warmup Iteration   1: 13.489 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.951 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.306 ±(99.9%) 0.018 ms/op
Iteration   1: 4.076 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.768 ms/op
                 getUser·p0.95:   5.841 ms/op
                 getUser·p0.99:   8.651 ms/op
                 getUser·p0.999:  17.400 ms/op
                 getUser·p0.9999: 26.892 ms/op
                 getUser·p1.00:   28.312 ms/op

Iteration   2: 3.990 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.608 ms/op
                 getUser·p0.50:   3.830 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   7.438 ms/op
                 getUser·p0.999:  25.297 ms/op
                 getUser·p0.9999: 36.043 ms/op
                 getUser·p1.00:   37.224 ms/op

Iteration   3: 3.999 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.311 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.341 ms/op
                 getUser·p0.99:   7.578 ms/op
                 getUser·p0.999:  12.402 ms/op
                 getUser·p0.9999: 31.621 ms/op
                 getUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238868
  mean =      4.021 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 207 
    [ 2.500,  5.000) = 223187 
    [ 5.000,  7.500) = 12671 
    [ 7.500, 10.000) = 1843 
    [10.000, 12.500) = 607 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      7.832 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     34.603 ms/op
     p(99.9990) =     37.097 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


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
# Warmup Iteration   1: 14.164 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 5.729 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.784 ±(99.9%) 0.017 ms/op
Iteration   1: 4.653 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.995 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  29.622 ms/op
                 listUser·p0.9999: 32.640 ms/op
                 listUser·p1.00:   35.062 ms/op

Iteration   2: 4.666 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  19.100 ms/op
                 listUser·p0.9999: 21.004 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   3: 4.766 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  16.022 ms/op
                 listUser·p0.9999: 18.107 ms/op
                 listUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204257
  mean =      4.694 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 169638 
    [ 5.000,  7.500) = 29288 
    [ 7.500, 10.000) = 3994 
    [10.000, 12.500) = 744 
    [12.500, 15.000) = 174 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.995 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     19.956 ms/op
     p(99.9900) =     32.122 ms/op
     p(99.9990) =     34.002 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.849 ± 6.770  ops/ms
ClientPb.existUser                       thrpt       3   8.222 ± 3.103  ops/ms
ClientPb.getUser                         thrpt       3   7.778 ± 2.457  ops/ms
ClientPb.listUser                        thrpt       3   6.739 ± 1.975  ops/ms
ClientPb.createUser                       avgt       3   4.111 ± 1.584   ms/op
ClientPb.existUser                        avgt       3   4.013 ± 0.845   ms/op
ClientPb.getUser                          avgt       3   4.016 ± 1.018   ms/op
ClientPb.listUser                         avgt       3   4.668 ± 1.999   ms/op
ClientPb.createUser                     sample  234718   4.090 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.624           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.735           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.077           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.626           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.065           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.125           ms/op
ClientPb.existUser                      sample  237640   4.039 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.403           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.817           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.694           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.538           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.307           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.244           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.882           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.766           ms/op
ClientPb.getUser                        sample  238868   4.021 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.280           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.620           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.390           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.832           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.400           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.603           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.224           ms/op
ClientPb.listUser                       sample  204257   4.694 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.995           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.267           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.816           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.995           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.956           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.122           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.062           ms/op
