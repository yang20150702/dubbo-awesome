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
# Warmup Iteration   1: 1.236 ops/ms
# Warmup Iteration   2: 2.901 ops/ms
# Warmup Iteration   3: 5.909 ops/ms
Iteration   1: 6.092 ops/ms
Iteration   2: 6.479 ops/ms
Iteration   3: 6.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.365 ±(99.9%) 4.337 ops/ms [Average]
  (min, avg, max) = (6.092, 6.365, 6.524), stdev = 0.238
  CI (99.9%): [2.028, 10.702] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.959 ops/ms
# Warmup Iteration   2: 6.213 ops/ms
# Warmup Iteration   3: 6.403 ops/ms
Iteration   1: 6.880 ops/ms
Iteration   2: 6.881 ops/ms
Iteration   3: 6.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.842 ±(99.9%) 1.209 ops/ms [Average]
  (min, avg, max) = (6.766, 6.842, 6.881), stdev = 0.066
  CI (99.9%): [5.634, 8.051] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.647 ops/ms
# Warmup Iteration   2: 4.881 ops/ms
# Warmup Iteration   3: 6.236 ops/ms
Iteration   1: 6.413 ops/ms
Iteration   2: 6.408 ops/ms
Iteration   3: 5.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.145 ±(99.9%) 8.383 ops/ms [Average]
  (min, avg, max) = (5.614, 6.145, 6.413), stdev = 0.460
  CI (99.9%): [≈ 0, 14.528] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.674 ops/ms
# Warmup Iteration   2: 4.627 ops/ms
# Warmup Iteration   3: 5.367 ops/ms
Iteration   1: 5.615 ops/ms
Iteration   2: 5.596 ops/ms
Iteration   3: 5.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.677 ±(99.9%) 2.258 ops/ms [Average]
  (min, avg, max) = (5.596, 5.677, 5.819), stdev = 0.124
  CI (99.9%): [3.418, 7.935] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 16.166 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.940 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.368 ±(99.9%) 0.005 ms/op
Iteration   1: 4.917 ±(99.9%) 0.015 ms/op
Iteration   2: 5.094 ±(99.9%) 0.011 ms/op
Iteration   3: 4.958 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.989 ±(99.9%) 1.688 ms/op [Average]
  (min, avg, max) = (4.917, 4.989, 5.094), stdev = 0.093
  CI (99.9%): [3.302, 6.677] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 17.602 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.577 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.818 ±(99.9%) 0.009 ms/op
Iteration   1: 4.706 ±(99.9%) 0.012 ms/op
Iteration   2: 4.738 ±(99.9%) 0.009 ms/op
Iteration   3: 4.794 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.746 ±(99.9%) 0.815 ms/op [Average]
  (min, avg, max) = (4.706, 4.746, 4.794), stdev = 0.045
  CI (99.9%): [3.932, 5.561] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 15.831 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.589 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.936 ±(99.9%) 0.011 ms/op
Iteration   1: 4.991 ±(99.9%) 0.011 ms/op
Iteration   2: 5.090 ±(99.9%) 0.020 ms/op
Iteration   3: 5.058 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.046 ±(99.9%) 0.928 ms/op [Average]
  (min, avg, max) = (4.991, 5.046, 5.090), stdev = 0.051
  CI (99.9%): [4.118, 5.975] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.303 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 6.991 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.010 ±(99.9%) 0.012 ms/op
Iteration   1: 5.652 ±(99.9%) 0.013 ms/op
Iteration   2: 5.782 ±(99.9%) 0.016 ms/op
Iteration   3: 5.413 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.616 ±(99.9%) 3.414 ms/op [Average]
  (min, avg, max) = (5.413, 5.616, 5.782), stdev = 0.187
  CI (99.9%): [2.201, 9.030] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.678 ±(99.9%) 0.272 ms/op
# Warmup Iteration   2: 6.370 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.721 ±(99.9%) 0.023 ms/op
Iteration   1: 4.885 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.249 ms/op
                 createUser·p0.50:   4.669 ms/op
                 createUser·p0.90:   5.816 ms/op
                 createUser·p0.95:   6.291 ms/op
                 createUser·p0.99:   8.454 ms/op
                 createUser·p0.999:  15.803 ms/op
                 createUser·p0.9999: 26.140 ms/op
                 createUser·p1.00:   26.739 ms/op

Iteration   2: 5.092 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.659 ms/op
                 createUser·p0.50:   4.915 ms/op
                 createUser·p0.90:   6.078 ms/op
                 createUser·p0.95:   6.496 ms/op
                 createUser·p0.99:   8.454 ms/op
                 createUser·p0.999:  22.047 ms/op
                 createUser·p0.9999: 27.778 ms/op
                 createUser·p1.00:   28.377 ms/op

Iteration   3: 4.963 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.175 ms/op
                 createUser·p0.50:   4.743 ms/op
                 createUser·p0.90:   6.046 ms/op
                 createUser·p0.95:   6.685 ms/op
                 createUser·p0.99:   8.585 ms/op
                 createUser·p0.999:  19.672 ms/op
                 createUser·p0.9999: 27.354 ms/op
                 createUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 192714
  mean =      4.978 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 121197 
    [ 5.000,  7.500) = 67697 
    [ 7.500, 10.000) = 2969 
    [10.000, 12.500) = 404 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 85 

  Percentiles, ms/op:
      p(0.0000) =      1.659 ms/op
     p(50.0000) =      4.768 ms/op
     p(90.0000) =      5.988 ms/op
     p(95.0000) =      6.488 ms/op
     p(99.0000) =      8.487 ms/op
     p(99.9000) =     20.494 ms/op
     p(99.9900) =     27.016 ms/op
     p(99.9990) =     28.513 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.780 ±(99.9%) 0.214 ms/op
# Warmup Iteration   2: 5.672 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 4.938 ±(99.9%) 0.017 ms/op
Iteration   1: 4.653 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.835 ms/op
                 existUser·p0.50:   4.456 ms/op
                 existUser·p0.90:   5.439 ms/op
                 existUser·p0.95:   6.046 ms/op
                 existUser·p0.99:   8.348 ms/op
                 existUser·p0.999:  14.396 ms/op
                 existUser·p0.9999: 23.986 ms/op
                 existUser·p1.00:   24.740 ms/op

Iteration   2: 4.641 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   2.224 ms/op
                 existUser·p0.50:   4.440 ms/op
                 existUser·p0.90:   5.423 ms/op
                 existUser·p0.95:   6.013 ms/op
                 existUser·p0.99:   7.660 ms/op
                 existUser·p0.999:  19.957 ms/op
                 existUser·p0.9999: 26.513 ms/op
                 existUser·p1.00:   27.787 ms/op

Iteration   3: 4.840 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.819 ms/op
                 existUser·p0.50:   4.571 ms/op
                 existUser·p0.90:   5.734 ms/op
                 existUser·p0.95:   6.521 ms/op
                 existUser·p0.99:   9.322 ms/op
                 existUser·p0.999:  20.326 ms/op
                 existUser·p0.9999: 30.946 ms/op
                 existUser·p1.00:   32.637 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 203860
  mean =      4.710 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 102 
    [ 2.500,  5.000) = 160582 
    [ 5.000,  7.500) = 39081 
    [ 7.500, 10.000) = 3140 
    [10.000, 12.500) = 479 
    [12.500, 15.000) = 243 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.819 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      6.169 ms/op
     p(99.0000) =      8.700 ms/op
     p(99.9000) =     18.822 ms/op
     p(99.9900) =     30.232 ms/op
     p(99.9990) =     31.835 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.616 ±(99.9%) 0.250 ms/op
# Warmup Iteration   2: 5.750 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.090 ±(99.9%) 0.016 ms/op
Iteration   1: 4.986 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.359 ms/op
                 getUser·p0.50:   4.751 ms/op
                 getUser·p0.90:   5.767 ms/op
                 getUser·p0.95:   6.447 ms/op
                 getUser·p0.99:   9.322 ms/op
                 getUser·p0.999:  19.748 ms/op
                 getUser·p0.9999: 22.334 ms/op
                 getUser·p1.00:   25.395 ms/op

Iteration   2: 5.073 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.261 ms/op
                 getUser·p0.50:   4.719 ms/op
                 getUser·p0.90:   6.062 ms/op
                 getUser·p0.95:   7.389 ms/op
                 getUser·p0.99:   11.026 ms/op
                 getUser·p0.999:  23.489 ms/op
                 getUser·p0.9999: 29.728 ms/op
                 getUser·p1.00:   33.260 ms/op

Iteration   3: 4.849 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.867 ms/op
                 getUser·p0.50:   4.653 ms/op
                 getUser·p0.90:   5.628 ms/op
                 getUser·p0.95:   6.595 ms/op
                 getUser·p0.99:   9.750 ms/op
                 getUser·p0.999:  14.988 ms/op
                 getUser·p0.9999: 26.995 ms/op
                 getUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 193078
  mean =      4.968 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 136843 
    [ 5.000,  7.500) = 49520 
    [ 7.500, 10.000) = 4876 
    [10.000, 12.500) = 1045 
    [12.500, 15.000) = 330 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.261 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      5.816 ms/op
     p(95.0000) =      6.799 ms/op
     p(99.0000) =      9.912 ms/op
     p(99.9000) =     21.004 ms/op
     p(99.9900) =     26.729 ms/op
     p(99.9990) =     33.138 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.754 ±(99.9%) 0.287 ms/op
# Warmup Iteration   2: 7.224 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.865 ±(99.9%) 0.022 ms/op
Iteration   1: 5.981 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.753 ms/op
                 listUser·p0.50:   5.726 ms/op
                 listUser·p0.90:   7.094 ms/op
                 listUser·p0.95:   8.331 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  23.300 ms/op
                 listUser·p0.9999: 26.214 ms/op
                 listUser·p1.00:   27.034 ms/op

Iteration   2: 5.852 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.724 ms/op
                 listUser·p0.50:   5.513 ms/op
                 listUser·p0.90:   7.022 ms/op
                 listUser·p0.95:   8.298 ms/op
                 listUser·p0.99:   10.699 ms/op
                 listUser·p0.999:  25.532 ms/op
                 listUser·p0.9999: 31.951 ms/op
                 listUser·p1.00:   33.751 ms/op

Iteration   3: 5.694 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   5.423 ms/op
                 listUser·p0.90:   6.717 ms/op
                 listUser·p0.95:   7.553 ms/op
                 listUser·p0.99:   10.125 ms/op
                 listUser·p0.999:  22.110 ms/op
                 listUser·p0.9999: 28.660 ms/op
                 listUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 164239
  mean =      5.840 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 25842 
    [ 5.000,  7.500) = 127542 
    [ 7.500, 10.000) = 8616 
    [10.000, 12.500) = 1497 
    [12.500, 15.000) = 332 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      5.546 ms/op
     p(90.0000) =      6.939 ms/op
     p(95.0000) =      8.045 ms/op
     p(99.0000) =     10.551 ms/op
     p(99.9000) =     23.331 ms/op
     p(99.9900) =     30.657 ms/op
     p(99.9990) =     33.709 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.365 ± 4.337  ops/ms
ClientPb.existUser                       thrpt       3   6.842 ± 1.209  ops/ms
ClientPb.getUser                         thrpt       3   6.145 ± 8.383  ops/ms
ClientPb.listUser                        thrpt       3   5.677 ± 2.258  ops/ms
ClientPb.createUser                       avgt       3   4.989 ± 1.688   ms/op
ClientPb.existUser                        avgt       3   4.746 ± 0.815   ms/op
ClientPb.getUser                          avgt       3   5.046 ± 0.928   ms/op
ClientPb.listUser                         avgt       3   5.616 ± 3.414   ms/op
ClientPb.createUser                     sample  192714   4.978 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.659           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.768           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.988           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.488           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.487           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.494           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.016           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.574           ms/op
ClientPb.existUser                      sample  203860   4.710 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.819           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.481           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.538           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.169           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.700           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.822           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.232           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.637           ms/op
ClientPb.getUser                        sample  193078   4.968 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.261           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.710           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.816           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.799           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.912           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.004           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.729           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.260           ms/op
ClientPb.listUser                       sample  164239   5.840 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.116           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.939           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.045           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.551           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.331           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.657           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.751           ms/op
