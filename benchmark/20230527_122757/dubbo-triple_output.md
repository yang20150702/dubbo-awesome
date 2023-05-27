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
# Warmup Iteration   1: 2.231 ops/ms
# Warmup Iteration   2: 5.400 ops/ms
# Warmup Iteration   3: 8.702 ops/ms
Iteration   1: 8.984 ops/ms
Iteration   2: 9.336 ops/ms
Iteration   3: 9.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.222 ±(99.9%) 3.763 ops/ms [Average]
  (min, avg, max) = (8.984, 9.222, 9.347), stdev = 0.206
  CI (99.9%): [5.459, 12.986] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.188 ops/ms
# Warmup Iteration   2: 8.540 ops/ms
# Warmup Iteration   3: 9.750 ops/ms
Iteration   1: 10.042 ops/ms
Iteration   2: 9.865 ops/ms
Iteration   3: 10.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.004 ±(99.9%) 2.278 ops/ms [Average]
  (min, avg, max) = (9.865, 10.004, 10.106), stdev = 0.125
  CI (99.9%): [7.726, 12.282] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.647 ops/ms
# Warmup Iteration   2: 8.416 ops/ms
# Warmup Iteration   3: 8.955 ops/ms
Iteration   1: 9.416 ops/ms
Iteration   2: 9.283 ops/ms
Iteration   3: 9.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.466 ±(99.9%) 3.891 ops/ms [Average]
  (min, avg, max) = (9.283, 9.466, 9.700), stdev = 0.213
  CI (99.9%): [5.575, 13.358] (assumes normal distribution)


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
# Warmup Iteration   1: 2.800 ops/ms
# Warmup Iteration   2: 6.930 ops/ms
# Warmup Iteration   3: 7.851 ops/ms
Iteration   1: 7.955 ops/ms
Iteration   2: 8.230 ops/ms
Iteration   3: 7.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.051 ±(99.9%) 2.819 ops/ms [Average]
  (min, avg, max) = (7.955, 8.051, 8.230), stdev = 0.155
  CI (99.9%): [5.232, 10.870] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.165 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.007 ms/op
Iteration   1: 3.371 ±(99.9%) 0.007 ms/op
Iteration   2: 3.280 ±(99.9%) 0.012 ms/op
Iteration   3: 3.258 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.303 ±(99.9%) 1.094 ms/op [Average]
  (min, avg, max) = (3.258, 3.303, 3.371), stdev = 0.060
  CI (99.9%): [2.209, 4.397] (assumes normal distribution)


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
# Warmup Iteration   1: 8.283 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.481 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.011 ms/op
Iteration   1: 3.409 ±(99.9%) 0.003 ms/op
Iteration   2: 3.241 ±(99.9%) 0.007 ms/op
Iteration   3: 3.261 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.304 ±(99.9%) 1.678 ms/op [Average]
  (min, avg, max) = (3.241, 3.304, 3.409), stdev = 0.092
  CI (99.9%): [1.625, 4.982] (assumes normal distribution)


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
# Warmup Iteration   1: 10.196 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.896 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.005 ms/op
Iteration   1: 3.321 ±(99.9%) 0.007 ms/op
Iteration   2: 3.256 ±(99.9%) 0.007 ms/op
Iteration   3: 3.388 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.322 ±(99.9%) 1.205 ms/op [Average]
  (min, avg, max) = (3.256, 3.322, 3.388), stdev = 0.066
  CI (99.9%): [2.117, 4.527] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.818 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.278 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.010 ms/op
Iteration   1: 4.113 ±(99.9%) 0.004 ms/op
Iteration   2: 4.020 ±(99.9%) 0.009 ms/op
Iteration   3: 3.969 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.034 ±(99.9%) 1.329 ms/op [Average]
  (min, avg, max) = (3.969, 4.034, 4.113), stdev = 0.073
  CI (99.9%): [2.704, 5.363] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.966 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.156 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.762 ±(99.9%) 0.014 ms/op
Iteration   1: 3.476 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.276 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   7.045 ms/op
                 createUser·p0.999:  20.413 ms/op
                 createUser·p0.9999: 23.449 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   2: 3.404 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.499 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  21.923 ms/op
                 createUser·p0.9999: 30.121 ms/op
                 createUser·p1.00:   31.228 ms/op

Iteration   3: 3.339 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  20.446 ms/op
                 createUser·p0.9999: 25.704 ms/op
                 createUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281717
  mean =      3.405 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6194 
    [ 2.500,  5.000) = 268293 
    [ 5.000,  7.500) = 5968 
    [ 7.500, 10.000) = 833 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     20.447 ms/op
     p(99.9900) =     28.765 ms/op
     p(99.9990) =     30.787 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.465 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.567 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.378 ±(99.9%) 0.009 ms/op
Iteration   1: 3.266 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.333 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  12.354 ms/op
                 existUser·p0.9999: 24.936 ms/op
                 existUser·p1.00:   25.821 ms/op

Iteration   2: 3.258 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.806 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  10.544 ms/op
                 existUser·p0.9999: 24.424 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   3: 3.267 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  13.107 ms/op
                 existUser·p0.9999: 24.255 ms/op
                 existUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294015
  mean =      3.264 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16007 
    [ 2.500,  5.000) = 274008 
    [ 5.000,  7.500) = 3158 
    [ 7.500, 10.000) = 489 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 134 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     13.107 ms/op
     p(99.9900) =     24.478 ms/op
     p(99.9990) =     25.463 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.094 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.901 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.542 ±(99.9%) 0.010 ms/op
Iteration   1: 3.469 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.336 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.728 ms/op
                 getUser·p0.99:   6.624 ms/op
                 getUser·p0.999:  14.922 ms/op
                 getUser·p0.9999: 20.702 ms/op
                 getUser·p1.00:   21.692 ms/op

Iteration   2: 3.358 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.720 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  20.713 ms/op
                 getUser·p0.9999: 29.753 ms/op
                 getUser·p1.00:   30.310 ms/op

Iteration   3: 3.330 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  17.844 ms/op
                 getUser·p0.9999: 24.620 ms/op
                 getUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283619
  mean =      3.385 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6653 
    [ 2.500,  5.000) = 268900 
    [ 5.000,  7.500) = 6792 
    [ 7.500, 10.000) = 812 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.336 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     18.789 ms/op
     p(99.9900) =     28.779 ms/op
     p(99.9990) =     30.660 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.426 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.469 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.022 ±(99.9%) 0.012 ms/op
Iteration   1: 3.891 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  18.637 ms/op
                 listUser·p0.9999: 21.809 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   2: 3.881 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.481 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  15.794 ms/op
                 listUser·p0.9999: 20.547 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   3: 4.001 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.933 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   7.731 ms/op
                 listUser·p0.999:  14.305 ms/op
                 listUser·p0.9999: 16.942 ms/op
                 listUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244484
  mean =      3.924 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 235883 
    [ 5.000,  7.500) = 6438 
    [ 7.500, 10.000) = 1347 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.161 ms/op
     p(99.9000) =     15.581 ms/op
     p(99.9900) =     21.157 ms/op
     p(99.9990) =     22.271 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.222 ± 3.763  ops/ms
ClientPb.existUser                       thrpt       3  10.004 ± 2.278  ops/ms
ClientPb.getUser                         thrpt       3   9.466 ± 3.891  ops/ms
ClientPb.listUser                        thrpt       3   8.051 ± 2.819  ops/ms
ClientPb.createUser                       avgt       3   3.303 ± 1.094   ms/op
ClientPb.existUser                        avgt       3   3.304 ± 1.678   ms/op
ClientPb.getUser                          avgt       3   3.322 ± 1.205   ms/op
ClientPb.listUser                         avgt       3   4.034 ± 1.329   ms/op
ClientPb.createUser                     sample  281717   3.405 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.094           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.054           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.447           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.765           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.228           ms/op
ClientPb.existUser                      sample  294015   3.264 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.855           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.513           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.107           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.478           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.821           ms/op
ClientPb.getUser                        sample  283619   3.385 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.336           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.740           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.063           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.160           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.789           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.779           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.769           ms/op
ClientPb.listUser                       sample  244484   3.924 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.278           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.793           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.161           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.581           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.157           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.348           ms/op
