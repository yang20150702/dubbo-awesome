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
# Warmup Iteration   1: 1.565 ops/ms
# Warmup Iteration   2: 3.663 ops/ms
# Warmup Iteration   3: 7.290 ops/ms
Iteration   1: 7.505 ops/ms
Iteration   2: 7.833 ops/ms
Iteration   3: 7.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.776 ±(99.9%) 4.502 ops/ms [Average]
  (min, avg, max) = (7.505, 7.776, 7.989), stdev = 0.247
  CI (99.9%): [3.273, 12.278] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.186 ops/ms
# Warmup Iteration   2: 6.593 ops/ms
# Warmup Iteration   3: 7.673 ops/ms
Iteration   1: 8.070 ops/ms
Iteration   2: 8.230 ops/ms
Iteration   3: 8.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.163 ±(99.9%) 1.523 ops/ms [Average]
  (min, avg, max) = (8.070, 8.163, 8.230), stdev = 0.083
  CI (99.9%): [6.641, 9.686] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.127 ops/ms
# Warmup Iteration   2: 6.395 ops/ms
# Warmup Iteration   3: 7.556 ops/ms
Iteration   1: 7.369 ops/ms
Iteration   2: 7.576 ops/ms
Iteration   3: 7.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.577 ±(99.9%) 3.798 ops/ms [Average]
  (min, avg, max) = (7.369, 7.577, 7.785), stdev = 0.208
  CI (99.9%): [3.779, 11.374] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.099 ops/ms
# Warmup Iteration   2: 5.498 ops/ms
# Warmup Iteration   3: 6.581 ops/ms
Iteration   1: 6.589 ops/ms
Iteration   2: 6.620 ops/ms
Iteration   3: 6.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.677 ±(99.9%) 2.312 ops/ms [Average]
  (min, avg, max) = (6.589, 6.677, 6.822), stdev = 0.127
  CI (99.9%): [4.365, 8.989] (assumes normal distribution)


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
# Warmup Iteration   1: 14.218 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.809 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.381 ±(99.9%) 0.003 ms/op
Iteration   1: 4.005 ±(99.9%) 0.006 ms/op
Iteration   2: 4.098 ±(99.9%) 0.009 ms/op
Iteration   3: 4.058 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.054 ±(99.9%) 0.859 ms/op [Average]
  (min, avg, max) = (4.005, 4.054, 4.098), stdev = 0.047
  CI (99.9%): [3.194, 4.913] (assumes normal distribution)


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
# Warmup Iteration   1: 12.144 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.615 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.975 ±(99.9%) 0.007 ms/op
Iteration   1: 3.817 ±(99.9%) 0.006 ms/op
Iteration   2: 4.065 ±(99.9%) 0.006 ms/op
Iteration   3: 3.886 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.922 ±(99.9%) 2.334 ms/op [Average]
  (min, avg, max) = (3.817, 3.922, 4.065), stdev = 0.128
  CI (99.9%): [1.588, 6.257] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.748 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.958 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.126 ±(99.9%) 0.005 ms/op
Iteration   1: 4.162 ±(99.9%) 0.005 ms/op
Iteration   2: 4.057 ±(99.9%) 0.008 ms/op
Iteration   3: 4.016 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.078 ±(99.9%) 1.369 ms/op [Average]
  (min, avg, max) = (4.016, 4.078, 4.162), stdev = 0.075
  CI (99.9%): [2.710, 5.447] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.913 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.960 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.974 ±(99.9%) 0.006 ms/op
Iteration   1: 4.937 ±(99.9%) 0.008 ms/op
Iteration   2: 4.705 ±(99.9%) 0.017 ms/op
Iteration   3: 4.654 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.766 ±(99.9%) 2.744 ms/op [Average]
  (min, avg, max) = (4.654, 4.766, 4.937), stdev = 0.150
  CI (99.9%): [2.021, 7.510] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.742 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 5.462 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.640 ±(99.9%) 0.020 ms/op
Iteration   1: 4.187 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.776 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   5.513 ms/op
                 createUser·p0.99:   8.094 ms/op
                 createUser·p0.999:  11.731 ms/op
                 createUser·p0.9999: 26.860 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   2: 4.043 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.294 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   6.922 ms/op
                 createUser·p0.999:  26.243 ms/op
                 createUser·p0.9999: 28.675 ms/op
                 createUser·p1.00:   29.458 ms/op

Iteration   3: 4.093 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.178 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   6.980 ms/op
                 createUser·p0.999:  28.221 ms/op
                 createUser·p0.9999: 31.142 ms/op
                 createUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 233719
  mean =      4.107 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 389 
    [ 2.500,  5.000) = 219146 
    [ 5.000,  7.500) = 11887 
    [ 7.500, 10.000) = 1577 
    [10.000, 12.500) = 411 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 119 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     25.119 ms/op
     p(99.9900) =     30.581 ms/op
     p(99.9990) =     32.746 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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
# Warmup Iteration   1: 12.945 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 4.724 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.013 ms/op
Iteration   1: 3.947 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.960 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   6.668 ms/op
                 existUser·p0.999:  15.897 ms/op
                 existUser·p0.9999: 25.821 ms/op
                 existUser·p1.00:   26.837 ms/op

Iteration   2: 3.894 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.976 ms/op
                 existUser·p0.50:   3.912 ms/op
                 existUser·p0.90:   4.047 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  26.536 ms/op
                 existUser·p0.9999: 28.749 ms/op
                 existUser·p1.00:   29.524 ms/op

Iteration   3: 3.870 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   2.232 ms/op
                 existUser·p0.50:   3.854 ms/op
                 existUser·p0.90:   4.018 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  11.574 ms/op
                 existUser·p0.9999: 30.335 ms/op
                 existUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245780
  mean =      3.904 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 129 
    [ 2.500,  5.000) = 238917 
    [ 5.000,  7.500) = 5607 
    [ 7.500, 10.000) = 684 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.960 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     14.356 ms/op
     p(99.9900) =     29.360 ms/op
     p(99.9990) =     31.066 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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
# Warmup Iteration   1: 12.223 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.674 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.387 ±(99.9%) 0.016 ms/op
Iteration   1: 4.104 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.772 ms/op
                 getUser·p0.50:   3.883 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.841 ms/op
                 getUser·p0.99:   8.249 ms/op
                 getUser·p0.999:  24.183 ms/op
                 getUser·p0.9999: 26.752 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   2: 4.037 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.343 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   7.173 ms/op
                 getUser·p0.999:  13.351 ms/op
                 getUser·p0.9999: 28.261 ms/op
                 getUser·p1.00:   29.262 ms/op

Iteration   3: 4.283 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.448 ms/op
                 getUser·p0.50:   4.051 ms/op
                 getUser·p0.90:   4.981 ms/op
                 getUser·p0.95:   6.136 ms/op
                 getUser·p0.99:   8.749 ms/op
                 getUser·p0.999:  27.525 ms/op
                 getUser·p0.9999: 33.279 ms/op
                 getUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 231730
  mean =      4.139 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 214971 
    [ 5.000,  7.500) = 12573 
    [ 7.500, 10.000) = 3553 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      8.331 ms/op
     p(99.9000) =     24.248 ms/op
     p(99.9900) =     32.385 ms/op
     p(99.9990) =     33.599 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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
# Warmup Iteration   1: 13.099 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 5.463 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.974 ±(99.9%) 0.019 ms/op
Iteration   1: 4.768 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.337 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   9.234 ms/op
                 listUser·p0.999:  23.560 ms/op
                 listUser·p0.9999: 29.543 ms/op
                 listUser·p1.00:   31.588 ms/op

Iteration   2: 4.880 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   4.665 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   9.290 ms/op
                 listUser·p0.999:  17.629 ms/op
                 listUser·p0.9999: 23.044 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   3: 4.768 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.982 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   9.174 ms/op
                 listUser·p0.999:  16.613 ms/op
                 listUser·p0.9999: 19.507 ms/op
                 listUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199560
  mean =      4.805 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 161458 
    [ 5.000,  7.500) = 32882 
    [ 7.500, 10.000) = 3974 
    [10.000, 12.500) = 649 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     18.711 ms/op
     p(99.9900) =     27.823 ms/op
     p(99.9990) =     30.186 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.776 ± 4.502  ops/ms
ClientPb.existUser                       thrpt       3   8.163 ± 1.523  ops/ms
ClientPb.getUser                         thrpt       3   7.577 ± 3.798  ops/ms
ClientPb.listUser                        thrpt       3   6.677 ± 2.312  ops/ms
ClientPb.createUser                       avgt       3   4.054 ± 0.859   ms/op
ClientPb.existUser                        avgt       3   3.922 ± 2.334   ms/op
ClientPb.getUser                          avgt       3   4.078 ± 1.369   ms/op
ClientPb.listUser                         avgt       3   4.766 ± 2.744   ms/op
ClientPb.createUser                     sample  233719   4.107 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.178           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.686           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.153           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.487           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.119           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.581           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.834           ms/op
ClientPb.existUser                      sample  245780   3.904 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.960           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.174           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.522           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.316           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.356           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.360           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.261           ms/op
ClientPb.getUser                        sample  231730   4.139 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.448           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.546           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.331           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.248           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.385           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.882           ms/op
ClientPb.listUser                       sample  199560   4.805 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.337           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.267           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.224           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.711           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.823           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.588           ms/op
