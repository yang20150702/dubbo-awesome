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
# Warmup Iteration   1: 1.649 ops/ms
# Warmup Iteration   2: 3.927 ops/ms
# Warmup Iteration   3: 7.894 ops/ms
Iteration   1: 7.947 ops/ms
Iteration   2: 8.859 ops/ms
Iteration   3: 8.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.505 ±(99.9%) 8.921 ops/ms [Average]
  (min, avg, max) = (7.947, 8.505, 8.859), stdev = 0.489
  CI (99.9%): [≈ 0, 17.427] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.454 ops/ms
# Warmup Iteration   2: 7.423 ops/ms
# Warmup Iteration   3: 8.748 ops/ms
Iteration   1: 9.203 ops/ms
Iteration   2: 9.204 ops/ms
Iteration   3: 9.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.259 ±(99.9%) 1.759 ops/ms [Average]
  (min, avg, max) = (9.203, 9.259, 9.370), stdev = 0.096
  CI (99.9%): [7.500, 11.018] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.401 ops/ms
# Warmup Iteration   2: 7.379 ops/ms
# Warmup Iteration   3: 8.464 ops/ms
Iteration   1: 8.731 ops/ms
Iteration   2: 8.714 ops/ms
Iteration   3: 8.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.753 ±(99.9%) 0.964 ops/ms [Average]
  (min, avg, max) = (8.714, 8.753, 8.813), stdev = 0.053
  CI (99.9%): [7.789, 9.717] (assumes normal distribution)


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
# Warmup Iteration   1: 2.073 ops/ms
# Warmup Iteration   2: 6.384 ops/ms
# Warmup Iteration   3: 7.281 ops/ms
Iteration   1: 7.366 ops/ms
Iteration   2: 7.429 ops/ms
Iteration   3: 7.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.433 ±(99.9%) 1.259 ops/ms [Average]
  (min, avg, max) = (7.366, 7.433, 7.504), stdev = 0.069
  CI (99.9%): [6.174, 8.693] (assumes normal distribution)


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
# Warmup Iteration   1: 12.818 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.475 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.010 ms/op
Iteration   1: 3.633 ±(99.9%) 0.013 ms/op
Iteration   2: 3.659 ±(99.9%) 0.004 ms/op
Iteration   3: 3.599 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.630 ±(99.9%) 0.548 ms/op [Average]
  (min, avg, max) = (3.599, 3.630, 3.659), stdev = 0.030
  CI (99.9%): [3.082, 4.179] (assumes normal distribution)


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
# Warmup Iteration   1: 11.025 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.005 ms/op
Iteration   1: 3.445 ±(99.9%) 0.012 ms/op
Iteration   2: 3.532 ±(99.9%) 0.010 ms/op
Iteration   3: 3.460 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.479 ±(99.9%) 0.847 ms/op [Average]
  (min, avg, max) = (3.445, 3.479, 3.532), stdev = 0.046
  CI (99.9%): [2.632, 4.326] (assumes normal distribution)


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
# Warmup Iteration   1: 12.207 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.876 ±(99.9%) 0.007 ms/op
Iteration   1: 3.802 ±(99.9%) 0.011 ms/op
Iteration   2: 3.706 ±(99.9%) 0.004 ms/op
Iteration   3: 3.691 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.733 ±(99.9%) 1.099 ms/op [Average]
  (min, avg, max) = (3.691, 3.733, 3.802), stdev = 0.060
  CI (99.9%): [2.634, 4.832] (assumes normal distribution)


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
# Warmup Iteration   1: 13.989 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.866 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.320 ±(99.9%) 0.010 ms/op
Iteration   1: 4.308 ±(99.9%) 0.008 ms/op
Iteration   2: 4.286 ±(99.9%) 0.006 ms/op
Iteration   3: 4.375 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.323 ±(99.9%) 0.842 ms/op [Average]
  (min, avg, max) = (4.286, 4.323, 4.375), stdev = 0.046
  CI (99.9%): [3.481, 5.166] (assumes normal distribution)


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
# Warmup Iteration   1: 12.812 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.660 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.017 ms/op
Iteration   1: 3.576 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.436 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.111 ms/op
                 createUser·p0.999:  23.888 ms/op
                 createUser·p0.9999: 26.347 ms/op
                 createUser·p1.00:   26.903 ms/op

Iteration   2: 3.615 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.513 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   6.423 ms/op
                 createUser·p0.999:  25.805 ms/op
                 createUser·p0.9999: 33.423 ms/op
                 createUser·p1.00:   34.210 ms/op

Iteration   3: 3.624 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.782 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   6.743 ms/op
                 createUser·p0.999:  11.403 ms/op
                 createUser·p0.9999: 35.019 ms/op
                 createUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 266278
  mean =      3.605 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2361 
    [ 2.500,  5.000) = 253684 
    [ 5.000,  7.500) = 8861 
    [ 7.500, 10.000) = 913 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 37 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.436 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     14.151 ms/op
     p(99.9900) =     34.038 ms/op
     p(99.9990) =     35.740 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


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
# Warmup Iteration   1: 9.592 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.686 ±(99.9%) 0.011 ms/op
Iteration   1: 3.583 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.817 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  24.429 ms/op
                 existUser·p0.9999: 29.221 ms/op
                 existUser·p1.00:   30.474 ms/op

Iteration   2: 3.493 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.722 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   3.940 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  12.190 ms/op
                 existUser·p0.9999: 27.127 ms/op
                 existUser·p1.00:   28.312 ms/op

Iteration   3: 3.619 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.548 ms/op
                 existUser·p0.50:   3.424 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   4.948 ms/op
                 existUser·p0.99:   7.987 ms/op
                 existUser·p0.999:  27.083 ms/op
                 existUser·p0.9999: 32.085 ms/op
                 existUser·p1.00:   32.637 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 269134
  mean =      3.564 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7851 
    [ 2.500,  5.000) = 253583 
    [ 5.000,  7.500) = 6064 
    [ 7.500, 10.000) = 1079 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     13.055 ms/op
     p(99.9900) =     30.611 ms/op
     p(99.9990) =     32.262 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


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
# Warmup Iteration   1: 12.083 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.904 ±(99.9%) 0.014 ms/op
Iteration   1: 3.588 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.581 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  23.753 ms/op
                 getUser·p0.9999: 27.200 ms/op
                 getUser·p1.00:   31.457 ms/op

Iteration   2: 3.595 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.481 ms/op
                 getUser·p0.50:   3.465 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  23.953 ms/op
                 getUser·p0.9999: 27.496 ms/op
                 getUser·p1.00:   28.705 ms/op

Iteration   3: 3.551 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   5.087 ms/op
                 getUser·p0.999:  26.314 ms/op
                 getUser·p0.9999: 30.935 ms/op
                 getUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268097
  mean =      3.578 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 358 
    [ 2.500,  5.000) = 262303 
    [ 5.000,  7.500) = 4144 
    [ 7.500, 10.000) = 774 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 144 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.481 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     23.983 ms/op
     p(99.9900) =     29.490 ms/op
     p(99.9990) =     33.309 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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
# Warmup Iteration   1: 15.123 ±(99.9%) 0.222 ms/op
# Warmup Iteration   2: 4.915 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.103 ±(99.9%) 0.013 ms/op
Iteration   1: 3.989 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.417 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  21.004 ms/op
                 listUser·p0.9999: 25.166 ms/op
                 listUser·p1.00:   27.099 ms/op

Iteration   2: 3.948 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 20.644 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 3.889 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.007 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  15.532 ms/op
                 listUser·p0.9999: 18.008 ms/op
                 listUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243423
  mean =      3.942 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 235741 
    [ 5.000,  7.500) = 5748 
    [ 7.500, 10.000) = 1052 
    [10.000, 12.500) = 278 
    [12.500, 15.000) = 228 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     16.377 ms/op
     p(99.9900) =     23.536 ms/op
     p(99.9990) =     26.846 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.505 ± 8.921  ops/ms
ClientPb.existUser                       thrpt       3   9.259 ± 1.759  ops/ms
ClientPb.getUser                         thrpt       3   8.753 ± 0.964  ops/ms
ClientPb.listUser                        thrpt       3   7.433 ± 1.259  ops/ms
ClientPb.createUser                       avgt       3   3.630 ± 0.548   ms/op
ClientPb.existUser                        avgt       3   3.479 ± 0.847   ms/op
ClientPb.getUser                          avgt       3   3.733 ± 1.099   ms/op
ClientPb.listUser                         avgt       3   4.323 ± 0.842   ms/op
ClientPb.createUser                     sample  266278   3.605 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.436           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.453           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.645           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.463           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.151           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.038           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.241           ms/op
ClientPb.existUser                      sample  269134   3.564 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.548           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.453           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.440           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.783           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.055           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.611           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.637           ms/op
ClientPb.getUser                        sample  268097   3.578 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.481           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.473           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.182           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.218           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.983           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.490           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.882           ms/op
ClientPb.listUser                       sample  243423   3.942 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.417           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.100           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.988           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.377           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.536           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.099           ms/op
