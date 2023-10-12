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
# Warmup Iteration   1: 1.832 ops/ms
# Warmup Iteration   2: 5.569 ops/ms
# Warmup Iteration   3: 8.587 ops/ms
Iteration   1: 8.861 ops/ms
Iteration   2: 9.257 ops/ms
Iteration   3: 9.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.111 ±(99.9%) 3.974 ops/ms [Average]
  (min, avg, max) = (8.861, 9.111, 9.257), stdev = 0.218
  CI (99.9%): [5.137, 13.085] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.717 ops/ms
# Warmup Iteration   2: 8.713 ops/ms
# Warmup Iteration   3: 9.278 ops/ms
Iteration   1: 9.400 ops/ms
Iteration   2: 9.716 ops/ms
Iteration   3: 9.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.565 ±(99.9%) 2.885 ops/ms [Average]
  (min, avg, max) = (9.400, 9.565, 9.716), stdev = 0.158
  CI (99.9%): [6.680, 12.450] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.737 ops/ms
# Warmup Iteration   2: 8.462 ops/ms
# Warmup Iteration   3: 8.967 ops/ms
Iteration   1: 8.909 ops/ms
Iteration   2: 9.266 ops/ms
Iteration   3: 9.228 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.134 ±(99.9%) 3.580 ops/ms [Average]
  (min, avg, max) = (8.909, 9.134, 9.266), stdev = 0.196
  CI (99.9%): [5.554, 12.715] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.657 ops/ms
# Warmup Iteration   2: 6.769 ops/ms
# Warmup Iteration   3: 7.621 ops/ms
Iteration   1: 7.626 ops/ms
Iteration   2: 7.749 ops/ms
Iteration   3: 7.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.754 ±(99.9%) 2.384 ops/ms [Average]
  (min, avg, max) = (7.626, 7.754, 7.888), stdev = 0.131
  CI (99.9%): [5.371, 10.138] (assumes normal distribution)


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
# Warmup Iteration   1: 9.234 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.657 ±(99.9%) 0.003 ms/op
Iteration   1: 3.510 ±(99.9%) 0.003 ms/op
Iteration   2: 3.563 ±(99.9%) 0.004 ms/op
Iteration   3: 3.528 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.534 ±(99.9%) 0.498 ms/op [Average]
  (min, avg, max) = (3.510, 3.534, 3.563), stdev = 0.027
  CI (99.9%): [3.035, 4.032] (assumes normal distribution)


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
# Warmup Iteration   1: 9.757 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.003 ms/op
Iteration   1: 3.388 ±(99.9%) 0.007 ms/op
Iteration   2: 3.427 ±(99.9%) 0.003 ms/op
Iteration   3: 3.427 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.414 ±(99.9%) 0.404 ms/op [Average]
  (min, avg, max) = (3.388, 3.414, 3.427), stdev = 0.022
  CI (99.9%): [3.010, 3.818] (assumes normal distribution)


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
# Warmup Iteration   1: 8.780 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.736 ±(99.9%) 0.004 ms/op
Iteration   1: 3.494 ±(99.9%) 0.005 ms/op
Iteration   2: 3.565 ±(99.9%) 0.004 ms/op
Iteration   3: 3.495 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.518 ±(99.9%) 0.746 ms/op [Average]
  (min, avg, max) = (3.494, 3.518, 3.565), stdev = 0.041
  CI (99.9%): [2.772, 4.264] (assumes normal distribution)


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
# Warmup Iteration   1: 12.165 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.600 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.222 ±(99.9%) 0.009 ms/op
Iteration   1: 4.336 ±(99.9%) 0.007 ms/op
Iteration   2: 4.218 ±(99.9%) 0.005 ms/op
Iteration   3: 4.163 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.239 ±(99.9%) 1.611 ms/op [Average]
  (min, avg, max) = (4.163, 4.239, 4.336), stdev = 0.088
  CI (99.9%): [2.628, 5.849] (assumes normal distribution)


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
# Warmup Iteration   1: 8.686 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.026 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.013 ms/op
Iteration   1: 3.620 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.778 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.922 ms/op
                 createUser·p0.999:  12.970 ms/op
                 createUser·p0.9999: 23.451 ms/op
                 createUser·p1.00:   24.609 ms/op

Iteration   2: 3.469 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.493 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   6.711 ms/op
                 createUser·p0.999:  24.138 ms/op
                 createUser·p0.9999: 26.993 ms/op
                 createUser·p1.00:   28.180 ms/op

Iteration   3: 3.600 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.612 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   7.250 ms/op
                 createUser·p0.999:  23.694 ms/op
                 createUser·p0.9999: 28.086 ms/op
                 createUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269649
  mean =      3.562 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3110 
    [ 2.500,  5.000) = 256827 
    [ 5.000,  7.500) = 8038 
    [ 7.500, 10.000) = 1024 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 112 

  Percentiles, ms/op:
      p(0.0000) =      1.493 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     22.130 ms/op
     p(99.9900) =     27.304 ms/op
     p(99.9990) =     28.364 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


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
# Warmup Iteration   1: 8.965 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.664 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.424 ±(99.9%) 0.010 ms/op
Iteration   1: 3.350 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.135 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   6.269 ms/op
                 existUser·p0.999:  10.994 ms/op
                 existUser·p0.9999: 29.241 ms/op
                 existUser·p1.00:   30.638 ms/op

Iteration   2: 3.407 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.567 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   6.988 ms/op
                 existUser·p0.999:  23.837 ms/op
                 existUser·p0.9999: 26.837 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   3: 3.480 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.773 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   7.168 ms/op
                 existUser·p0.999:  23.265 ms/op
                 existUser·p0.9999: 27.263 ms/op
                 existUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281174
  mean =      3.412 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7104 
    [ 2.500,  5.000) = 263339 
    [ 5.000,  7.500) = 9082 
    [ 7.500, 10.000) = 979 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     21.037 ms/op
     p(99.9900) =     27.591 ms/op
     p(99.9990) =     30.585 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


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
# Warmup Iteration   1: 10.261 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.012 ms/op
Iteration   1: 3.581 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.307 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  21.746 ms/op
                 getUser·p0.9999: 24.054 ms/op
                 getUser·p1.00:   25.199 ms/op

Iteration   2: 3.523 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.667 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   7.430 ms/op
                 getUser·p0.999:  23.797 ms/op
                 getUser·p0.9999: 25.985 ms/op
                 getUser·p1.00:   31.883 ms/op

Iteration   3: 3.524 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.403 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.632 ms/op
                 getUser·p0.999:  18.424 ms/op
                 getUser·p0.9999: 26.890 ms/op
                 getUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270876
  mean =      3.542 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3178 
    [ 2.500,  5.000) = 258992 
    [ 5.000,  7.500) = 6839 
    [ 7.500, 10.000) = 1213 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 166 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     21.729 ms/op
     p(99.9900) =     26.182 ms/op
     p(99.9990) =     29.068 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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
# Warmup Iteration   1: 11.173 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.456 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.457 ±(99.9%) 0.016 ms/op
Iteration   1: 4.301 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.886 ms/op
                 listUser·p0.50:   4.129 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   8.208 ms/op
                 listUser·p0.999:  21.224 ms/op
                 listUser·p0.9999: 24.824 ms/op
                 listUser·p1.00:   26.182 ms/op

Iteration   2: 4.244 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 18.785 ms/op
                 listUser·p1.00:   22.577 ms/op

Iteration   3: 4.329 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.688 ms/op
                 listUser·p0.50:   4.100 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  16.451 ms/op
                 listUser·p0.9999: 20.921 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 223485
  mean =      4.291 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 97 
    [ 2.500,  5.000) = 209274 
    [ 5.000,  7.500) = 10117 
    [ 7.500, 10.000) = 2839 
    [10.000, 12.500) = 319 
    [12.500, 15.000) = 382 
    [15.000, 17.500) = 235 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.688 ms/op
     p(50.0000) =      4.096 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.265 ms/op
     p(99.0000) =      8.522 ms/op
     p(99.9000) =     17.466 ms/op
     p(99.9900) =     23.582 ms/op
     p(99.9990) =     25.554 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.111 ± 3.974  ops/ms
ClientPb.existUser                       thrpt       3   9.565 ± 2.885  ops/ms
ClientPb.getUser                         thrpt       3   9.134 ± 3.580  ops/ms
ClientPb.listUser                        thrpt       3   7.754 ± 2.384  ops/ms
ClientPb.createUser                       avgt       3   3.534 ± 0.498   ms/op
ClientPb.existUser                        avgt       3   3.414 ± 0.404   ms/op
ClientPb.getUser                          avgt       3   3.518 ± 0.746   ms/op
ClientPb.listUser                         avgt       3   4.239 ± 1.611   ms/op
ClientPb.createUser                     sample  269649   3.562 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.493           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.371           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.465           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.971           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.130           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.304           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.491           ms/op
ClientPb.existUser                      sample  281174   3.412 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.773           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.971           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.037           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.591           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.638           ms/op
ClientPb.getUser                        sample  270876   3.542 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.307           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.086           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.729           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.182           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.883           ms/op
ClientPb.listUser                       sample  223485   4.291 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.688           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.096           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.265           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.522           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.466           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.582           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.182           ms/op
