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
# Warmup Iteration   1: 1.234 ops/ms
# Warmup Iteration   2: 2.900 ops/ms
# Warmup Iteration   3: 5.526 ops/ms
Iteration   1: 5.549 ops/ms
Iteration   2: 6.122 ops/ms
Iteration   3: 6.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.922 ±(99.9%) 5.897 ops/ms [Average]
  (min, avg, max) = (5.549, 5.922, 6.122), stdev = 0.323
  CI (99.9%): [0.025, 11.819] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.651 ops/ms
# Warmup Iteration   2: 4.844 ops/ms
# Warmup Iteration   3: 6.048 ops/ms
Iteration   1: 6.344 ops/ms
Iteration   2: 6.118 ops/ms
Iteration   3: 6.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.215 ±(99.9%) 2.113 ops/ms [Average]
  (min, avg, max) = (6.118, 6.215, 6.344), stdev = 0.116
  CI (99.9%): [4.103, 8.328] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.646 ops/ms
# Warmup Iteration   2: 4.691 ops/ms
# Warmup Iteration   3: 5.682 ops/ms
Iteration   1: 5.843 ops/ms
Iteration   2: 6.013 ops/ms
Iteration   3: 6.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.977 ±(99.9%) 2.192 ops/ms [Average]
  (min, avg, max) = (5.843, 5.977, 6.075), stdev = 0.120
  CI (99.9%): [3.784, 8.169] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.678 ops/ms
# Warmup Iteration   2: 4.151 ops/ms
# Warmup Iteration   3: 5.046 ops/ms
Iteration   1: 4.992 ops/ms
Iteration   2: 5.348 ops/ms
Iteration   3: 5.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.168 ±(99.9%) 3.250 ops/ms [Average]
  (min, avg, max) = (4.992, 5.168, 5.348), stdev = 0.178
  CI (99.9%): [1.918, 8.418] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 17.081 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.319 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.667 ±(99.9%) 0.011 ms/op
Iteration   1: 5.338 ±(99.9%) 0.015 ms/op
Iteration   2: 5.532 ±(99.9%) 0.011 ms/op
Iteration   3: 5.535 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.468 ±(99.9%) 2.058 ms/op [Average]
  (min, avg, max) = (5.338, 5.468, 5.535), stdev = 0.113
  CI (99.9%): [3.410, 7.526] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 16.578 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 6.246 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.356 ±(99.9%) 0.006 ms/op
Iteration   1: 5.369 ±(99.9%) 0.008 ms/op
Iteration   2: 5.212 ±(99.9%) 0.008 ms/op
Iteration   3: 5.129 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.237 ±(99.9%) 2.222 ms/op [Average]
  (min, avg, max) = (5.129, 5.237, 5.369), stdev = 0.122
  CI (99.9%): [3.015, 7.459] (assumes normal distribution)


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
# Warmup Iteration   1: 15.616 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.824 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.388 ±(99.9%) 0.012 ms/op
Iteration   1: 5.335 ±(99.9%) 0.017 ms/op
Iteration   2: 5.700 ±(99.9%) 0.015 ms/op
Iteration   3: 5.481 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.505 ±(99.9%) 3.349 ms/op [Average]
  (min, avg, max) = (5.335, 5.505, 5.700), stdev = 0.184
  CI (99.9%): [2.156, 8.854] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 19.050 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 7.680 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.349 ±(99.9%) 0.018 ms/op
Iteration   1: 6.088 ±(99.9%) 0.027 ms/op
Iteration   2: 6.486 ±(99.9%) 0.012 ms/op
Iteration   3: 6.270 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.281 ±(99.9%) 3.638 ms/op [Average]
  (min, avg, max) = (6.088, 6.281, 6.486), stdev = 0.199
  CI (99.9%): [2.643, 9.919] (assumes normal distribution)


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
# Warmup Iteration   1: 16.610 ±(99.9%) 0.266 ms/op
# Warmup Iteration   2: 6.800 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.886 ±(99.9%) 0.026 ms/op
Iteration   1: 5.369 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.503 ms/op
                 createUser·p0.50:   5.161 ms/op
                 createUser·p0.90:   6.390 ms/op
                 createUser·p0.95:   7.651 ms/op
                 createUser·p0.99:   9.716 ms/op
                 createUser·p0.999:  24.160 ms/op
                 createUser·p0.9999: 29.756 ms/op
                 createUser·p1.00:   30.081 ms/op

Iteration   2: 5.691 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   5.333 ms/op
                 createUser·p0.90:   7.504 ms/op
                 createUser·p0.95:   8.602 ms/op
                 createUser·p0.99:   11.321 ms/op
                 createUser·p0.999:  21.620 ms/op
                 createUser·p0.9999: 28.967 ms/op
                 createUser·p1.00:   31.195 ms/op

Iteration   3: 5.128 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.228 ms/op
                 createUser·p0.50:   4.866 ms/op
                 createUser·p0.90:   6.431 ms/op
                 createUser·p0.95:   7.307 ms/op
                 createUser·p0.99:   9.503 ms/op
                 createUser·p0.999:  27.927 ms/op
                 createUser·p0.9999: 31.687 ms/op
                 createUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178158
  mean =      5.386 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 78976 
    [ 5.000,  7.500) = 87670 
    [ 7.500, 10.000) = 9309 
    [10.000, 12.500) = 1450 
    [12.500, 15.000) = 372 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      5.112 ms/op
     p(90.0000) =      6.832 ms/op
     p(95.0000) =      7.930 ms/op
     p(99.0000) =     10.338 ms/op
     p(99.9000) =     21.982 ms/op
     p(99.9900) =     31.392 ms/op
     p(99.9990) =     32.153 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 13.756 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 5.203 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.047 ±(99.9%) 0.017 ms/op
Iteration   1: 5.023 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.817 ms/op
                 existUser·p0.50:   4.801 ms/op
                 existUser·p0.90:   6.300 ms/op
                 existUser·p0.95:   7.135 ms/op
                 existUser·p0.99:   9.339 ms/op
                 existUser·p0.999:  21.868 ms/op
                 existUser·p0.9999: 25.970 ms/op
                 existUser·p1.00:   26.837 ms/op

Iteration   2: 4.758 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   2.179 ms/op
                 existUser·p0.50:   4.596 ms/op
                 existUser·p0.90:   5.702 ms/op
                 existUser·p0.95:   6.398 ms/op
                 existUser·p0.99:   8.364 ms/op
                 existUser·p0.999:  13.854 ms/op
                 existUser·p0.9999: 24.987 ms/op
                 existUser·p1.00:   26.411 ms/op

Iteration   3: 4.643 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.909 ms/op
                 existUser·p0.50:   4.481 ms/op
                 existUser·p0.90:   5.538 ms/op
                 existUser·p0.95:   6.070 ms/op
                 existUser·p0.99:   8.348 ms/op
                 existUser·p0.999:  15.305 ms/op
                 existUser·p0.9999: 29.339 ms/op
                 existUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 199738
  mean =      4.803 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 78 
    [ 2.500,  5.000) = 137464 
    [ 5.000,  7.500) = 57340 
    [ 7.500, 10.000) = 3771 
    [10.000, 12.500) = 589 
    [12.500, 15.000) = 310 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.817 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      5.849 ms/op
     p(95.0000) =      6.603 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     14.848 ms/op
     p(99.9900) =     28.379 ms/op
     p(99.9990) =     31.851 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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
# Warmup Iteration   1: 12.588 ±(99.9%) 0.182 ms/op
# Warmup Iteration   2: 5.315 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.107 ±(99.9%) 0.018 ms/op
Iteration   1: 4.779 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.968 ms/op
                 getUser·p0.50:   4.489 ms/op
                 getUser·p0.90:   5.906 ms/op
                 getUser·p0.95:   7.029 ms/op
                 getUser·p0.99:   9.421 ms/op
                 getUser·p0.999:  15.450 ms/op
                 getUser·p0.9999: 24.475 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   2: 4.900 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.548 ms/op
                 getUser·p0.50:   4.686 ms/op
                 getUser·p0.90:   5.915 ms/op
                 getUser·p0.95:   6.840 ms/op
                 getUser·p0.99:   9.388 ms/op
                 getUser·p0.999:  16.106 ms/op
                 getUser·p0.9999: 25.847 ms/op
                 getUser·p1.00:   27.886 ms/op

Iteration   3: 5.329 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.335 ms/op
                 getUser·p0.50:   5.112 ms/op
                 getUser·p0.90:   6.406 ms/op
                 getUser·p0.95:   7.225 ms/op
                 getUser·p0.99:   9.454 ms/op
                 getUser·p0.999:  30.504 ms/op
                 getUser·p0.9999: 37.617 ms/op
                 getUser·p1.00:   38.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 192436
  mean =      4.992 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 117913 
    [ 5.000,  7.500) = 67306 
    [ 7.500, 10.000) = 5879 
    [10.000, 12.500) = 919 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.968 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      6.136 ms/op
     p(95.0000) =      7.037 ms/op
     p(99.0000) =      9.421 ms/op
     p(99.9000) =     18.006 ms/op
     p(99.9900) =     34.996 ms/op
     p(99.9990) =     38.085 ms/op
     p(99.9999) =     38.994 ms/op
    p(100.0000) =     38.994 ms/op


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
# Warmup Iteration   1: 19.743 ±(99.9%) 0.357 ms/op
# Warmup Iteration   2: 7.164 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 6.347 ±(99.9%) 0.028 ms/op
Iteration   1: 6.072 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.841 ms/op
                 listUser·p0.50:   5.792 ms/op
                 listUser·p0.90:   7.193 ms/op
                 listUser·p0.95:   8.110 ms/op
                 listUser·p0.99:   11.944 ms/op
                 listUser·p0.999:  28.040 ms/op
                 listUser·p0.9999: 33.751 ms/op
                 listUser·p1.00:   34.537 ms/op

Iteration   2: 6.180 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.490 ms/op
                 listUser·p0.50:   5.997 ms/op
                 listUser·p0.90:   7.315 ms/op
                 listUser·p0.95:   8.118 ms/op
                 listUser·p0.99:   10.207 ms/op
                 listUser·p0.999:  24.991 ms/op
                 listUser·p0.9999: 28.808 ms/op
                 listUser·p1.00:   29.229 ms/op

Iteration   3: 6.085 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   3.277 ms/op
                 listUser·p0.50:   5.833 ms/op
                 listUser·p0.90:   7.242 ms/op
                 listUser·p0.95:   8.282 ms/op
                 listUser·p0.99:   11.403 ms/op
                 listUser·p0.999:  19.427 ms/op
                 listUser·p0.9999: 26.607 ms/op
                 listUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 157079
  mean =      6.112 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 16548 
    [ 5.000,  7.500) = 128047 
    [ 7.500, 10.000) = 9676 
    [10.000, 12.500) = 1877 
    [12.500, 15.000) = 423 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.841 ms/op
     p(50.0000) =      5.865 ms/op
     p(90.0000) =      7.250 ms/op
     p(95.0000) =      8.167 ms/op
     p(99.0000) =     11.190 ms/op
     p(99.9000) =     24.052 ms/op
     p(99.9900) =     31.336 ms/op
     p(99.9990) =     34.537 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.922 ± 5.897  ops/ms
ClientPb.existUser                       thrpt       3   6.215 ± 2.113  ops/ms
ClientPb.getUser                         thrpt       3   5.977 ± 2.192  ops/ms
ClientPb.listUser                        thrpt       3   5.168 ± 3.250  ops/ms
ClientPb.createUser                       avgt       3   5.468 ± 2.058   ms/op
ClientPb.existUser                        avgt       3   5.237 ± 2.222   ms/op
ClientPb.getUser                          avgt       3   5.505 ± 3.349   ms/op
ClientPb.listUser                         avgt       3   6.281 ± 3.638   ms/op
ClientPb.createUser                     sample  178158   5.386 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.139           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.112           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.832           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.930           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.338           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.982           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.392           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.768           ms/op
ClientPb.existUser                      sample  199738   4.803 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.817           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.612           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.849           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.603           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.733           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.848           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.379           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.178           ms/op
ClientPb.getUser                        sample  192436   4.992 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.968           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.776           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.136           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.037           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.421           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.006           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.996           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.994           ms/op
ClientPb.listUser                       sample  157079   6.112 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.841           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.865           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.250           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.167           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.190           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.052           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.336           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.537           ms/op
