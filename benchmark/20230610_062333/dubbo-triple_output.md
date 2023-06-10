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
# Warmup Iteration   1: 1.981 ops/ms
# Warmup Iteration   2: 5.212 ops/ms
# Warmup Iteration   3: 8.437 ops/ms
Iteration   1: 9.041 ops/ms
Iteration   2: 9.385 ops/ms
Iteration   3: 9.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.317 ±(99.9%) 4.534 ops/ms [Average]
  (min, avg, max) = (9.041, 9.317, 9.524), stdev = 0.249
  CI (99.9%): [4.783, 13.851] (assumes normal distribution)


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
# Warmup Iteration   1: 2.952 ops/ms
# Warmup Iteration   2: 9.024 ops/ms
# Warmup Iteration   3: 9.827 ops/ms
Iteration   1: 9.865 ops/ms
Iteration   2: 9.936 ops/ms
Iteration   3: 9.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.842 ±(99.9%) 1.965 ops/ms [Average]
  (min, avg, max) = (9.725, 9.842, 9.936), stdev = 0.108
  CI (99.9%): [7.877, 11.807] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.909 ops/ms
# Warmup Iteration   2: 7.974 ops/ms
# Warmup Iteration   3: 9.250 ops/ms
Iteration   1: 9.434 ops/ms
Iteration   2: 9.375 ops/ms
Iteration   3: 9.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.463 ±(99.9%) 1.915 ops/ms [Average]
  (min, avg, max) = (9.375, 9.463, 9.579), stdev = 0.105
  CI (99.9%): [7.547, 11.378] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.727 ops/ms
# Warmup Iteration   2: 7.375 ops/ms
# Warmup Iteration   3: 7.704 ops/ms
Iteration   1: 7.942 ops/ms
Iteration   2: 7.844 ops/ms
Iteration   3: 7.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.921 ±(99.9%) 1.263 ops/ms [Average]
  (min, avg, max) = (7.844, 7.921, 7.978), stdev = 0.069
  CI (99.9%): [6.658, 9.185] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.627 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.765 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.650 ±(99.9%) 0.005 ms/op
Iteration   1: 3.462 ±(99.9%) 0.006 ms/op
Iteration   2: 3.456 ±(99.9%) 0.005 ms/op
Iteration   3: 3.477 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.465 ±(99.9%) 0.205 ms/op [Average]
  (min, avg, max) = (3.456, 3.465, 3.477), stdev = 0.011
  CI (99.9%): [3.260, 3.670] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 9.867 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.007 ms/op
Iteration   1: 3.278 ±(99.9%) 0.008 ms/op
Iteration   2: 3.412 ±(99.9%) 0.004 ms/op
Iteration   3: 3.549 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.413 ±(99.9%) 2.470 ms/op [Average]
  (min, avg, max) = (3.278, 3.413, 3.549), stdev = 0.135
  CI (99.9%): [0.943, 5.883] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 10.129 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.246 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.007 ms/op
Iteration   1: 4.066 ±(99.9%) 0.006 ms/op
Iteration   2: 3.905 ±(99.9%) 0.005 ms/op
Iteration   3: 4.006 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.992 ±(99.9%) 1.487 ms/op [Average]
  (min, avg, max) = (3.905, 3.992, 4.066), stdev = 0.081
  CI (99.9%): [2.506, 5.479] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 14.687 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.436 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.599 ±(99.9%) 0.010 ms/op
Iteration   1: 4.495 ±(99.9%) 0.008 ms/op
Iteration   2: 4.421 ±(99.9%) 0.016 ms/op
Iteration   3: 4.260 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.392 ±(99.9%) 2.195 ms/op [Average]
  (min, avg, max) = (4.260, 4.392, 4.495), stdev = 0.120
  CI (99.9%): [2.197, 6.587] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 14.021 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 4.924 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.022 ±(99.9%) 0.018 ms/op
Iteration   1: 3.503 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.702 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.521 ms/op
                 createUser·p0.999:  23.200 ms/op
                 createUser·p0.9999: 35.521 ms/op
                 createUser·p1.00:   36.766 ms/op

Iteration   2: 3.557 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.497 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  22.228 ms/op
                 createUser·p0.9999: 31.069 ms/op
                 createUser·p1.00:   32.702 ms/op

Iteration   3: 3.366 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.565 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   6.586 ms/op
                 createUser·p0.999:  23.753 ms/op
                 createUser·p0.9999: 30.768 ms/op
                 createUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276276
  mean =      3.473 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5860 
    [ 2.500,  5.000) = 263551 
    [ 5.000,  7.500) = 5062 
    [ 7.500, 10.000) = 1115 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     22.404 ms/op
     p(99.9900) =     34.079 ms/op
     p(99.9990) =     36.650 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.432 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 3.557 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.010 ms/op
Iteration   1: 3.300 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.464 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   4.129 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  12.807 ms/op
                 existUser·p0.9999: 26.877 ms/op
                 existUser·p1.00:   27.591 ms/op

Iteration   2: 3.350 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.810 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  10.502 ms/op
                 existUser·p0.9999: 27.212 ms/op
                 existUser·p1.00:   28.180 ms/op

Iteration   3: 3.388 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.468 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  22.467 ms/op
                 existUser·p0.9999: 30.835 ms/op
                 existUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286733
  mean =      3.345 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11438 
    [ 2.500,  5.000) = 269618 
    [ 5.000,  7.500) = 4516 
    [ 7.500, 10.000) = 500 
    [10.000, 12.500) = 310 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 110 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.464 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     29.414 ms/op
     p(99.9990) =     31.901 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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
# Warmup Iteration   1: 11.414 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.365 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.569 ±(99.9%) 0.010 ms/op
Iteration   1: 3.635 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.657 ms/op
                 getUser·p0.50:   3.478 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   7.578 ms/op
                 getUser·p0.999:  22.047 ms/op
                 getUser·p0.9999: 25.500 ms/op
                 getUser·p1.00:   26.935 ms/op

Iteration   2: 3.449 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   2.075 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  10.777 ms/op
                 getUser·p0.9999: 28.089 ms/op
                 getUser·p1.00:   28.508 ms/op

Iteration   3: 3.428 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.019 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  23.438 ms/op
                 getUser·p0.9999: 35.324 ms/op
                 getUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274141
  mean =      3.502 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7599 
    [ 2.500,  5.000) = 258021 
    [ 5.000,  7.500) = 6794 
    [ 7.500, 10.000) = 1301 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.657 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     14.334 ms/op
     p(99.9900) =     34.013 ms/op
     p(99.9990) =     35.979 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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
# Warmup Iteration   1: 12.455 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.592 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.212 ±(99.9%) 0.015 ms/op
Iteration   1: 4.221 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.872 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  22.920 ms/op
                 listUser·p0.9999: 26.049 ms/op
                 listUser·p1.00:   26.706 ms/op

Iteration   2: 4.062 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.921 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.963 ms/op
                 listUser·p0.999:  15.122 ms/op
                 listUser·p0.9999: 18.170 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   3: 4.009 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  15.254 ms/op
                 listUser·p0.9999: 16.089 ms/op
                 listUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234246
  mean =      4.095 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 224010 
    [ 5.000,  7.500) = 7700 
    [ 7.500, 10.000) = 1511 
    [10.000, 12.500) = 412 
    [12.500, 15.000) = 208 
    [15.000, 17.500) = 215 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.872 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.668 ms/op
     p(99.9000) =     15.712 ms/op
     p(99.9900) =     24.974 ms/op
     p(99.9990) =     26.585 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.317 ± 4.534  ops/ms
ClientPb.existUser                       thrpt       3   9.842 ± 1.965  ops/ms
ClientPb.getUser                         thrpt       3   9.463 ± 1.915  ops/ms
ClientPb.listUser                        thrpt       3   7.921 ± 1.263  ops/ms
ClientPb.createUser                       avgt       3   3.465 ± 0.205   ms/op
ClientPb.existUser                        avgt       3   3.413 ± 2.470   ms/op
ClientPb.getUser                          avgt       3   3.992 ± 1.487   ms/op
ClientPb.listUser                         avgt       3   4.392 ± 2.195   ms/op
ClientPb.createUser                     sample  276276   3.473 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.497           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.455           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.404           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.079           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.766           ms/op
ClientPb.existUser                      sample  286733   3.345 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.464           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.108           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.792           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.713           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.414           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.375           ms/op
ClientPb.getUser                        sample  274141   3.502 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.657           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.396           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.350           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.545           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.334           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.013           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.979           ms/op
ClientPb.listUser                       sample  234246   4.095 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.872           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.668           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.712           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.974           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.706           ms/op
