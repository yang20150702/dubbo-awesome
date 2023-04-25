# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.009 ops/ms
# Warmup Iteration   2: 2.578 ops/ms
# Warmup Iteration   3: 5.419 ops/ms
Iteration   1: 5.644 ops/ms
Iteration   2: 6.038 ops/ms
Iteration   3: 6.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.939 ±(99.9%) 4.741 ops/ms [Average]
  (min, avg, max) = (5.644, 5.939, 6.134), stdev = 0.260
  CI (99.9%): [1.198, 10.680] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.643 ops/ms
# Warmup Iteration   2: 4.994 ops/ms
# Warmup Iteration   3: 6.015 ops/ms
Iteration   1: 6.125 ops/ms
Iteration   2: 5.961 ops/ms
Iteration   3: 5.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.000 ±(99.9%) 2.019 ops/ms [Average]
  (min, avg, max) = (5.914, 6.000, 6.125), stdev = 0.111
  CI (99.9%): [3.980, 8.019] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.483 ops/ms
# Warmup Iteration   2: 4.482 ops/ms
# Warmup Iteration   3: 5.592 ops/ms
Iteration   1: 5.869 ops/ms
Iteration   2: 5.940 ops/ms
Iteration   3: 5.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.846 ±(99.9%) 1.965 ops/ms [Average]
  (min, avg, max) = (5.728, 5.846, 5.940), stdev = 0.108
  CI (99.9%): [3.881, 7.811] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.734 ops/ms
# Warmup Iteration   2: 4.708 ops/ms
# Warmup Iteration   3: 5.595 ops/ms
Iteration   1: 5.317 ops/ms
Iteration   2: 5.072 ops/ms
Iteration   3: 5.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.146 ±(99.9%) 2.720 ops/ms [Average]
  (min, avg, max) = (5.048, 5.146, 5.317), stdev = 0.149
  CI (99.9%): [2.425, 7.866] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.470 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 6.869 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.923 ±(99.9%) 0.011 ms/op
Iteration   1: 5.316 ±(99.9%) 0.012 ms/op
Iteration   2: 5.222 ±(99.9%) 0.009 ms/op
Iteration   3: 5.037 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.192 ±(99.9%) 2.590 ms/op [Average]
  (min, avg, max) = (5.037, 5.192, 5.316), stdev = 0.142
  CI (99.9%): [2.601, 7.782] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 14.564 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.746 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.104 ±(99.9%) 0.005 ms/op
Iteration   1: 5.024 ±(99.9%) 0.005 ms/op
Iteration   2: 5.018 ±(99.9%) 0.015 ms/op
Iteration   3: 5.113 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.052 ±(99.9%) 0.966 ms/op [Average]
  (min, avg, max) = (5.018, 5.052, 5.113), stdev = 0.053
  CI (99.9%): [4.086, 6.018] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 16.473 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 6.395 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.588 ±(99.9%) 0.012 ms/op
Iteration   1: 5.210 ±(99.9%) 0.013 ms/op
Iteration   2: 5.274 ±(99.9%) 0.009 ms/op
Iteration   3: 5.313 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.266 ±(99.9%) 0.943 ms/op [Average]
  (min, avg, max) = (5.210, 5.266, 5.313), stdev = 0.052
  CI (99.9%): [4.323, 6.209] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 17.104 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 7.782 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.571 ±(99.9%) 0.012 ms/op
Iteration   1: 6.019 ±(99.9%) 0.012 ms/op
Iteration   2: 6.498 ±(99.9%) 0.021 ms/op
Iteration   3: 6.236 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.251 ±(99.9%) 4.373 ms/op [Average]
  (min, avg, max) = (6.019, 6.251, 6.498), stdev = 0.240
  CI (99.9%): [1.878, 10.624] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 17.142 ±(99.9%) 0.283 ms/op
# Warmup Iteration   2: 6.386 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.358 ±(99.9%) 0.021 ms/op
Iteration   1: 5.500 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.277 ms/op
                 createUser·p0.50:   5.300 ms/op
                 createUser·p0.90:   7.003 ms/op
                 createUser·p0.95:   7.791 ms/op
                 createUser·p0.99:   10.027 ms/op
                 createUser·p0.999:  22.498 ms/op
                 createUser·p0.9999: 27.523 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   2: 5.223 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.236 ms/op
                 createUser·p0.50:   5.030 ms/op
                 createUser·p0.90:   6.439 ms/op
                 createUser·p0.95:   7.094 ms/op
                 createUser·p0.99:   9.322 ms/op
                 createUser·p0.999:  22.769 ms/op
                 createUser·p0.9999: 26.145 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   3: 5.261 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.212 ms/op
                 createUser·p0.50:   4.940 ms/op
                 createUser·p0.90:   6.586 ms/op
                 createUser·p0.95:   7.324 ms/op
                 createUser·p0.99:   9.552 ms/op
                 createUser·p0.999:  30.573 ms/op
                 createUser·p0.9999: 39.342 ms/op
                 createUser·p1.00:   40.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 180051
  mean =      5.325 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 83787 
    [ 5.000, 10.000) = 94821 
    [10.000, 15.000) = 1119 
    [15.000, 20.000) = 68 
    [20.000, 25.000) = 124 
    [25.000, 30.000) = 68 
    [30.000, 35.000) = 35 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.212 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      6.676 ms/op
     p(95.0000) =      7.422 ms/op
     p(99.0000) =      9.617 ms/op
     p(99.9000) =     23.921 ms/op
     p(99.9900) =     36.961 ms/op
     p(99.9990) =     40.593 ms/op
     p(99.9999) =     40.698 ms/op
    p(100.0000) =     40.698 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 14.955 ±(99.9%) 0.228 ms/op
# Warmup Iteration   2: 5.875 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.125 ±(99.9%) 0.019 ms/op
Iteration   1: 4.940 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.855 ms/op
                 existUser·p0.50:   4.645 ms/op
                 existUser·p0.90:   6.267 ms/op
                 existUser·p0.95:   7.234 ms/op
                 existUser·p0.99:   9.421 ms/op
                 existUser·p0.999:  19.926 ms/op
                 existUser·p0.9999: 28.130 ms/op
                 existUser·p1.00:   28.836 ms/op

Iteration   2: 4.997 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.079 ms/op
                 existUser·p0.50:   4.678 ms/op
                 existUser·p0.90:   6.349 ms/op
                 existUser·p0.95:   7.283 ms/op
                 existUser·p0.99:   9.650 ms/op
                 existUser·p0.999:  26.221 ms/op
                 existUser·p0.9999: 30.540 ms/op
                 existUser·p1.00:   34.669 ms/op

Iteration   3: 5.081 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.236 ms/op
                 existUser·p0.50:   4.776 ms/op
                 existUser·p0.90:   6.496 ms/op
                 existUser·p0.95:   7.258 ms/op
                 existUser·p0.99:   9.503 ms/op
                 existUser·p0.999:  25.626 ms/op
                 existUser·p0.9999: 29.753 ms/op
                 existUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 191600
  mean =      5.005 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 121861 
    [ 5.000,  7.500) = 61874 
    [ 7.500, 10.000) = 6354 
    [10.000, 12.500) = 919 
    [12.500, 15.000) = 279 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 83 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.855 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      6.365 ms/op
     p(95.0000) =      7.258 ms/op
     p(99.0000) =      9.486 ms/op
     p(99.9000) =     22.734 ms/op
     p(99.9900) =     29.753 ms/op
     p(99.9990) =     30.977 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 16.494 ±(99.9%) 0.280 ms/op
# Warmup Iteration   2: 6.494 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.317 ±(99.9%) 0.019 ms/op
Iteration   1: 5.241 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.782 ms/op
                 getUser·p0.50:   4.932 ms/op
                 getUser·p0.90:   6.537 ms/op
                 getUser·p0.95:   7.471 ms/op
                 getUser·p0.99:   10.732 ms/op
                 getUser·p0.999:  24.705 ms/op
                 getUser·p0.9999: 34.013 ms/op
                 getUser·p1.00:   34.931 ms/op

Iteration   2: 5.538 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.441 ms/op
                 getUser·p0.50:   5.153 ms/op
                 getUser·p0.90:   7.127 ms/op
                 getUser·p0.95:   8.339 ms/op
                 getUser·p0.99:   11.700 ms/op
                 getUser·p0.999:  29.727 ms/op
                 getUser·p0.9999: 37.763 ms/op
                 getUser·p1.00:   38.207 ms/op

Iteration   3: 5.263 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.486 ms/op
                 getUser·p0.50:   5.014 ms/op
                 getUser·p0.90:   6.513 ms/op
                 getUser·p0.95:   7.242 ms/op
                 getUser·p0.99:   9.355 ms/op
                 getUser·p0.999:  13.505 ms/op
                 getUser·p0.9999: 30.769 ms/op
                 getUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 179574
  mean =      5.344 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 87567 
    [ 5.000,  7.500) = 81942 
    [ 7.500, 10.000) = 7718 
    [10.000, 12.500) = 1546 
    [12.500, 15.000) = 449 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.782 ms/op
     p(50.0000) =      5.022 ms/op
     p(90.0000) =      6.685 ms/op
     p(95.0000) =      7.692 ms/op
     p(99.0000) =     10.568 ms/op
     p(99.9000) =     23.260 ms/op
     p(99.9900) =     36.045 ms/op
     p(99.9990) =     38.207 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.844 ±(99.9%) 0.305 ms/op
# Warmup Iteration   2: 7.580 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.529 ±(99.9%) 0.027 ms/op
Iteration   1: 6.552 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.248 ms/op
                 listUser·p0.50:   6.160 ms/op
                 listUser·p0.90:   8.258 ms/op
                 listUser·p0.95:   9.650 ms/op
                 listUser·p0.99:   12.410 ms/op
                 listUser·p0.999:  21.833 ms/op
                 listUser·p0.9999: 25.464 ms/op
                 listUser·p1.00:   25.919 ms/op

Iteration   2: 6.583 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.785 ms/op
                 listUser·p0.50:   6.267 ms/op
                 listUser·p0.90:   8.069 ms/op
                 listUser·p0.95:   9.077 ms/op
                 listUser·p0.99:   11.698 ms/op
                 listUser·p0.999:  25.297 ms/op
                 listUser·p0.9999: 27.796 ms/op
                 listUser·p1.00:   28.344 ms/op

Iteration   3: 6.620 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.859 ms/op
                 listUser·p0.50:   6.275 ms/op
                 listUser·p0.90:   8.102 ms/op
                 listUser·p0.95:   9.306 ms/op
                 listUser·p0.99:   13.222 ms/op
                 listUser·p0.999:  25.746 ms/op
                 listUser·p0.9999: 30.158 ms/op
                 listUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 145775
  mean =      6.585 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 5740 
    [ 5.000,  7.500) = 116412 
    [ 7.500, 10.000) = 18645 
    [10.000, 12.500) = 3681 
    [12.500, 15.000) = 760 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.785 ms/op
     p(50.0000) =      6.226 ms/op
     p(90.0000) =      8.135 ms/op
     p(95.0000) =      9.322 ms/op
     p(99.0000) =     12.222 ms/op
     p(99.9000) =     24.263 ms/op
     p(99.9900) =     27.974 ms/op
     p(99.9990) =     30.911 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.939 ± 4.741  ops/ms
ClientPb.existUser                       thrpt       3   6.000 ± 2.019  ops/ms
ClientPb.getUser                         thrpt       3   5.846 ± 1.965  ops/ms
ClientPb.listUser                        thrpt       3   5.146 ± 2.720  ops/ms
ClientPb.createUser                       avgt       3   5.192 ± 2.590   ms/op
ClientPb.existUser                        avgt       3   5.052 ± 0.966   ms/op
ClientPb.getUser                          avgt       3   5.266 ± 0.943   ms/op
ClientPb.listUser                         avgt       3   6.251 ± 4.373   ms/op
ClientPb.createUser                     sample  180051   5.325 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.212           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.087           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.676           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.422           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.617           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.921           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.961           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.698           ms/op
ClientPb.existUser                      sample  191600   5.005 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.855           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.702           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.365           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.258           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.486           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.734           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.753           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.669           ms/op
ClientPb.getUser                        sample  179574   5.344 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.782           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.022           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.685           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.692           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.568           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.260           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.045           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.207           ms/op
ClientPb.listUser                       sample  145775   6.585 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.785           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.226           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.135           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.322           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.222           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.263           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.974           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.031           ms/op
