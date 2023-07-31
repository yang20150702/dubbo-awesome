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
# Warmup Iteration   1: 1.591 ops/ms
# Warmup Iteration   2: 3.672 ops/ms
# Warmup Iteration   3: 6.964 ops/ms
Iteration   1: 7.598 ops/ms
Iteration   2: 7.766 ops/ms
Iteration   3: 7.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.771 ±(99.9%) 3.205 ops/ms [Average]
  (min, avg, max) = (7.598, 7.771, 7.949), stdev = 0.176
  CI (99.9%): [4.566, 10.977] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.115 ops/ms
# Warmup Iteration   2: 7.031 ops/ms
# Warmup Iteration   3: 8.145 ops/ms
Iteration   1: 8.448 ops/ms
Iteration   2: 8.177 ops/ms
Iteration   3: 8.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.290 ±(99.9%) 2.573 ops/ms [Average]
  (min, avg, max) = (8.177, 8.290, 8.448), stdev = 0.141
  CI (99.9%): [5.717, 10.863] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.419 ops/ms
# Warmup Iteration   2: 6.805 ops/ms
# Warmup Iteration   3: 7.531 ops/ms
Iteration   1: 7.725 ops/ms
Iteration   2: 7.685 ops/ms
Iteration   3: 7.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.706 ±(99.9%) 0.371 ops/ms [Average]
  (min, avg, max) = (7.685, 7.706, 7.725), stdev = 0.020
  CI (99.9%): [7.335, 8.077] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.003 ops/ms
# Warmup Iteration   2: 4.574 ops/ms
# Warmup Iteration   3: 6.364 ops/ms
Iteration   1: 6.784 ops/ms
Iteration   2: 6.649 ops/ms
Iteration   3: 6.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.810 ±(99.9%) 3.213 ops/ms [Average]
  (min, avg, max) = (6.649, 6.810, 6.998), stdev = 0.176
  CI (99.9%): [3.597, 10.024] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 11.794 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.799 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.182 ±(99.9%) 0.004 ms/op
Iteration   1: 3.952 ±(99.9%) 0.007 ms/op
Iteration   2: 3.973 ±(99.9%) 0.007 ms/op
Iteration   3: 3.965 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.963 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (3.952, 3.963, 3.973), stdev = 0.010
  CI (99.9%): [3.774, 4.152] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.243 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.472 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.883 ±(99.9%) 0.006 ms/op
Iteration   1: 3.970 ±(99.9%) 0.007 ms/op
Iteration   2: 3.950 ±(99.9%) 0.009 ms/op
Iteration   3: 3.881 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.934 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (3.881, 3.934, 3.970), stdev = 0.047
  CI (99.9%): [3.081, 4.787] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 11.339 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.695 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.105 ±(99.9%) 0.008 ms/op
Iteration   1: 4.057 ±(99.9%) 0.004 ms/op
Iteration   2: 3.958 ±(99.9%) 0.004 ms/op
Iteration   3: 3.831 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.949 ±(99.9%) 2.065 ms/op [Average]
  (min, avg, max) = (3.831, 3.949, 4.057), stdev = 0.113
  CI (99.9%): [1.883, 6.014] (assumes normal distribution)


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
# Warmup Iteration   1: 14.059 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.382 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.693 ±(99.9%) 0.011 ms/op
Iteration   1: 4.621 ±(99.9%) 0.006 ms/op
Iteration   2: 4.662 ±(99.9%) 0.007 ms/op
Iteration   3: 4.682 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.655 ±(99.9%) 0.571 ms/op [Average]
  (min, avg, max) = (4.621, 4.655, 4.682), stdev = 0.031
  CI (99.9%): [4.084, 5.227] (assumes normal distribution)


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
# Warmup Iteration   1: 13.821 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 5.060 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.399 ±(99.9%) 0.019 ms/op
Iteration   1: 4.056 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.769 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.579 ms/op
                 createUser·p0.99:   7.733 ms/op
                 createUser·p0.999:  16.482 ms/op
                 createUser·p0.9999: 26.000 ms/op
                 createUser·p1.00:   27.296 ms/op

Iteration   2: 3.969 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  25.180 ms/op
                 createUser·p0.9999: 29.491 ms/op
                 createUser·p1.00:   29.917 ms/op

Iteration   3: 4.081 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   2.126 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.940 ms/op
                 createUser·p0.95:   5.472 ms/op
                 createUser·p0.99:   6.955 ms/op
                 createUser·p0.999:  27.206 ms/op
                 createUser·p0.9999: 33.396 ms/op
                 createUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237750
  mean =      4.035 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 294 
    [ 2.500,  5.000) = 220330 
    [ 5.000,  7.500) = 15061 
    [ 7.500, 10.000) = 1384 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 128 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     24.576 ms/op
     p(99.9900) =     32.972 ms/op
     p(99.9990) =     33.542 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 11.188 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.130 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.011 ms/op
Iteration   1: 3.839 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.372 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.981 ms/op
                 existUser·p0.99:   6.915 ms/op
                 existUser·p0.999:  14.778 ms/op
                 existUser·p0.9999: 25.428 ms/op
                 existUser·p1.00:   25.821 ms/op

Iteration   2: 4.142 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.440 ms/op
                 existUser·p0.50:   3.916 ms/op
                 existUser·p0.90:   5.014 ms/op
                 existUser·p0.95:   5.472 ms/op
                 existUser·p0.99:   7.553 ms/op
                 existUser·p0.999:  14.021 ms/op
                 existUser·p0.9999: 29.603 ms/op
                 existUser·p1.00:   30.900 ms/op

Iteration   3: 3.832 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   7.602 ms/op
                 existUser·p0.999:  27.432 ms/op
                 existUser·p0.9999: 31.424 ms/op
                 existUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 243914
  mean =      3.933 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 533 
    [ 2.500,  5.000) = 228008 
    [ 5.000,  7.500) = 13185 
    [ 7.500, 10.000) = 1339 
    [10.000, 12.500) = 419 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 89 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     18.064 ms/op
     p(99.9900) =     29.970 ms/op
     p(99.9990) =     33.261 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 11.889 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.420 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.139 ±(99.9%) 0.014 ms/op
Iteration   1: 4.199 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.894 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   5.038 ms/op
                 getUser·p0.95:   6.955 ms/op
                 getUser·p0.99:   9.716 ms/op
                 getUser·p0.999:  21.904 ms/op
                 getUser·p0.9999: 27.009 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   2: 4.100 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.364 ms/op
                 getUser·p0.50:   3.916 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   8.372 ms/op
                 getUser·p0.999:  22.086 ms/op
                 getUser·p0.9999: 24.891 ms/op
                 getUser·p1.00:   25.756 ms/op

Iteration   3: 3.961 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.784 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   7.102 ms/op
                 getUser·p0.999:  11.998 ms/op
                 getUser·p0.9999: 28.272 ms/op
                 getUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234972
  mean =      4.084 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 145 
    [ 2.500,  5.000) = 218438 
    [ 5.000,  7.500) = 11154 
    [ 7.500, 10.000) = 4089 
    [10.000, 12.500) = 752 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 82 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     21.398 ms/op
     p(99.9900) =     27.787 ms/op
     p(99.9990) =     29.032 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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
# Warmup Iteration   1: 13.658 ±(99.9%) 0.236 ms/op
# Warmup Iteration   2: 5.186 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.931 ±(99.9%) 0.020 ms/op
Iteration   1: 4.777 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.896 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   6.873 ms/op
                 listUser·p0.99:   9.885 ms/op
                 listUser·p0.999:  26.020 ms/op
                 listUser·p0.9999: 28.732 ms/op
                 listUser·p1.00:   30.048 ms/op

Iteration   2: 4.716 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.976 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.455 ms/op
                 listUser·p0.99:   9.683 ms/op
                 listUser·p0.999:  17.826 ms/op
                 listUser·p0.9999: 20.873 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   3: 4.701 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   6.250 ms/op
                 listUser·p0.99:   10.076 ms/op
                 listUser·p0.999:  16.809 ms/op
                 listUser·p0.9999: 19.195 ms/op
                 listUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202751
  mean =      4.731 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 175236 
    [ 5.000,  7.500) = 20393 
    [ 7.500, 10.000) = 5210 
    [10.000, 12.500) = 1127 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 252 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.896 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      6.103 ms/op
     p(99.0000) =      9.896 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     27.596 ms/op
     p(99.9990) =     29.686 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.771 ± 3.205  ops/ms
ClientPb.existUser                       thrpt       3   8.290 ± 2.573  ops/ms
ClientPb.getUser                         thrpt       3   7.706 ± 0.371  ops/ms
ClientPb.listUser                        thrpt       3   6.810 ± 3.213  ops/ms
ClientPb.createUser                       avgt       3   3.963 ± 0.189   ms/op
ClientPb.existUser                        avgt       3   3.934 ± 0.853   ms/op
ClientPb.getUser                          avgt       3   3.949 ± 2.065   ms/op
ClientPb.listUser                         avgt       3   4.655 ± 0.571   ms/op
ClientPb.createUser                     sample  237750   4.035 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.229           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.768           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.390           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.242           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.576           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.972           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.554           ms/op
ClientPb.existUser                      sample  243914   3.933 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.202           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.678           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.128           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.315           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.064           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.970           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.751           ms/op
ClientPb.getUser                        sample  234972   4.084 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.364           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.620           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.792           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.585           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.398           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.787           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.164           ms/op
ClientPb.listUser                       sample  202751   4.731 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.896           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.128           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.103           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.896           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.514           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.596           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.048           ms/op
