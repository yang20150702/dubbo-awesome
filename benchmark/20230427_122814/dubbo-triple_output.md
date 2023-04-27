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
# Warmup Iteration   1: 1.708 ops/ms
# Warmup Iteration   2: 3.887 ops/ms
# Warmup Iteration   3: 7.284 ops/ms
Iteration   1: 7.198 ops/ms
Iteration   2: 7.879 ops/ms
Iteration   3: 7.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.590 ±(99.9%) 6.425 ops/ms [Average]
  (min, avg, max) = (7.198, 7.590, 7.879), stdev = 0.352
  CI (99.9%): [1.165, 14.015] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.243 ops/ms
# Warmup Iteration   2: 6.947 ops/ms
# Warmup Iteration   3: 7.974 ops/ms
Iteration   1: 8.536 ops/ms
Iteration   2: 8.239 ops/ms
Iteration   3: 7.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.202 ±(99.9%) 6.465 ops/ms [Average]
  (min, avg, max) = (7.830, 8.202, 8.536), stdev = 0.354
  CI (99.9%): [1.737, 14.667] (assumes normal distribution)


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
# Warmup Iteration   1: 2.210 ops/ms
# Warmup Iteration   2: 6.526 ops/ms
# Warmup Iteration   3: 7.417 ops/ms
Iteration   1: 7.828 ops/ms
Iteration   2: 7.657 ops/ms
Iteration   3: 8.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.854 ±(99.9%) 3.840 ops/ms [Average]
  (min, avg, max) = (7.657, 7.854, 8.076), stdev = 0.210
  CI (99.9%): [4.013, 11.694] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.120 ops/ms
# Warmup Iteration   2: 4.753 ops/ms
# Warmup Iteration   3: 6.445 ops/ms
Iteration   1: 6.388 ops/ms
Iteration   2: 6.767 ops/ms
Iteration   3: 6.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.666 ±(99.9%) 4.439 ops/ms [Average]
  (min, avg, max) = (6.388, 6.666, 6.842), stdev = 0.243
  CI (99.9%): [2.227, 11.105] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 13.250 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.111 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.010 ms/op
Iteration   1: 3.997 ±(99.9%) 0.008 ms/op
Iteration   2: 3.832 ±(99.9%) 0.013 ms/op
Iteration   3: 3.901 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.910 ±(99.9%) 1.510 ms/op [Average]
  (min, avg, max) = (3.832, 3.910, 3.997), stdev = 0.083
  CI (99.9%): [2.400, 5.420] (assumes normal distribution)


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
# Warmup Iteration   1: 12.775 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.510 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.003 ms/op
Iteration   1: 4.024 ±(99.9%) 0.006 ms/op
Iteration   2: 3.708 ±(99.9%) 0.010 ms/op
Iteration   3: 3.790 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.841 ±(99.9%) 2.988 ms/op [Average]
  (min, avg, max) = (3.708, 3.841, 4.024), stdev = 0.164
  CI (99.9%): [0.853, 6.829] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 14.087 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.677 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.170 ±(99.9%) 0.009 ms/op
Iteration   1: 4.334 ±(99.9%) 0.010 ms/op
Iteration   2: 3.911 ±(99.9%) 0.011 ms/op
Iteration   3: 3.979 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.075 ±(99.9%) 4.146 ms/op [Average]
  (min, avg, max) = (3.911, 4.075, 4.334), stdev = 0.227
  CI (99.9%): [≈ 0, 8.221] (assumes normal distribution)


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
# Warmup Iteration   1: 14.936 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.633 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.883 ±(99.9%) 0.011 ms/op
Iteration   1: 4.692 ±(99.9%) 0.014 ms/op
Iteration   2: 4.768 ±(99.9%) 0.012 ms/op
Iteration   3: 4.508 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.656 ±(99.9%) 2.441 ms/op [Average]
  (min, avg, max) = (4.508, 4.656, 4.768), stdev = 0.134
  CI (99.9%): [2.216, 7.097] (assumes normal distribution)


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
# Warmup Iteration   1: 13.496 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 5.282 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.630 ±(99.9%) 0.021 ms/op
Iteration   1: 4.374 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.491 ms/op
                 createUser·p0.50:   4.108 ms/op
                 createUser·p0.90:   5.308 ms/op
                 createUser·p0.95:   6.529 ms/op
                 createUser·p0.99:   8.946 ms/op
                 createUser·p0.999:  13.304 ms/op
                 createUser·p0.9999: 27.209 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   2: 4.018 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.864 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   7.046 ms/op
                 createUser·p0.999:  25.507 ms/op
                 createUser·p0.9999: 28.548 ms/op
                 createUser·p1.00:   29.622 ms/op

Iteration   3: 4.104 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   6.927 ms/op
                 createUser·p0.999:  31.785 ms/op
                 createUser·p0.9999: 36.110 ms/op
                 createUser·p1.00:   36.504 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 230753
  mean =      4.160 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 465 
    [ 2.500,  5.000) = 210037 
    [ 5.000,  7.500) = 17427 
    [ 7.500, 10.000) = 1927 
    [10.000, 12.500) = 479 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 43 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      8.020 ms/op
     p(99.9000) =     25.919 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     36.443 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


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
# Warmup Iteration   1: 13.308 ±(99.9%) 0.210 ms/op
# Warmup Iteration   2: 4.532 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.038 ±(99.9%) 0.013 ms/op
Iteration   1: 4.076 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.462 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.809 ms/op
                 existUser·p0.95:   5.636 ms/op
                 existUser·p0.99:   8.348 ms/op
                 existUser·p0.999:  23.928 ms/op
                 existUser·p0.9999: 27.230 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   2: 3.978 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.585 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   4.588 ms/op
                 existUser·p0.95:   5.194 ms/op
                 existUser·p0.99:   7.064 ms/op
                 existUser·p0.999:  12.485 ms/op
                 existUser·p0.9999: 27.489 ms/op
                 existUser·p1.00:   27.984 ms/op

Iteration   3: 3.787 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.876 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  11.092 ms/op
                 existUser·p0.9999: 28.901 ms/op
                 existUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 243198
  mean =      3.943 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 255 
    [ 2.500,  5.000) = 229631 
    [ 5.000,  7.500) = 11096 
    [ 7.500, 10.000) = 1608 
    [10.000, 12.500) = 324 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 125 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     15.824 ms/op
     p(99.9900) =     28.180 ms/op
     p(99.9990) =     29.535 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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
# Warmup Iteration   1: 12.818 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.847 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.013 ms/op
Iteration   1: 4.224 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.933 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.669 ms/op
                 getUser·p0.95:   7.225 ms/op
                 getUser·p0.99:   10.404 ms/op
                 getUser·p0.999:  24.805 ms/op
                 getUser·p0.9999: 26.851 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   2: 4.168 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.663 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   4.915 ms/op
                 getUser·p0.95:   5.628 ms/op
                 getUser·p0.99:   8.421 ms/op
                 getUser·p0.999:  13.161 ms/op
                 getUser·p0.9999: 35.629 ms/op
                 getUser·p1.00:   36.176 ms/op

Iteration   3: 4.144 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.034 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   5.374 ms/op
                 getUser·p0.99:   7.479 ms/op
                 getUser·p0.999:  29.479 ms/op
                 getUser·p0.9999: 33.433 ms/op
                 getUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 229585
  mean =      4.178 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 211149 
    [ 5.000,  7.500) = 12985 
    [ 7.500, 10.000) = 3916 
    [10.000, 12.500) = 979 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.663 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     24.983 ms/op
     p(99.9900) =     33.885 ms/op
     p(99.9990) =     36.091 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


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
# Warmup Iteration   1: 15.024 ±(99.9%) 0.232 ms/op
# Warmup Iteration   2: 5.537 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.890 ±(99.9%) 0.016 ms/op
Iteration   1: 4.875 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.446 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  22.590 ms/op
                 listUser·p0.9999: 25.031 ms/op
                 listUser·p1.00:   25.559 ms/op

Iteration   2: 4.676 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   8.847 ms/op
                 listUser·p0.999:  18.514 ms/op
                 listUser·p0.9999: 21.272 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   3: 4.862 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.693 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  17.138 ms/op
                 listUser·p0.9999: 22.020 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199784
  mean =      4.803 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 159613 
    [ 5.000,  7.500) = 33783 
    [ 7.500, 10.000) = 4800 
    [10.000, 12.500) = 861 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.446 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      5.358 ms/op
     p(95.0000) =      6.136 ms/op
     p(99.0000) =      9.503 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     24.315 ms/op
     p(99.9990) =     25.134 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.590 ± 6.425  ops/ms
ClientPb.existUser                       thrpt       3   8.202 ± 6.465  ops/ms
ClientPb.getUser                         thrpt       3   7.854 ± 3.840  ops/ms
ClientPb.listUser                        thrpt       3   6.666 ± 4.439  ops/ms
ClientPb.createUser                       avgt       3   3.910 ± 1.510   ms/op
ClientPb.existUser                        avgt       3   3.841 ± 2.988   ms/op
ClientPb.getUser                          avgt       3   4.075 ± 4.146   ms/op
ClientPb.listUser                         avgt       3   4.656 ± 2.441   ms/op
ClientPb.createUser                     sample  230753   4.160 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.135           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.899           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.020           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.919           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.144           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.504           ms/op
ClientPb.existUser                      sample  243198   3.943 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.462           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.497           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.079           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.291           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.824           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.180           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.147           ms/op
ClientPb.getUser                        sample  229585   4.178 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.663           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.751           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.997           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.897           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.983           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.885           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.176           ms/op
ClientPb.listUser                       sample  199784   4.803 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.446           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.136           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.503           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.333           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.315           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.559           ms/op
