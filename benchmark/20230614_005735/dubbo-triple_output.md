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
# Warmup Iteration   1: 1.855 ops/ms
# Warmup Iteration   2: 3.656 ops/ms
# Warmup Iteration   3: 8.145 ops/ms
Iteration   1: 8.361 ops/ms
Iteration   2: 9.238 ops/ms
Iteration   3: 8.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.800 ±(99.9%) 8.001 ops/ms [Average]
  (min, avg, max) = (8.361, 8.800, 9.238), stdev = 0.439
  CI (99.9%): [0.800, 16.801] (assumes normal distribution)


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
# Warmup Iteration   1: 2.594 ops/ms
# Warmup Iteration   2: 7.916 ops/ms
# Warmup Iteration   3: 8.732 ops/ms
Iteration   1: 8.741 ops/ms
Iteration   2: 9.266 ops/ms
Iteration   3: 9.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.004 ±(99.9%) 4.791 ops/ms [Average]
  (min, avg, max) = (8.741, 9.004, 9.266), stdev = 0.263
  CI (99.9%): [4.214, 13.795] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.731 ops/ms
# Warmup Iteration   2: 7.235 ops/ms
# Warmup Iteration   3: 8.262 ops/ms
Iteration   1: 8.855 ops/ms
Iteration   2: 8.767 ops/ms
Iteration   3: 9.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.954 ±(99.9%) 4.609 ops/ms [Average]
  (min, avg, max) = (8.767, 8.954, 9.242), stdev = 0.253
  CI (99.9%): [4.345, 13.564] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.144 ops/ms
# Warmup Iteration   2: 6.082 ops/ms
# Warmup Iteration   3: 7.424 ops/ms
Iteration   1: 7.474 ops/ms
Iteration   2: 7.419 ops/ms
Iteration   3: 7.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.582 ±(99.9%) 4.305 ops/ms [Average]
  (min, avg, max) = (7.419, 7.582, 7.852), stdev = 0.236
  CI (99.9%): [3.277, 11.887] (assumes normal distribution)


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
# Warmup Iteration   1: 12.613 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.136 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.630 ±(99.9%) 0.006 ms/op
Iteration   1: 3.690 ±(99.9%) 0.005 ms/op
Iteration   2: 3.535 ±(99.9%) 0.004 ms/op
Iteration   3: 3.485 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.570 ±(99.9%) 1.942 ms/op [Average]
  (min, avg, max) = (3.485, 3.570, 3.690), stdev = 0.106
  CI (99.9%): [1.628, 5.513] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.197 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.166 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.561 ±(99.9%) 0.007 ms/op
Iteration   1: 3.476 ±(99.9%) 0.010 ms/op
Iteration   2: 3.444 ±(99.9%) 0.005 ms/op
Iteration   3: 3.459 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.460 ±(99.9%) 0.297 ms/op [Average]
  (min, avg, max) = (3.444, 3.460, 3.476), stdev = 0.016
  CI (99.9%): [3.163, 3.757] (assumes normal distribution)


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
# Warmup Iteration   1: 13.009 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.316 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.704 ±(99.9%) 0.007 ms/op
Iteration   1: 3.738 ±(99.9%) 0.005 ms/op
Iteration   2: 3.620 ±(99.9%) 0.008 ms/op
Iteration   3: 3.565 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.641 ±(99.9%) 1.605 ms/op [Average]
  (min, avg, max) = (3.565, 3.641, 3.738), stdev = 0.088
  CI (99.9%): [2.036, 5.246] (assumes normal distribution)


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
# Warmup Iteration   1: 13.041 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.818 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.233 ±(99.9%) 0.012 ms/op
Iteration   1: 4.272 ±(99.9%) 0.009 ms/op
Iteration   2: 4.110 ±(99.9%) 0.013 ms/op
Iteration   3: 4.171 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.184 ±(99.9%) 1.495 ms/op [Average]
  (min, avg, max) = (4.110, 4.184, 4.272), stdev = 0.082
  CI (99.9%): [2.690, 5.679] (assumes normal distribution)


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
# Warmup Iteration   1: 10.564 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.636 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.017 ms/op
Iteration   1: 3.646 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.706 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  26.814 ms/op
                 createUser·p0.9999: 30.479 ms/op
                 createUser·p1.00:   31.097 ms/op

Iteration   2: 3.579 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.917 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  26.101 ms/op
                 createUser·p0.9999: 30.050 ms/op
                 createUser·p1.00:   30.540 ms/op

Iteration   3: 3.532 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.282 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   6.087 ms/op
                 createUser·p0.999:  23.150 ms/op
                 createUser·p0.9999: 33.256 ms/op
                 createUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267703
  mean =      3.585 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3199 
    [ 2.500,  5.000) = 256262 
    [ 5.000,  7.500) = 6785 
    [ 7.500, 10.000) = 829 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 123 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     23.963 ms/op
     p(99.9900) =     32.178 ms/op
     p(99.9990) =     34.096 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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
# Warmup Iteration   1: 10.913 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 3.862 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.012 ms/op
Iteration   1: 3.411 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.782 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  10.645 ms/op
                 existUser·p0.9999: 31.125 ms/op
                 existUser·p1.00:   31.949 ms/op

Iteration   2: 3.448 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.784 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  26.270 ms/op
                 existUser·p0.9999: 30.252 ms/op
                 existUser·p1.00:   30.671 ms/op

Iteration   3: 3.570 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.317 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.656 ms/op
                 existUser·p0.99:   7.127 ms/op
                 existUser·p0.999:  29.579 ms/op
                 existUser·p0.9999: 38.800 ms/op
                 existUser·p1.00:   41.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 275950
  mean =      3.475 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 268613 
    [ 5.000, 10.000) = 6848 
    [10.000, 15.000) = 180 
    [15.000, 20.000) = 53 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 136 
    [30.000, 35.000) = 56 
    [35.000, 40.000) = 63 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.345 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     15.958 ms/op
     p(99.9900) =     37.986 ms/op
     p(99.9990) =     39.222 ms/op
     p(99.9999) =     41.157 ms/op
    p(100.0000) =     41.157 ms/op


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
# Warmup Iteration   1: 11.208 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.693 ±(99.9%) 0.013 ms/op
Iteration   1: 3.958 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.716 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   5.947 ms/op
                 getUser·p0.99:   8.282 ms/op
                 getUser·p0.999:  24.975 ms/op
                 getUser·p0.9999: 33.093 ms/op
                 getUser·p1.00:   34.537 ms/op

Iteration   2: 3.850 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   3.584 ms/op
                 getUser·p0.90:   4.735 ms/op
                 getUser·p0.95:   5.816 ms/op
                 getUser·p0.99:   8.323 ms/op
                 getUser·p0.999:  12.222 ms/op
                 getUser·p0.9999: 38.339 ms/op
                 getUser·p1.00:   39.846 ms/op

Iteration   3: 3.614 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   5.153 ms/op
                 getUser·p0.99:   7.381 ms/op
                 getUser·p0.999:  29.360 ms/op
                 getUser·p0.9999: 32.077 ms/op
                 getUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 252363
  mean =      3.802 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2161 
    [ 2.500,  5.000) = 231530 
    [ 5.000,  7.500) = 15380 
    [ 7.500, 10.000) = 2545 
    [10.000, 12.500) = 317 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 100 
    [32.500, 35.000) = 38 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      7.875 ms/op
     p(99.9000) =     24.379 ms/op
     p(99.9900) =     34.537 ms/op
     p(99.9990) =     39.400 ms/op
     p(99.9999) =     39.846 ms/op
    p(100.0000) =     39.846 ms/op


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
# Warmup Iteration   1: 13.131 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.756 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.299 ±(99.9%) 0.017 ms/op
Iteration   1: 4.258 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   8.044 ms/op
                 listUser·p0.999:  27.423 ms/op
                 listUser·p0.9999: 31.768 ms/op
                 listUser·p1.00:   32.309 ms/op

Iteration   2: 4.274 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.509 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  19.202 ms/op
                 listUser·p0.9999: 23.757 ms/op
                 listUser·p1.00:   24.609 ms/op

Iteration   3: 4.175 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  18.514 ms/op
                 listUser·p0.9999: 20.404 ms/op
                 listUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226443
  mean =      4.235 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 212359 
    [ 5.000,  7.500) = 10695 
    [ 7.500, 10.000) = 2114 
    [10.000, 12.500) = 527 
    [12.500, 15.000) = 256 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      4.039 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      8.200 ms/op
     p(99.9000) =     20.316 ms/op
     p(99.9900) =     30.912 ms/op
     p(99.9990) =     32.063 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.800 ± 8.001  ops/ms
ClientPb.existUser                       thrpt       3   9.004 ± 4.791  ops/ms
ClientPb.getUser                         thrpt       3   8.954 ± 4.609  ops/ms
ClientPb.listUser                        thrpt       3   7.582 ± 4.305  ops/ms
ClientPb.createUser                       avgt       3   3.570 ± 1.942   ms/op
ClientPb.existUser                        avgt       3   3.460 ± 0.297   ms/op
ClientPb.getUser                          avgt       3   3.641 ± 1.605   ms/op
ClientPb.listUser                         avgt       3   4.184 ± 1.495   ms/op
ClientPb.createUser                     sample  267703   3.585 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.282           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.506           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.226           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.963           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.178           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.734           ms/op
ClientPb.existUser                      sample  275950   3.475 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.317           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.359           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.345           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.193           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.958           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.986           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.157           ms/op
ClientPb.getUser                        sample  252363   3.802 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.243           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.551           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.563           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.718           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.875           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.379           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.537           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.846           ms/op
ClientPb.listUser                       sample  226443   4.235 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.870           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.218           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.200           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.316           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.912           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.309           ms/op
