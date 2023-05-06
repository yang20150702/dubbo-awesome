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
# Warmup Iteration   1: 1.782 ops/ms
# Warmup Iteration   2: 3.890 ops/ms
# Warmup Iteration   3: 7.414 ops/ms
Iteration   1: 7.588 ops/ms
Iteration   2: 8.179 ops/ms
Iteration   3: 8.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.933 ±(99.9%) 5.613 ops/ms [Average]
  (min, avg, max) = (7.588, 7.933, 8.179), stdev = 0.308
  CI (99.9%): [2.320, 13.546] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.437 ops/ms
# Warmup Iteration   2: 7.118 ops/ms
# Warmup Iteration   3: 8.292 ops/ms
Iteration   1: 8.241 ops/ms
Iteration   2: 8.241 ops/ms
Iteration   3: 8.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.334 ±(99.9%) 2.931 ops/ms [Average]
  (min, avg, max) = (8.241, 8.334, 8.519), stdev = 0.161
  CI (99.9%): [5.403, 11.264] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.227 ops/ms
# Warmup Iteration   2: 6.531 ops/ms
# Warmup Iteration   3: 8.107 ops/ms
Iteration   1: 7.755 ops/ms
Iteration   2: 8.044 ops/ms
Iteration   3: 8.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.003 ±(99.9%) 4.186 ops/ms [Average]
  (min, avg, max) = (7.755, 8.003, 8.208), stdev = 0.229
  CI (99.9%): [3.816, 12.189] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.063 ops/ms
# Warmup Iteration   2: 5.471 ops/ms
# Warmup Iteration   3: 6.570 ops/ms
Iteration   1: 6.529 ops/ms
Iteration   2: 6.754 ops/ms
Iteration   3: 6.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.725 ±(99.9%) 3.324 ops/ms [Average]
  (min, avg, max) = (6.529, 6.725, 6.890), stdev = 0.182
  CI (99.9%): [3.400, 10.049] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 12.878 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.715 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.308 ±(99.9%) 0.006 ms/op
Iteration   1: 3.883 ±(99.9%) 0.012 ms/op
Iteration   2: 3.820 ±(99.9%) 0.015 ms/op
Iteration   3: 3.856 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.853 ±(99.9%) 0.578 ms/op [Average]
  (min, avg, max) = (3.820, 3.853, 3.883), stdev = 0.032
  CI (99.9%): [3.275, 4.431] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 13.146 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.253 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.744 ±(99.9%) 0.011 ms/op
Iteration   1: 3.777 ±(99.9%) 0.006 ms/op
Iteration   2: 3.830 ±(99.9%) 0.008 ms/op
Iteration   3: 3.754 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.787 ±(99.9%) 0.720 ms/op [Average]
  (min, avg, max) = (3.754, 3.787, 3.830), stdev = 0.039
  CI (99.9%): [3.067, 4.507] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 11.777 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.473 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.069 ±(99.9%) 0.004 ms/op
Iteration   1: 3.925 ±(99.9%) 0.005 ms/op
Iteration   2: 4.004 ±(99.9%) 0.007 ms/op
Iteration   3: 3.941 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.957 ±(99.9%) 0.768 ms/op [Average]
  (min, avg, max) = (3.925, 3.957, 4.004), stdev = 0.042
  CI (99.9%): [3.189, 4.724] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.783 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.179 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.611 ±(99.9%) 0.010 ms/op
Iteration   1: 4.610 ±(99.9%) 0.012 ms/op
Iteration   2: 4.712 ±(99.9%) 0.008 ms/op
Iteration   3: 4.389 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.570 ±(99.9%) 3.015 ms/op [Average]
  (min, avg, max) = (4.389, 4.570, 4.712), stdev = 0.165
  CI (99.9%): [1.555, 7.585] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.997 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.708 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.314 ±(99.9%) 0.018 ms/op
Iteration   1: 3.959 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.925 ms/op
                 createUser·p0.50:   3.756 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   6.984 ms/op
                 createUser·p0.999:  23.003 ms/op
                 createUser·p0.9999: 26.444 ms/op
                 createUser·p1.00:   26.739 ms/op

Iteration   2: 3.843 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.542 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.548 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  25.199 ms/op
                 createUser·p0.9999: 27.122 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   3: 3.935 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.786 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   7.709 ms/op
                 createUser·p0.999:  25.821 ms/op
                 createUser·p0.9999: 30.302 ms/op
                 createUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 245150
  mean =      3.912 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 351 
    [ 2.500,  5.000) = 235160 
    [ 5.000,  7.500) = 7503 
    [ 7.500, 10.000) = 1526 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 161 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.542 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.229 ms/op
     p(99.9000) =     23.850 ms/op
     p(99.9900) =     28.687 ms/op
     p(99.9990) =     30.907 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.733 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.504 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.975 ±(99.9%) 0.013 ms/op
Iteration   1: 3.865 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.692 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   4.997 ms/op
                 existUser·p0.99:   7.389 ms/op
                 existUser·p0.999:  24.084 ms/op
                 existUser·p0.9999: 26.262 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   2: 3.777 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.145 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  12.572 ms/op
                 existUser·p0.9999: 26.151 ms/op
                 existUser·p1.00:   28.738 ms/op

Iteration   3: 3.810 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.862 ms/op
                 existUser·p0.50:   3.633 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   8.012 ms/op
                 existUser·p0.999:  19.201 ms/op
                 existUser·p0.9999: 30.900 ms/op
                 existUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251339
  mean =      3.817 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 251 
    [ 2.500,  5.000) = 241449 
    [ 5.000,  7.500) = 7253 
    [ 7.500, 10.000) = 1634 
    [10.000, 12.500) = 334 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     18.847 ms/op
     p(99.9900) =     30.208 ms/op
     p(99.9990) =     32.047 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.203 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.674 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.109 ±(99.9%) 0.017 ms/op
Iteration   1: 4.011 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.806 ms/op
                 getUser·p0.50:   3.789 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.382 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  21.537 ms/op
                 getUser·p0.9999: 24.740 ms/op
                 getUser·p1.00:   25.166 ms/op

Iteration   2: 3.913 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.968 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  25.926 ms/op
                 getUser·p0.9999: 31.818 ms/op
                 getUser·p1.00:   33.325 ms/op

Iteration   3: 3.953 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.501 ms/op
                 getUser·p0.50:   3.793 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   6.996 ms/op
                 getUser·p0.999:  12.322 ms/op
                 getUser·p0.9999: 29.491 ms/op
                 getUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 242440
  mean =      3.958 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 231090 
    [ 5.000,  7.500) = 9811 
    [ 7.500, 10.000) = 888 
    [10.000, 12.500) = 277 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.501 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     21.496 ms/op
     p(99.9900) =     30.335 ms/op
     p(99.9990) =     33.087 ms/op
     p(99.9999) =     33.325 ms/op
    p(100.0000) =     33.325 ms/op


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
# Warmup Iteration   1: 14.160 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 5.479 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.729 ±(99.9%) 0.015 ms/op
Iteration   1: 4.730 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.692 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   8.971 ms/op
                 listUser·p0.999:  22.658 ms/op
                 listUser·p0.9999: 24.395 ms/op
                 listUser·p1.00:   25.428 ms/op

Iteration   2: 4.704 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  17.466 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   3: 4.812 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.062 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   9.077 ms/op
                 listUser·p0.999:  18.285 ms/op
                 listUser·p0.9999: 21.606 ms/op
                 listUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201927
  mean =      4.748 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 166886 
    [ 5.000,  7.500) = 29365 
    [ 7.500, 10.000) = 4554 
    [10.000, 12.500) = 524 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.692 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      8.880 ms/op
     p(99.9000) =     19.237 ms/op
     p(99.9900) =     23.757 ms/op
     p(99.9990) =     25.355 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.933 ± 5.613  ops/ms
ClientPb.existUser                       thrpt       3   8.334 ± 2.931  ops/ms
ClientPb.getUser                         thrpt       3   8.003 ± 4.186  ops/ms
ClientPb.listUser                        thrpt       3   6.725 ± 3.324  ops/ms
ClientPb.createUser                       avgt       3   3.853 ± 0.578   ms/op
ClientPb.existUser                        avgt       3   3.787 ± 0.720   ms/op
ClientPb.getUser                          avgt       3   3.957 ± 0.768   ms/op
ClientPb.listUser                         avgt       3   4.570 ± 3.015   ms/op
ClientPb.createUser                     sample  245150   3.912 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.542           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.784           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.229           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.850           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.687           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.031           ms/op
ClientPb.existUser                      sample  251339   3.817 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.290           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.194           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.686           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.373           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.847           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.208           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.211           ms/op
ClientPb.getUser                        sample  242440   3.958 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.501           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.473           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.932           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.627           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.496           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.335           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.325           ms/op
ClientPb.listUser                       sample  201927   4.748 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.692           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.218           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.880           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.237           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.757           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.428           ms/op
