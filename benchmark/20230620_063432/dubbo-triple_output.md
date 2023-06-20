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
# Warmup Iteration   1: 2.051 ops/ms
# Warmup Iteration   2: 5.650 ops/ms
# Warmup Iteration   3: 8.588 ops/ms
Iteration   1: 8.832 ops/ms
Iteration   2: 9.218 ops/ms
Iteration   3: 9.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.043 ±(99.9%) 3.566 ops/ms [Average]
  (min, avg, max) = (8.832, 9.043, 9.218), stdev = 0.195
  CI (99.9%): [5.477, 12.609] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.920 ops/ms
# Warmup Iteration   2: 8.512 ops/ms
# Warmup Iteration   3: 9.840 ops/ms
Iteration   1: 9.867 ops/ms
Iteration   2: 10.081 ops/ms
Iteration   3: 9.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.849 ±(99.9%) 4.393 ops/ms [Average]
  (min, avg, max) = (9.600, 9.849, 10.081), stdev = 0.241
  CI (99.9%): [5.456, 14.242] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.960 ops/ms
# Warmup Iteration   2: 8.424 ops/ms
# Warmup Iteration   3: 8.916 ops/ms
Iteration   1: 9.132 ops/ms
Iteration   2: 9.397 ops/ms
Iteration   3: 9.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.184 ±(99.9%) 3.499 ops/ms [Average]
  (min, avg, max) = (9.024, 9.184, 9.397), stdev = 0.192
  CI (99.9%): [5.685, 12.683] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.685 ops/ms
# Warmup Iteration   2: 6.924 ops/ms
# Warmup Iteration   3: 7.775 ops/ms
Iteration   1: 7.629 ops/ms
Iteration   2: 8.070 ops/ms
Iteration   3: 7.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.780 ±(99.9%) 4.591 ops/ms [Average]
  (min, avg, max) = (7.629, 7.780, 8.070), stdev = 0.252
  CI (99.9%): [3.189, 12.371] (assumes normal distribution)


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
# Warmup Iteration   1: 9.489 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.018 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.008 ms/op
Iteration   1: 3.527 ±(99.9%) 0.007 ms/op
Iteration   2: 3.483 ±(99.9%) 0.007 ms/op
Iteration   3: 3.350 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.453 ±(99.9%) 1.676 ms/op [Average]
  (min, avg, max) = (3.350, 3.453, 3.527), stdev = 0.092
  CI (99.9%): [1.777, 5.129] (assumes normal distribution)


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
# Warmup Iteration   1: 9.998 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.778 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.396 ±(99.9%) 0.004 ms/op
Iteration   1: 3.264 ±(99.9%) 0.005 ms/op
Iteration   2: 3.225 ±(99.9%) 0.012 ms/op
Iteration   3: 3.204 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.231 ±(99.9%) 0.560 ms/op [Average]
  (min, avg, max) = (3.204, 3.231, 3.264), stdev = 0.031
  CI (99.9%): [2.671, 3.791] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.831 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.863 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.704 ±(99.9%) 0.005 ms/op
Iteration   1: 3.435 ±(99.9%) 0.005 ms/op
Iteration   2: 3.465 ±(99.9%) 0.007 ms/op
Iteration   3: 3.517 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.472 ±(99.9%) 0.752 ms/op [Average]
  (min, avg, max) = (3.435, 3.472, 3.517), stdev = 0.041
  CI (99.9%): [2.720, 4.224] (assumes normal distribution)


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
# Warmup Iteration   1: 12.747 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.535 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.201 ±(99.9%) 0.007 ms/op
Iteration   1: 4.101 ±(99.9%) 0.014 ms/op
Iteration   2: 4.114 ±(99.9%) 0.009 ms/op
Iteration   3: 3.980 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.065 ±(99.9%) 1.355 ms/op [Average]
  (min, avg, max) = (3.980, 4.065, 4.114), stdev = 0.074
  CI (99.9%): [2.710, 5.420] (assumes normal distribution)


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
# Warmup Iteration   1: 10.771 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 3.931 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.799 ±(99.9%) 0.014 ms/op
Iteration   1: 3.455 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.536 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  25.140 ms/op
                 createUser·p0.9999: 31.973 ms/op
                 createUser·p1.00:   32.473 ms/op

Iteration   2: 3.546 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.135 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  12.403 ms/op
                 createUser·p0.9999: 28.180 ms/op
                 createUser·p1.00:   29.229 ms/op

Iteration   3: 3.582 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.313 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  26.327 ms/op
                 createUser·p0.9999: 37.421 ms/op
                 createUser·p1.00:   46.662 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272027
  mean =      3.527 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 264313 
    [ 5.000, 10.000) = 7073 
    [10.000, 15.000) = 329 
    [15.000, 20.000) = 24 
    [20.000, 25.000) = 46 
    [25.000, 30.000) = 154 
    [30.000, 35.000) = 56 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     23.985 ms/op
     p(99.9900) =     37.093 ms/op
     p(99.9990) =     39.059 ms/op
     p(99.9999) =     46.662 ms/op
    p(100.0000) =     46.662 ms/op


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
# Warmup Iteration   1: 9.778 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.925 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.460 ±(99.9%) 0.009 ms/op
Iteration   1: 3.394 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.616 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  20.808 ms/op
                 existUser·p0.9999: 24.044 ms/op
                 existUser·p1.00:   26.214 ms/op

Iteration   2: 3.423 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.339 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  23.561 ms/op
                 existUser·p0.9999: 25.843 ms/op
                 existUser·p1.00:   28.082 ms/op

Iteration   3: 3.349 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.671 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  8.558 ms/op
                 existUser·p0.9999: 31.818 ms/op
                 existUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282997
  mean =      3.388 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8416 
    [ 2.500,  5.000) = 269627 
    [ 5.000,  7.500) = 4311 
    [ 7.500, 10.000) = 275 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     11.469 ms/op
     p(99.9900) =     30.966 ms/op
     p(99.9990) =     32.943 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


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
# Warmup Iteration   1: 8.718 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.664 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.666 ±(99.9%) 0.013 ms/op
Iteration   1: 3.516 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.663 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  22.086 ms/op
                 getUser·p0.9999: 24.959 ms/op
                 getUser·p1.00:   26.673 ms/op

Iteration   2: 3.394 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  23.280 ms/op
                 getUser·p0.9999: 25.840 ms/op
                 getUser·p1.00:   27.460 ms/op

Iteration   3: 3.475 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.448 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  22.380 ms/op
                 getUser·p0.9999: 28.730 ms/op
                 getUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277332
  mean =      3.461 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8248 
    [ 2.500,  5.000) = 262057 
    [ 5.000,  7.500) = 5733 
    [ 7.500, 10.000) = 809 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 103 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      6.190 ms/op
     p(99.9000) =     22.118 ms/op
     p(99.9900) =     27.617 ms/op
     p(99.9990) =     29.102 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


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
# Warmup Iteration   1: 10.387 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.356 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.147 ±(99.9%) 0.014 ms/op
Iteration   1: 3.965 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.757 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.841 ms/op
                 listUser·p0.999:  20.152 ms/op
                 listUser·p0.9999: 23.658 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   2: 3.934 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   6.283 ms/op
                 listUser·p0.999:  15.892 ms/op
                 listUser·p0.9999: 17.883 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   3: 4.027 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  17.878 ms/op
                 listUser·p0.9999: 22.184 ms/op
                 listUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241469
  mean =      3.975 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 234029 
    [ 5.000,  7.500) = 5519 
    [ 7.500, 10.000) = 1057 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 255 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.757 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.072 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     22.671 ms/op
     p(99.9990) =     23.945 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.043 ± 3.566  ops/ms
ClientPb.existUser                       thrpt       3   9.849 ± 4.393  ops/ms
ClientPb.getUser                         thrpt       3   9.184 ± 3.499  ops/ms
ClientPb.listUser                        thrpt       3   7.780 ± 4.591  ops/ms
ClientPb.createUser                       avgt       3   3.453 ± 1.676   ms/op
ClientPb.existUser                        avgt       3   3.231 ± 0.560   ms/op
ClientPb.getUser                          avgt       3   3.472 ± 0.752   ms/op
ClientPb.listUser                         avgt       3   4.065 ± 1.355   ms/op
ClientPb.createUser                     sample  272027   3.527 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.965           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.005           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.985           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.093           ms/op
ClientPb.createUser:createUser·p1.00    sample          46.662           ms/op
ClientPb.existUser                      sample  282997   3.388 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.339           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.137           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.661           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.469           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.966           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.128           ms/op
ClientPb.getUser                        sample  277332   3.461 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.448           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.157           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.190           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.118           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.617           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.262           ms/op
ClientPb.listUser                       sample  241469   3.975 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.757           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.072           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.269           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.671           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.052           ms/op
