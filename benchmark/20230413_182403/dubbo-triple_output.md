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
# Warmup Iteration   1: 1.417 ops/ms
# Warmup Iteration   2: 3.507 ops/ms
# Warmup Iteration   3: 6.357 ops/ms
Iteration   1: 6.630 ops/ms
Iteration   2: 6.766 ops/ms
Iteration   3: 6.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.718 ±(99.9%) 1.389 ops/ms [Average]
  (min, avg, max) = (6.630, 6.718, 6.766), stdev = 0.076
  CI (99.9%): [5.329, 8.106] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.200 ops/ms
# Warmup Iteration   2: 6.328 ops/ms
# Warmup Iteration   3: 6.875 ops/ms
Iteration   1: 7.622 ops/ms
Iteration   2: 7.190 ops/ms
Iteration   3: 7.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.443 ±(99.9%) 4.104 ops/ms [Average]
  (min, avg, max) = (7.190, 7.443, 7.622), stdev = 0.225
  CI (99.9%): [3.339, 11.547] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.986 ops/ms
# Warmup Iteration   2: 5.708 ops/ms
# Warmup Iteration   3: 6.656 ops/ms
Iteration   1: 6.945 ops/ms
Iteration   2: 6.444 ops/ms
Iteration   3: 7.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.800 ±(99.9%) 5.651 ops/ms [Average]
  (min, avg, max) = (6.444, 6.800, 7.010), stdev = 0.310
  CI (99.9%): [1.148, 12.451] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.000 ops/ms
# Warmup Iteration   2: 5.018 ops/ms
# Warmup Iteration   3: 5.426 ops/ms
Iteration   1: 5.943 ops/ms
Iteration   2: 5.764 ops/ms
Iteration   3: 6.094 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.934 ±(99.9%) 3.005 ops/ms [Average]
  (min, avg, max) = (5.764, 5.934, 6.094), stdev = 0.165
  CI (99.9%): [2.928, 8.939] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 14.932 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.495 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.750 ±(99.9%) 0.019 ms/op
Iteration   1: 4.702 ±(99.9%) 0.014 ms/op
Iteration   2: 4.944 ±(99.9%) 0.012 ms/op
Iteration   3: 4.565 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.737 ±(99.9%) 3.505 ms/op [Average]
  (min, avg, max) = (4.565, 4.737, 4.944), stdev = 0.192
  CI (99.9%): [1.232, 8.242] (assumes normal distribution)


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
# Warmup Iteration   1: 12.989 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.074 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.624 ±(99.9%) 0.017 ms/op
Iteration   1: 4.354 ±(99.9%) 0.021 ms/op
Iteration   2: 4.582 ±(99.9%) 0.014 ms/op
Iteration   3: 4.490 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.475 ±(99.9%) 2.087 ms/op [Average]
  (min, avg, max) = (4.354, 4.475, 4.582), stdev = 0.114
  CI (99.9%): [2.388, 6.563] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 14.304 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.468 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.840 ±(99.9%) 0.007 ms/op
Iteration   1: 5.218 ±(99.9%) 0.006 ms/op
Iteration   2: 4.705 ±(99.9%) 0.006 ms/op
Iteration   3: 4.861 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.928 ±(99.9%) 4.791 ms/op [Average]
  (min, avg, max) = (4.705, 4.928, 5.218), stdev = 0.263
  CI (99.9%): [0.137, 9.719] (assumes normal distribution)


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
# Warmup Iteration   1: 15.691 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.169 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.187 ±(99.9%) 0.021 ms/op
Iteration   1: 5.440 ±(99.9%) 0.013 ms/op
Iteration   2: 5.454 ±(99.9%) 0.015 ms/op
Iteration   3: 5.500 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.465 ±(99.9%) 0.575 ms/op [Average]
  (min, avg, max) = (5.440, 5.465, 5.500), stdev = 0.031
  CI (99.9%): [4.890, 6.039] (assumes normal distribution)


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
# Warmup Iteration   1: 14.854 ±(99.9%) 0.217 ms/op
# Warmup Iteration   2: 5.864 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.737 ±(99.9%) 0.017 ms/op
Iteration   1: 4.992 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.667 ms/op
                 createUser·p0.50:   4.776 ms/op
                 createUser·p0.90:   6.137 ms/op
                 createUser·p0.95:   6.857 ms/op
                 createUser·p0.99:   9.474 ms/op
                 createUser·p0.999:  23.752 ms/op
                 createUser·p0.9999: 31.548 ms/op
                 createUser·p1.00:   31.850 ms/op

Iteration   2: 4.544 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.913 ms/op
                 createUser·p0.50:   4.391 ms/op
                 createUser·p0.90:   5.431 ms/op
                 createUser·p0.95:   5.939 ms/op
                 createUser·p0.99:   7.668 ms/op
                 createUser·p0.999:  12.255 ms/op
                 createUser·p0.9999: 24.115 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   3: 4.722 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.183 ms/op
                 createUser·p0.50:   4.489 ms/op
                 createUser·p0.90:   5.751 ms/op
                 createUser·p0.95:   6.349 ms/op
                 createUser·p0.99:   8.765 ms/op
                 createUser·p0.999:  14.931 ms/op
                 createUser·p0.9999: 32.783 ms/op
                 createUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 202146
  mean =      4.746 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 223 
    [ 2.500,  5.000) = 143400 
    [ 5.000,  7.500) = 54100 
    [ 7.500, 10.000) = 3377 
    [10.000, 12.500) = 645 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.667 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.792 ms/op
     p(95.0000) =      6.398 ms/op
     p(99.0000) =      8.700 ms/op
     p(99.9000) =     15.913 ms/op
     p(99.9900) =     31.542 ms/op
     p(99.9990) =     33.811 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 14.271 ±(99.9%) 0.209 ms/op
# Warmup Iteration   2: 5.135 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.677 ±(99.9%) 0.015 ms/op
Iteration   1: 4.646 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.212 ms/op
                 existUser·p0.50:   4.432 ms/op
                 existUser·p0.90:   5.652 ms/op
                 existUser·p0.95:   6.300 ms/op
                 existUser·p0.99:   8.777 ms/op
                 existUser·p0.999:  15.247 ms/op
                 existUser·p0.9999: 26.087 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   2: 4.578 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.849 ms/op
                 existUser·p0.50:   4.415 ms/op
                 existUser·p0.90:   5.505 ms/op
                 existUser·p0.95:   6.038 ms/op
                 existUser·p0.99:   7.963 ms/op
                 existUser·p0.999:  14.393 ms/op
                 existUser·p0.9999: 26.806 ms/op
                 existUser·p1.00:   27.394 ms/op

Iteration   3: 4.871 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.962 ms/op
                 existUser·p0.50:   4.612 ms/op
                 existUser·p0.90:   6.128 ms/op
                 existUser·p0.95:   7.029 ms/op
                 existUser·p0.99:   9.388 ms/op
                 existUser·p0.999:  16.818 ms/op
                 existUser·p0.9999: 27.570 ms/op
                 existUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 204471
  mean =      4.695 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 103 
    [ 2.500,  5.000) = 153475 
    [ 5.000,  7.500) = 46212 
    [ 7.500, 10.000) = 3647 
    [10.000, 12.500) = 705 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 76 

  Percentiles, ms/op:
      p(0.0000) =      1.849 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.718 ms/op
     p(95.0000) =      6.496 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     15.999 ms/op
     p(99.9900) =     27.052 ms/op
     p(99.9990) =     28.770 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 12.810 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 4.894 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.811 ±(99.9%) 0.018 ms/op
Iteration   1: 4.594 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.800 ms/op
                 getUser·p0.50:   4.399 ms/op
                 getUser·p0.90:   5.472 ms/op
                 getUser·p0.95:   6.193 ms/op
                 getUser·p0.99:   8.667 ms/op
                 getUser·p0.999:  14.670 ms/op
                 getUser·p0.9999: 23.070 ms/op
                 getUser·p1.00:   23.626 ms/op

Iteration   2: 4.760 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.696 ms/op
                 getUser·p0.50:   4.571 ms/op
                 getUser·p0.90:   5.808 ms/op
                 getUser·p0.95:   6.537 ms/op
                 getUser·p0.99:   8.552 ms/op
                 getUser·p0.999:  14.334 ms/op
                 getUser·p0.9999: 23.724 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   3: 4.574 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.494 ms/op
                 getUser·p0.50:   4.383 ms/op
                 getUser·p0.90:   5.505 ms/op
                 getUser·p0.95:   6.054 ms/op
                 getUser·p0.99:   7.807 ms/op
                 getUser·p0.999:  17.465 ms/op
                 getUser·p0.9999: 30.573 ms/op
                 getUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 206611
  mean =      4.641 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 158797 
    [ 5.000,  7.500) = 44139 
    [ 7.500, 10.000) = 2775 
    [10.000, 12.500) = 514 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.696 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.595 ms/op
     p(95.0000) =      6.259 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     16.888 ms/op
     p(99.9900) =     29.994 ms/op
     p(99.9990) =     31.650 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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
# Warmup Iteration   1: 14.615 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 5.799 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.930 ±(99.9%) 0.023 ms/op
Iteration   1: 5.794 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.048 ms/op
                 listUser·p0.50:   5.464 ms/op
                 listUser·p0.90:   7.004 ms/op
                 listUser·p0.95:   8.184 ms/op
                 listUser·p0.99:   12.190 ms/op
                 listUser·p0.999:  27.807 ms/op
                 listUser·p0.9999: 34.076 ms/op
                 listUser·p1.00:   34.931 ms/op

Iteration   2: 5.646 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.827 ms/op
                 listUser·p0.50:   5.399 ms/op
                 listUser·p0.90:   6.726 ms/op
                 listUser·p0.95:   7.496 ms/op
                 listUser·p0.99:   10.912 ms/op
                 listUser·p0.999:  24.416 ms/op
                 listUser·p0.9999: 31.872 ms/op
                 listUser·p1.00:   33.063 ms/op

Iteration   3: 5.478 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.597 ms/op
                 listUser·p0.50:   5.218 ms/op
                 listUser·p0.90:   6.578 ms/op
                 listUser·p0.95:   7.807 ms/op
                 listUser·p0.99:   10.562 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 19.442 ms/op
                 listUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 170219
  mean =      5.636 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 51494 
    [ 5.000,  7.500) = 108611 
    [ 7.500, 10.000) = 7311 
    [10.000, 12.500) = 1736 
    [12.500, 15.000) = 508 
    [15.000, 17.500) = 237 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.827 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      6.775 ms/op
     p(95.0000) =      7.807 ms/op
     p(99.0000) =     11.141 ms/op
     p(99.9000) =     23.422 ms/op
     p(99.9900) =     32.534 ms/op
     p(99.9990) =     34.701 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.718 ± 1.389  ops/ms
ClientPb.existUser                       thrpt       3   7.443 ± 4.104  ops/ms
ClientPb.getUser                         thrpt       3   6.800 ± 5.651  ops/ms
ClientPb.listUser                        thrpt       3   5.934 ± 3.005  ops/ms
ClientPb.createUser                       avgt       3   4.737 ± 3.505   ms/op
ClientPb.existUser                        avgt       3   4.475 ± 2.087   ms/op
ClientPb.getUser                          avgt       3   4.928 ± 4.791   ms/op
ClientPb.listUser                         avgt       3   5.465 ± 0.575   ms/op
ClientPb.createUser                     sample  202146   4.746 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.667           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.538           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.792           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.398           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.700           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.913           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.542           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.079           ms/op
ClientPb.existUser                      sample  204471   4.695 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.849           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.481           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.718           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.496           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.733           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.999           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.052           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.770           ms/op
ClientPb.getUser                        sample  206611   4.641 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.696           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.440           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.595           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.259           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.520           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.888           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.994           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.883           ms/op
ClientPb.listUser                       sample  170219   5.636 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.827           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.349           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.775           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.807           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.141           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.422           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.534           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.931           ms/op
