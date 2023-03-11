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
# Warmup Iteration   1: 1.160 ops/ms
# Warmup Iteration   2: 2.432 ops/ms
# Warmup Iteration   3: 5.829 ops/ms
Iteration   1: 6.258 ops/ms
Iteration   2: 6.335 ops/ms
Iteration   3: 6.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.461 ±(99.9%) 5.256 ops/ms [Average]
  (min, avg, max) = (6.258, 6.461, 6.791), stdev = 0.288
  CI (99.9%): [1.205, 11.717] (assumes normal distribution)


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
# Warmup Iteration   1: 1.768 ops/ms
# Warmup Iteration   2: 4.935 ops/ms
# Warmup Iteration   3: 6.311 ops/ms
Iteration   1: 6.758 ops/ms
Iteration   2: 6.658 ops/ms
Iteration   3: 6.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.689 ±(99.9%) 1.105 ops/ms [Average]
  (min, avg, max) = (6.650, 6.689, 6.758), stdev = 0.061
  CI (99.9%): [5.584, 7.793] (assumes normal distribution)


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
# Warmup Iteration   1: 1.925 ops/ms
# Warmup Iteration   2: 4.997 ops/ms
# Warmup Iteration   3: 6.131 ops/ms
Iteration   1: 5.932 ops/ms
Iteration   2: 5.888 ops/ms
Iteration   3: 6.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.106 ±(99.9%) 6.197 ops/ms [Average]
  (min, avg, max) = (5.888, 6.106, 6.497), stdev = 0.340
  CI (99.9%): [≈ 0, 12.303] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.606 ops/ms
# Warmup Iteration   2: 4.626 ops/ms
# Warmup Iteration   3: 5.798 ops/ms
Iteration   1: 5.920 ops/ms
Iteration   2: 5.952 ops/ms
Iteration   3: 5.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.920 ±(99.9%) 0.590 ops/ms [Average]
  (min, avg, max) = (5.888, 5.920, 5.952), stdev = 0.032
  CI (99.9%): [5.330, 6.510] (assumes normal distribution)


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
# Warmup Iteration   1: 15.928 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.986 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.297 ±(99.9%) 0.013 ms/op
Iteration   1: 4.979 ±(99.9%) 0.013 ms/op
Iteration   2: 4.869 ±(99.9%) 0.013 ms/op
Iteration   3: 4.800 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.883 ±(99.9%) 1.642 ms/op [Average]
  (min, avg, max) = (4.800, 4.883, 4.979), stdev = 0.090
  CI (99.9%): [3.241, 6.525] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 14.638 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.464 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.885 ±(99.9%) 0.008 ms/op
Iteration   1: 4.659 ±(99.9%) 0.008 ms/op
Iteration   2: 4.600 ±(99.9%) 0.012 ms/op
Iteration   3: 4.633 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.630 ±(99.9%) 0.540 ms/op [Average]
  (min, avg, max) = (4.600, 4.630, 4.659), stdev = 0.030
  CI (99.9%): [4.090, 5.171] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.118 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.979 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.193 ±(99.9%) 0.013 ms/op
Iteration   1: 5.319 ±(99.9%) 0.007 ms/op
Iteration   2: 5.108 ±(99.9%) 0.009 ms/op
Iteration   3: 4.838 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.088 ±(99.9%) 4.397 ms/op [Average]
  (min, avg, max) = (4.838, 5.088, 5.319), stdev = 0.241
  CI (99.9%): [0.691, 9.485] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 16.098 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 6.984 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.788 ±(99.9%) 0.018 ms/op
Iteration   1: 5.880 ±(99.9%) 0.010 ms/op
Iteration   2: 6.034 ±(99.9%) 0.010 ms/op
Iteration   3: 6.348 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.087 ±(99.9%) 4.348 ms/op [Average]
  (min, avg, max) = (5.880, 6.087, 6.348), stdev = 0.238
  CI (99.9%): [1.739, 10.436] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.379 ±(99.9%) 0.275 ms/op
# Warmup Iteration   2: 6.381 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.442 ±(99.9%) 0.023 ms/op
Iteration   1: 5.313 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.503 ms/op
                 createUser·p0.50:   4.981 ms/op
                 createUser·p0.90:   6.578 ms/op
                 createUser·p0.95:   7.717 ms/op
                 createUser·p0.99:   10.600 ms/op
                 createUser·p0.999:  22.863 ms/op
                 createUser·p0.9999: 26.608 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   2: 5.047 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.318 ms/op
                 createUser·p0.50:   4.801 ms/op
                 createUser·p0.90:   6.005 ms/op
                 createUser·p0.95:   6.742 ms/op
                 createUser·p0.99:   9.257 ms/op
                 createUser·p0.999:  23.329 ms/op
                 createUser·p0.9999: 27.863 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   3: 5.271 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.319 ms/op
                 createUser·p0.50:   4.809 ms/op
                 createUser·p0.90:   6.726 ms/op
                 createUser·p0.95:   7.750 ms/op
                 createUser·p0.99:   11.106 ms/op
                 createUser·p0.999:  26.528 ms/op
                 createUser·p0.9999: 29.325 ms/op
                 createUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 184358
  mean =      5.208 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 106513 
    [ 5.000,  7.500) = 68688 
    [ 7.500, 10.000) = 7027 
    [10.000, 12.500) = 1245 
    [12.500, 15.000) = 484 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 91 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      4.850 ms/op
     p(90.0000) =      6.447 ms/op
     p(95.0000) =      7.479 ms/op
     p(99.0000) =     10.224 ms/op
     p(99.9000) =     23.066 ms/op
     p(99.9900) =     28.447 ms/op
     p(99.9990) =     29.852 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.107 ±(99.9%) 0.225 ms/op
# Warmup Iteration   2: 5.502 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.106 ±(99.9%) 0.019 ms/op
Iteration   1: 5.018 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.204 ms/op
                 existUser·p0.50:   4.702 ms/op
                 existUser·p0.90:   6.218 ms/op
                 existUser·p0.95:   7.217 ms/op
                 existUser·p0.99:   10.142 ms/op
                 existUser·p0.999:  21.129 ms/op
                 existUser·p0.9999: 26.124 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   2: 4.870 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.968 ms/op
                 existUser·p0.50:   4.637 ms/op
                 existUser·p0.90:   5.906 ms/op
                 existUser·p0.95:   6.627 ms/op
                 existUser·p0.99:   9.142 ms/op
                 existUser·p0.999:  17.236 ms/op
                 existUser·p0.9999: 27.581 ms/op
                 existUser·p1.00:   27.853 ms/op

Iteration   3: 4.739 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.212 ms/op
                 existUser·p0.50:   4.538 ms/op
                 existUser·p0.90:   5.562 ms/op
                 existUser·p0.95:   6.144 ms/op
                 existUser·p0.99:   8.487 ms/op
                 existUser·p0.999:  16.132 ms/op
                 existUser·p0.9999: 40.845 ms/op
                 existUser·p1.00:   42.598 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 196926
  mean =      4.873 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 139437 
    [ 5.000, 10.000) = 56022 
    [10.000, 15.000) = 1214 
    [15.000, 20.000) = 34 
    [20.000, 25.000) = 83 
    [25.000, 30.000) = 103 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 18 
    [40.000, 45.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      5.890 ms/op
     p(95.0000) =      6.668 ms/op
     p(99.0000) =      9.159 ms/op
     p(99.9000) =     20.283 ms/op
     p(99.9900) =     38.575 ms/op
     p(99.9990) =     41.137 ms/op
     p(99.9999) =     42.598 ms/op
    p(100.0000) =     42.598 ms/op


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
# Warmup Iteration   1: 16.242 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 5.628 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.289 ±(99.9%) 0.019 ms/op
Iteration   1: 5.028 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.068 ms/op
                 getUser·p0.50:   4.727 ms/op
                 getUser·p0.90:   5.923 ms/op
                 getUser·p0.95:   7.553 ms/op
                 getUser·p0.99:   10.093 ms/op
                 getUser·p0.999:  20.744 ms/op
                 getUser·p0.9999: 25.401 ms/op
                 getUser·p1.00:   26.706 ms/op

Iteration   2: 5.092 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.985 ms/op
                 getUser·p0.50:   4.727 ms/op
                 getUser·p0.90:   6.865 ms/op
                 getUser·p0.95:   7.643 ms/op
                 getUser·p0.99:   9.984 ms/op
                 getUser·p0.999:  22.619 ms/op
                 getUser·p0.9999: 28.480 ms/op
                 getUser·p1.00:   30.015 ms/op

Iteration   3: 5.053 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.576 ms/op
                 getUser·p0.50:   4.792 ms/op
                 getUser·p0.90:   6.054 ms/op
                 getUser·p0.95:   7.021 ms/op
                 getUser·p0.99:   9.978 ms/op
                 getUser·p0.999:  24.259 ms/op
                 getUser·p0.9999: 27.547 ms/op
                 getUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 189821
  mean =      5.058 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 123561 
    [ 5.000,  7.500) = 56995 
    [ 7.500, 10.000) = 7338 
    [10.000, 12.500) = 1302 
    [12.500, 15.000) = 252 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.985 ms/op
     p(50.0000) =      4.743 ms/op
     p(90.0000) =      6.218 ms/op
     p(95.0000) =      7.455 ms/op
     p(99.0000) =     10.011 ms/op
     p(99.9000) =     20.875 ms/op
     p(99.9900) =     27.526 ms/op
     p(99.9990) =     29.397 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


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
# Warmup Iteration   1: 19.676 ±(99.9%) 0.317 ms/op
# Warmup Iteration   2: 7.557 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.128 ±(99.9%) 0.023 ms/op
Iteration   1: 5.968 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   5.612 ms/op
                 listUser·p0.90:   7.062 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   11.944 ms/op
                 listUser·p0.999:  25.985 ms/op
                 listUser·p0.9999: 29.458 ms/op
                 listUser·p1.00:   30.409 ms/op

Iteration   2: 5.832 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   3.064 ms/op
                 listUser·p0.50:   5.521 ms/op
                 listUser·p0.90:   6.906 ms/op
                 listUser·p0.95:   7.807 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  26.227 ms/op
                 listUser·p0.9999: 33.588 ms/op
                 listUser·p1.00:   34.406 ms/op

Iteration   3: 5.868 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.699 ms/op
                 listUser·p0.50:   5.612 ms/op
                 listUser·p0.90:   6.717 ms/op
                 listUser·p0.95:   7.717 ms/op
                 listUser·p0.99:   10.928 ms/op
                 listUser·p0.999:  20.531 ms/op
                 listUser·p0.9999: 22.122 ms/op
                 listUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 162821
  mean =      5.889 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 15566 
    [ 5.000,  7.500) = 136566 
    [ 7.500, 10.000) = 7940 
    [10.000, 12.500) = 1752 
    [12.500, 15.000) = 518 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.228 ms/op
     p(50.0000) =      5.579 ms/op
     p(90.0000) =      6.881 ms/op
     p(95.0000) =      8.028 ms/op
     p(99.0000) =     11.272 ms/op
     p(99.9000) =     24.609 ms/op
     p(99.9900) =     32.593 ms/op
     p(99.9990) =     34.201 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.461 ± 5.256  ops/ms
ClientPb.existUser                       thrpt       3   6.689 ± 1.105  ops/ms
ClientPb.getUser                         thrpt       3   6.106 ± 6.197  ops/ms
ClientPb.listUser                        thrpt       3   5.920 ± 0.590  ops/ms
ClientPb.createUser                       avgt       3   4.883 ± 1.642   ms/op
ClientPb.existUser                        avgt       3   4.630 ± 0.540   ms/op
ClientPb.getUser                          avgt       3   5.088 ± 4.397   ms/op
ClientPb.listUser                         avgt       3   6.087 ± 4.348   ms/op
ClientPb.createUser                     sample  184358   5.208 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.319           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.850           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.447           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.479           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.224           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.066           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.447           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.852           ms/op
ClientPb.existUser                      sample  196926   4.873 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.968           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.628           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.890           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.668           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.159           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.283           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.575           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.598           ms/op
ClientPb.getUser                        sample  189821   5.058 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.985           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.743           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.218           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.455           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.011           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.875           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.526           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.015           ms/op
ClientPb.listUser                       sample  162821   5.889 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.228           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.881           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.028           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.272           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.609           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.593           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.406           ms/op
